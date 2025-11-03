# 3. Departure Clearance Procedures
## 3.1 General provisions
Airways clearance/Ground Movement Planner (GMP) is responsible for validating routes and shall provide IFR clearance to departing aircraft. The controller shall assign the correct departure procedure to the aircraft based on the first point that is filed on the flight plan.

Where the flight plan contains an invalid route, level or departure procedure, GMP must ensure that the error is corrected before the aircraft is given its clearance.

GMP is also responsible for minimizing taxiway delays and taxiway congestion for departing aircraft. During times of increased departure activity, aircraft are held at the gate to save fuel and lessen taxiway congestion.

## 3.2 Departure clearance
### 3.2.1 General
GMP is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the following information on first contact: 

-	Callsign;
-	Aircraft type; 
-	Parking stand;
-	Reporting “Ready to Push and Start”

GMP shall instruct pilots to monitor the appropriate Ground Movement Controller (GMC) frequency as per the pilot's location and standby for ATC call.

GMC shall inform aircraft that are ready for pushback of any delay exceeding 5 minutes and provide an estimate. If no contact is made by ATC after 5 minutes of monitoring pilots shall contact Ground Movement Control to receive an estimate for pushback and start.

To facilitate the most expeditious movement of ready aircraft, pilots not ready to pushback and start when instructed to do so by ATC shall expect to wait for further pushback instructions.

!!! warning
      The **FREQ** tag within Euroscope should be used only when a pilot has been instructed to monitor the next frequency. This will instruct next controller that the traffic is ready and expecting their call to push and start.

### 3.2.2 Information contained in a departure clearance
An IFR clearance shall be in the following format:

-	Callsign;
-	Destination;
-	Departure procedure;
-	Initially cleared altitude;
-	Departure frequency;
-	Assigned SSR code

Aircraft shall be instructed to change frequency after departure in the following manner:

<figure markdown>
| Runway Configuration | Handoff Station | Frequency |
|:--------------------:|:---------------:|:---------:|
|      31s             |    APP W        | 128.100   |
|      13s             |    APP C        | 124.400   |

  <figcaption>Table 2-1: Departure Handoffs</figcaption>
</figure>

When APP W is offline all handoffs shall be to APP C or as appropriate.

!!! example
    **Pilot**: "Abu Dhabi Delivery, ETD11 SUPER, type A380, stand 622, Information A, requesting IFR clearance to London, fully ready for push and start."
    
    **ATC**: "ETD11, Abu Dhabi Delivery, cleared to London via DAXIB 1K, maintain altitude 5000ft, when airborne contact Abu Dhabi Radar on 128.100, Squawk 3432."
    
    **Pilot**: "Cleared to London via DAXIB 1K, maintain altitude 5000ft, when airborne contact Abu Dhabi Radar on 128.100, Squawk 3432, ETD11."

    **ATC**: ETD11, readback correct. Monitor Abu Dhabi Ground on 120.425"
    
!!!info
    GMP must obtain a full readback of the clearance. If the pilot does not report the current ATIS letter on first contact, GMP shall pass the current ATIS letter and QNH.

### 3.2.3 Datalink clearance (DCL)
Aircraft clearance may also be delivered by DCL. This type of clearance reduces controller workload and frequency congestion. For suitably equipped aircraft, this will be through the ACARS system on board the aircraft.

!!!info
    Controllers shall ensure that DCL is available to be used at all times.

### 3.2.4 Aircraft requiring a reroute
Aircraft requiring a reroute shall not be given a PDC/DCL. Instead, a voice clearance must be used. This shall be communicated by ACARS datalink message or on frequency. 

!!!info
    Controllers shall use best judgement and task prioritisation to notify pilots of invalid flightplans.

### 3.2.5 Voice clearance
Aircraft requesting clearance via voice should be given a voice clearance as per the format in 3.2.2.

## 3.3 Departure Procedures
### 3.3.1 RNAV Standard instrument departures
Abu Dhabi primarily uses RNAV standard instrument departures (SIDs) and is the preferred departure type for IFR aircraft. Departing aircraft shall be assigned an appropriate RNAV departure according to the first fix in the flight plan and runways in use.

!!! info
      All departures from ***31L/13R*** have an initial climb of **5000ft** and departures from ***31R/13L*** have an initial climb of **4000ft**

