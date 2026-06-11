<figure markdown>
![CDM](img/arbvacc_library_hero_cdm.jpg)
</figure>

## What is CDM?
CDM (Collaborative Decision Making), manages demand and capacity across the network by coordinating departure slots, regulating outbound flow rates, and adjusting traffic patterns to prevent sector or airport overload. By providing a structured approach to traffic sequencing and delay management, CDM ensures smoother operations and more consistent handling during high-traffic conditions and major events.

## Definitions

| Abbreviation| Description                          |
| :---------: | ------------------------------------ |
| `EOBT`      | Estimated off block time             |
| `TOBT`      | Target off block time                |
| `TSAT`      | Target Start-Up Approval Time        |
| `TSAC`      | Target Start-Up Approval Communicated|
| `ASAT`      | Actual Start-Up Approval Time        |
| `ASRT`      | Actual Start-Up Request Time         |
| `TTOT`      | Target Take Off Time                 |  
| `CTOT`      | Calculated Take Off Time             |


### Activating CDM
1. The plugin is split into 2 roles, "master" and "slave". The "master" should be the lowest ATC position, usually delivery.

    When CDM is in use, an aerodrome should always have master, **however only 1 master per aerodrome is permitted**. Controllers may be the master at 2 airports if covering topdown, simply use the command below.

    `.cdm master {airport}` should be used to become the master of the selected aerodrome.

2. Using the CDM Master Panel, click on the aerodrome that you are opening (if you are controlling TMA and above, you are able to click multiple aerodromes) and wait until the aerodrome turns green. This indicates that this aerodrome is active with CDM.

<figure markdown>
![CDM: Master Panel](img/cdm_master_panel.png)
</figure>
<figure markdown>
![CDM: Active Master Panel](img/cdm_active.png)
</figure>

### Controller Change

During a controller handover, the current master (old controller) will change to a slave using `.cdm slave {airport}`, the new controller will then use the `.cdm master {airport}` command to become the new master. Once the new master has done this, the new controller will also need to run the `.cdm resetmaster {airport}` command.

## Commands

| Command                                            | Description                                                                                 |
| :------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| `.cdm resetmaster {airport}`                       | Resets the master for the new controller                                                    |
| `.cdm refresh`                                     | Force the refresh phase to do it now.                                                       |
| `.cdm master {airport}`                            | Become the master of the selected airport.                                                  |
| `.cdm slave {airport}`                             | Turn back to slave of the selected airport.                                                 |
| `.cdm customdelay {airport}/{runway} {time-start}` | Moves all TSATs for the selected airport and runway. Use time **9999** to remove the delay. |
| `.cdm lvo`                                         | Toggle LVP's on or off.                                                                     |
| `.cdm recover {airport}`                           | In case of CTD (crashed to desktop), it tries to recover the latest time status backed up in the server.      |
| `.cdm help`                                        | Sends a message with the available commands.                                                |

## Functions and Colours

### TOBT

If there is no existing TOBT, to add a TOBT, click on the column of the aircraft to set the current time as the TOBT. 

| Colour                                              |                 |
| :-------------------------------------------------- | :-------------- |
| ![Light Green](<img/light green.svg>) `LIGHT GREEN` | Before TOBT -5. |
| ![Dark Green](<img/dark green.svg>) `DARK GREEN`    | TOBT -5 to -2   |
| ![Yellow](img/yellow.svg) `YELLOW`                  | TOBT -1         |

### TSAT

TSAT is defined as the TTOT minus the taxi time.

| Colour                                              |                     |
| :-------------------------------------------------- | :------------------ |
| ![Light Green](<img/light green.svg>) `LIGHT GREEN` | TOBT -35 to TSAT -5 |
| ![Dark Green](<img/dark green.svg>) `DARK GREEN`    | TSAT -5 to +5       |
| ![Yellow](img/yellow.svg) `YELLOW`                  | TSAT +5 to +6       |

### CTOT

Shows the aircraft's CTOT

| Colour                              |                   |
| :---------------------------------- | :---------------- |
| ![Green](img/green.svg) `GREEN`     | CDM Server CTOT  |
| ![Orange](img/orange.svg) `ORANGE`  | Manual/Event CTOT |
| ![Red](img/red.svg) `RED`           | Flow/CAD CTOT     |

### NET

Shows the status from the CDM Network

| Colour                       |                                            |
| :--------------------------- | :----------------------------------------- |
| ![REA](img/REA.svg) `REA`    | Sends a REA message                        |
| ![PRIO](img/PRIO.svg) `PRIO` | Sets aircraft to top priority              |
| ![SUSP](img/SUSP.svg) `SUSP` | When an aircraft's flightplan is suspended |


## Usage

### Delivery (DEL)

When CDM is in use, pilot's should call for clearance as normal, however DEL should inform the pilot of their TSAT.

!!! info "Phraseology"

    UAE101, readback correct, QNH 1001 information A is current, TSAT 1203


When the pilot calls for start, the master should left click the TOBT column to generate timings (if not already there).
If the TSAT of the aircraft is ±5 minutes, shown in a ![Dark Green](<img/dark green.svg>) `DARK GREEN` colour, then the aircraft should be handed off to GMC.

!!! info "Phraseology"

    UAE101, hold position, contact ground 118.350

If the aircraft calls prior to the ±5 minute window, shown in a ![Light Green](<img/light green.svg>) `LIGHT GREEN` colour, then the aircraft should be told to hold position and a TSAT should be passed on.

!!! info "Phraseology"

    UAE101, TSAT 1203, hold position

!!! warning

    When handing off from DEL to GMC, DEL should set the status of the aircraft to "FREQ".


**Missed Slot**

If the aircraft is not marked with "FREQ" before TSAT +6, CDM will determine the aircraft as suspended shown by ![SUSP](img/SUSP.svg) `SUSP` in the NET column. When the aircraft calls ready for start the process is to be as normal where we left click the TOBT column to regenerate timings (as shown above).


### Ground Movement Control (GMC)

When an aircraft calls for start, GMC should confirm that the TSAT is within ±5 minutes, shown ![Dark Green](<img/dark green.svg>) `DARK GREEN` colour, before giving push and start.


### Tower (AIR)

The AIR controller should make use of the TTOT/CTOT timings to determine the departure order of aircraft.


## Pilot Submitted TOBT

Pilots are able to submit their own slot (TOBT) time through [vats.im/vdgs](https://vats.im/vdgs). Through this system, pilots are able to manually input their TOBT and view their TTOT/CTOT among other information.

## Frequently Asked Questions
??? Question: "What is the difference between TOBT and TSAT?"
     TOBT is the time the pilot would like to push without delays or traffic taken into consideration. TSAT includes all of this, the time the pilot would like to push added with delays, SID intervals as well as traffic around the Gulf.

??? Question: "Does white mean they have pushed on time?"
     If there TOBT/TSAT is showing white, it just means that they have pushed regardless of whether it was on time or not.

??? Question: "Do pilots NEED to submit their TOBT via the link?"
     The answer is NO! If the aerodrome is quiet and it won't affect you, when they call for push, just follow procedures and left click the TOBT column to add their timings and you can push them!
     

---