<figure markdown>
|    Fix    | RWY 13L | RWY 13R | RWY 31L     | RWY 31R   |
|-----------|---------|---------|-------------|-----------|
| **ATUDO** | 5F      | 5G      | 4K/1U       | 3P        |
| **BOSEV** | 1F      | 1G      | 1K          | 1P        |
| **DAXIB** | 1F      | 1G      | 1K          | 1P        |
| **KANIP** | 3F      | 3G      | 4K/2U       | 1N/3P     |
| **LORID** | 1F      | 1G      | 2K          | 1P        |
| **MEKRI** | 1F      | 1G      | 2K          | 1P        |
| **ORNEL** | 1F      | 1G      | 2K/1U       | 1P        |
| **TULON** | 1F      | 1G      | 2K          | 1P        |

  <figcaption>Table 2-2: RNAV SIDs</figcaption>
</figure>

### 3.3.2 Simultaneous parallel instrument departures
Parallel runways may be used for parralel instrument departures as follows:

- Both runways are used exclusively for departure (independent parallel departures)
- One runway is used exclusively for departures while the other runway is used for a mixture of arrivals and departures (semi mixed operations)
- Both runways are used for mixed arrivals and departures (mixed operations)

!!!info
      The design of the SIDs permit simultaneous departures from all runway pairs because the departure tracks diverge more than 15 degrees and;
    
      A minimum of 3NM of separation will be observed between successive departures from the same runway direciton.

!!!note
    Refer to Section 4.4.1 of "Manual for Air Traffic Services - Part 1" under "Foundations" for more information.

!!!note
    Simulataneous parallel departures are available in all weather conditions.

The following conditions are required in the application of this standard between succeeding departing aircraft:

- ATS surveillance systems are used in the provision of aerodrome control service to establish surveillance separation between succeeding departing aircraft.
- Vertical separation shall be applied between successive departures when the following aircraft has a closing airspeed.
  
#### 3.3.2.1 Runway 31 operations
When simultaneous independent parallel departures are in use; the following SIDs shall be used for runway 31 operations:

<figure markdown>
| Runway 31L | Runway 31R |
|:----------:|:----------:|
|  MEKRI 2K  |  LORID 1P  |
|  BOSEV 1K  |  TULON 1P  |
|  DAXIB 1K  |  ATUDO 3P  |
|            |  KANIP 1N  |
|            |  ORNEL 1P  |

  <figcaption>Table 2-3: Simultaneous independent departures (31 configuration)</figcaption>
</figure>

#### 3.3.2.2 Runway 13 operations
When simultaneous independent parallel departures are in use; the following SIDs shall be used for runway 13 operations:

<figure markdown>
| Runway 13L | Runway 13R |
|:----------:|:----------:|
|  DAXIB 1F  |  MEKRI 1G  |
|  LORID 1F  |  BOSEV 1G  |
|  TULON 1F  |  ORNEL 1G  |
|  ATUDO 5F  |  KANIP 3G  |

  <figcaption>Table 2-4: Simultaneous independent departures (13 configuration)</figcaption>
</figure>

!!! warning
    Until further notice as of August 2025, the following SIDs are temporarily suspended until further notice as per OMAA NOTAMS:
    
    ***ATUDO 4K, KANIP 2U/3P, ORNEL 2K*** 
   
### 3.3.3 Radar departures
The radar departure procedure shall be used when aircraft are unable to accept an RNAV departure, such as one with outdated nav data. Whereas RNAV departures follow a prescribed track until leaving the Abu Dhabi Departures airspace, radar departures are given radar vectors to the first fix.

In the take-off clearance. Air Control (AIR) may assign a heading based on the departure runway to facilitate independent departure operations.

A radar departure clearance shall contain the following information:

- Callsign
- Destination
- Radar departure
- Runway
- Initial climb
- Assigned SSR code

!!! example
      "ETD77, Abu Dhabi delivery, cleared to Amsterdam, runway 31R, expect radar vectors, maintain altitude 4000ft, when airborne contact Abu Dhabi radar 128.100, squawk 3421"

!!! note
      Aircraft on radar departure shall have the text **RDR** inserted to the scratchpad section of their entry on the departure list.

## 3.4 Rerouting aircraft and standard routes
An aircraft shall be issued a reroute by GMP if the pilot’s route doesn’t comply with the standard routes laid out in Table 2-5. 

Several routing restrictions exist within UAE airspace and must be complied with when issuing a departure clearance. 

If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged.

!!! note
    The Arabian vACC Operations Department maintains an up-to-date route database on SimBrief. These routes can be accessed by selecting the ***"User Submitted Routes"*** option, highlighted in purple, when planning a flight.

<figure markdown>
| Destination                                                    | Level Restriction         | Routing                                         | Remarks                                           |
|---------------------------------------------------------------|--------------------------|-------------------------------------------------|---------------------------------------------------|
| OIKB and beyond                                               | -                        | TULON M318 GABKO                                | -                                                 |
| Muscat FIR and beyond                                         | -                        | KANIP N318 LABRI                                | Does not apply to traffic landing at OOMS, OOMN and OOSH |
| OOMS, OOMN and OOSH                                           | -                        | ORNEL N685 RETAS                                | -                                                 |
| Sanaa FIR and Jeddah FIR                                      | -                        | ORNEL T560 ELUDA G783 TANSU                     | -                                                 |
| Sanaa FIR and Jeddah FIR                                      | -                        | ORNEL T560 ELUDA G783 RIGIL M628 PEKEM          | -                                                 |
| Sanaa FIR and Jeddah FIR                                      | -                        | ATUDO M318 KATIT                                | -                                                 |
| Sanaa FIR and Jeddah FIR                                      | -                        | ATUDO M318 GOLGU M550 RIBOT                     | -                                                 |
| Doha FIR and Jeddah FIR and beyond overflying Riyadh VOR (KIA)| -                        | MEKRI P899 TOVOX                                | Conditions apply via Bahrain's standard routing    |
| Bahrain FIR Northbound and Westbound to Tehran FIR, Kuwait FIR and Baghdad FIR | - | DAXIB Q563 UKUVO G462 TUMAK                     | -                                                 |
| Jeddah FIR via COPPI and Bopan VOR (BPN) and destinations OERK and OEJN | - | BOSEV N563 ALPOB                                | -                                                 |
| OBBI, OBBS, OBKH, OEDF and OEDR                              | -                        | BOSEV N563 IMGUX P699 ORMID                     | -                                                 |
| OIBK                                                          | -                        | DAXIB Q563 UKUVO DCT KIVUS DCT LUDAM DCT ORSAR  |                                                   |
| OISS, OIII and beyond                                         | -                        | TULON M318 TOVIV P574 KUMUN                     | -                                                 |
| OMAL                                                          | 9,000ft or below        | KANIP                                           | Use appropriate KANIP SID                         |
| OMDB, OMDW and OMSJ                                           | 10,000ft or below        | LORID                                           | Use appropriate LORID SID; Subject to delays during high IFR activity |
| OMFJ                                                          | -                        | KANIP DCT VAMIM DCT PEDOG DCT MURGU Q308 RUDAT DCT IMVAT | -                                         |
| OMFJ                                                          | -                        | KANIP DCT VAMIM DCT PEDOG DCT MURGU Q308 RUDAT DCT FJV   | -                                         |
| OMRK                                                          | -                        | KANIP DCT VAMIM DCT PEDOG DCT MURGU Q308 ORKOB DCT FJV DCT LAGLI DCT RAV | -      |

  <figcaption>Table 2-5: Standard routes</figcaption>
</figure>

!!! note
      Any other flight plans departing OMAA into other airports within UAE airspace can expect **radar vectors** subject to ATC approval and possible delays.


## 3.5 Requested cruising level
### 3.5.1 Level restrictions
Aircraft routes out of the aerodrome must comply with all routing and level restrictions as described in *section 3.1 of Arabian MATS P1 under foundations* and *Table 2-5*. This is based on direction and type of flight.

Should an aircraft file an invalid cruise level, GMP shall advise the aircraft of this when delivering the clearance. In all cases, the next lowest valid cruise level shall be assigned, and the aircraft advised.

## 3.6 Delay mitigation
### 3.6.1 Target off-block time (TOBT)
When A-CDM procedures are active, pilots must report their confirmed TOBT on *vacdm.vatsim.me*, which is then displayed in the controller's client on the departure list. A fully green time indicates a confirmed TOBT.

The TOBT system allows aircraft to push back, taxi to the runway holding point, and depart on schedule without extended delays in the departure queue. If an aircraft reports ready for pushback before its assigned TOBT, it will be instructed to hold position and will be given its place in the pushback sequence, unless aerodrome conditions permit and a slot is available. If an aircraft is cleared for push and start but does not begin pushing within 2-5 minutes, the pushback clearance is canceled, and a new TOBT is assigned.

!!! note
     If a pilot has not confirmed their TOBT, the controller should request it on frequency and update the departure list accordingly.

## 3.7 Runway change procedure
AIR shall provide ample notice to GMP before changing runway configuration. The last departure using the old configuration shall be coordinated between AIR, GMP, GMC and approach/departure.

Aircraft that have already been cleared to depart using the old configuration shall be re-cleared if they have not already requested pushback.

## 3.8 VFR aircraft
VFR flight activity should be planned in accordance to published VFR charts, specifically the **"Abu Dhabi - CTA VFR** and **CTA VFR Route information** for navigating within the Abu Dhabi CTA and for flying out of the CTA into neighboring airspaces. 

GMP may use the appropriate charts as per the requirements of the pilot's intentions in accordance with 3.8.1, 3.8.2 and 3.8.3

!!! warning
    At any time, AIR control and/or Approach/Departure control may impose partial or full restrictions to VFR operations out of the aerodrome during periods of increased IFR activity or due to restrictions and limitations to aircraft type.

    It is imperative that GMP is in continuous coordination with AIR control and Abu Dhabi Approach control for departing VFR traffic.


### 3.8.1 VFR departures into uncontrolled airspace
VFR traffic shall be cleared via the most appropriate VFR route towards their destination. If necessary, the clearance may be amended by AIR prior to departure.

!!! example
      **Pilot**: Abu Dhabi Delivery, A6-AWW Abu Dhabi Aviation apron, request clearance to Dubai, information C

      **Controller**: A6-AWW, Abu Dhabi Delivery, cleared to exit Abu Dhabi control zone via Al Reef North (REN), AA1. Shahama East (SHE), not above Altitude 1000ft VFR, Squawk 0611.""

      **Pilot**: Cleared to exit Abu Dhabi control zone via Al Reef North (REN), AA1. Shahama East (SHE), not above Altitude 1000ft VFR, Squawk 0611, A6-AWW."

      **Controller**: AWW, readback correct, information C, report ready for startup.

      **Pilot**: Wilco.

!!! note
      All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

!!! warning
      As of March 2022 VFR route AA6 is suspended
      
### 3.8.2 VFR departures into controlled airspace
!!! note
      VFR aircraft intending to climb into Abu Dhabi CTA (above 1500 ft) shall only be cleared after prior coordination with Approach/Departure control. Otherwise, they shall be instructed to remain outside controlled airspace after leaving the control zone. 

      Unless an altitude higher than the Abu Dhabi CTR has been requested by the pilot, they shall be treated with procedures outlined in 3.8.1.

VFR traffic shall be cleared via the most appropriate VFR route towards their destination. If necessary, the clearance may be amended by AIR prior to departure.

!!! example
      **Pilot**: Abu Dhabi Delivery, A6-AWW Abu Dhabi Aviation apron, request clearance to Dubai, Altitude 7500ft, information C

      **Controller**: A6-AWW, Abu Dhabi Delivery, cleared to exit Abu Dhabi control zone via Al Reef North (REN), AA1. Shahama East (SHE), not above Altitude 1000ft VFR, Squawk 0611.""

      **Pilot**: Cleared to exit Abu Dhabi control zone via Al Reef North (REN), AA1. Shahama East (SHE), not above Altitude 1000ft VFR, Squawk 0611, A6-AWW."

      **Controller**: AWW, readback correct, information C, report ready for startup.

      **Pilot**: Wilco.

!!! note
      All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

### 3.8.3 VFR traffic remaining in circuit
!!! note
      VFR traffic wishing to remain in the circuit shall be cleared only after prior coordination with AIR.

**Left hand** circuits shall be carried out by VFR traffic departing runways **31L and 13L**

**Right hand** circuits shall be carried out by VFR traffic departing runways runway **31R and 13R**.

Circuits shall be conducted at an altitude of **1000ft**. This can be ammended up to 1500ft by AIR if required.

!!! note
      Runway **31L/13R** is preferred for departure and full stop landings as it sits closer to the GA apron (Abu Dhabi Aviation Apron) situated at the south of the aerodrome.

!!! note
      All VFR circuit traffic shall be assigned a discrete SSR code so that they may be identified on radar.

!!! note
      VFR circuits shall not be permitted at the aerodrome during times of increased IFR departure or arrival activity.

!!! example
      **Pilot**: Abu Dhabi delivery, A6-CTA type SR22T, Abu Dhabi Aviation Apron, Information Z, requesting clearance for circuits.

      **Controller:** A6-CTA, Abu Dhabi delivery, cleared left hand circuit, runway 31L, not above altitude 1000ft, VFR, squawk 6022.

      **Pilot:** Cleared left hand circuit, runway 31L, not above altitude 1000ft, VFR, squawk 6022, A6-CTA.

      **Controller:** ATA, readback correct. Information Z, report ready for startup."

      **Pilot:** Wilco.