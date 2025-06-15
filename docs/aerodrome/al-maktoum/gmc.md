# 2. Ground Movement Control ("Al Maktoum Ground")
## 2.1 General provisions
Ground Movement Control (GMC) is responsible for validating routes and shall provide IFR clearance to departing aircraft. The controller shall assign the correct departure procedure to the aircraft based on the first point that is filed on the flight plan.

Where the flight plan contains an invalid route, level, or departure procedure, GMC shall ensure that the error is corrected before the aircraft is given its clearance.

GMC is also responsible for managing aircraft movements on all aerodrome movement areas except for runways and their associated taxiways. Departing aircraft are given pushback instructions and instructions to taxi to the runway holding point. Arriving aircraft are assigned a stand and instructed to taxi as appropriate.

## 2.2 Departure clearance
### 2.2.1 General
The GMC is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the following information on first contact:

- Aircraft Callsign;
- Aircraft type;
- Parking Stand;
- Destination;
- Dubai CTA exit point;
- Speed if unable to comply with minimum speed on the SID;
- ATIS letter & QNH

### 2.2.2 Information contained in a departure clearance
An IFR clearance shall be in the following format:

- Callsign;
- Destination;
- Departure procedure;
- Initially cleared altitude;
- Assigned SSR code

GMC shall obtain a full readback of the clearance. If the pilot does not report the current ATIS letter on first contact, GMC shall pass the current ATIS letter and QNH.

Departing aircraft shall be instructed to report ready for pushback.

!!! example
    **Pilot**: "Al Maktoum Ground, good evening, UAE9782, Boeing 777-200LR, stand S298, requesting IFR clearance to Hong Kong, exiting the Dubai control zone at ANVIX"
    
    **Controller**: "UAE9782, cleared to Hong Kong via the ANVIX4L departure, maintain altitude 3000ft, squawk 0542."
    
    **Pilot**: "Cleared to Hong Kong, ANVIX4L departure, maintain altitude 3000ft, squawk 0542, UAE9782."

    **Controller**: "UAE9782, readback correct, information Foxtrot, QNH 1009, report ready for pushback."



### 2.2.3 Datalink clearance (DCL)
Aircraft clearance may also be delivered by DCL. This type of clearance reduces controller workload and frequency congestion. For suitably equipped aircraft, this will be through the ACARS system on board the aircraft.

### 2.2.4 Aircraft requiring a reroute
If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged.

An aircraft shall be issued a reroute by GMC if the pilot’s route doesn’t comply with the standard routes laid out in Table 2-2.

### 2.2.5 Voice clearance
Aircraft requesting clearance via voice shall be given a voice clearance as per the format in 2.2.2.

## 2.3 Departure Procedures
### 2.3.1 RNAV Standard instrument departures
Al Maktoum primarily uses RNAV standard instrument departures (SIDs) and is the preferred departure type for IFR aircraft. Departing aircraft shall be assigned an appropriate RNAV departure according to the first fix in the flight plan and runway(s) in use.

| First Fix |    30   |    12   |    31   |    13   |
|:---------:|:-------:|:-------:|:-------:|:-------:|
|   ANVIX   |    4L   |    6J   |    1P   |    2N   |
|   DAVMO   |    4L   |    5J   |         |         |
|   EMERU   |    1L   |    3J   |         |         |  
|   KUTLI   |    3L   |    4J   |         |         |
|   MIROT   |    3L   |    4J   |    1P   |    1N   |
|   NABIX   |    3L   |    4J   |    1P   |    1N   |
|   NOLSU   |    3L   |    3J   |         |         |
|   RIDAP   |    3L   |    4J   |         |         |
|   SENPA   |    3L   |    4J   |         |         |

<figure markdown>
  <figcaption>Table 2-1: RNAV SIDs</figcaption>
</figure>

!!! info
      All aircraft shall be assigned an initial climb of **3000ft**. 


### 2.3.2 Radar departures
The radar departure procedure shall be used when aircraft are unable to accept an RNAV departure, such as one with outdated nav data. Whereas RNAV departures follow a prescribed track until leaving the Dubai Departures airspace, radar departures are given radar vectors to the first fix.

In the take-off clearance, Air Control (AIR) shall assign a heading to fly after departure appropriate to the Dubai CTA exit point.

A radar departure clearance shall contain the following information:

- Callsign;
- Destination;
- Departure instructions;
- Initially cleared altitude;
- Frequency handoff;
- Assigned SSR code


!!! note
      Aircraft on a radar departure shall have the text *VECTORS* inserted to the scratchpad section of their entry on the departure list.


## 2.4 Rerouting aircraft


An aircraft shall be issued a reroute by GMP if the pilot’s route doesn’t comply with the standard routes laid out in Table 2-2. 

Several routing restrictions exist within UAE airspace and must be complied with when issuing a departure clearance.

!!! example
    **Controller**: "UAE9824, cleared to Amman, via SENPA3L, SENPA N571 ALPOB L768 ULADA, flight planned route. Maintain 3000ft, squawk 0553."

!!! note
    The Arabian vACC Operations Department maintains an up-to-date route database on SimBrief. These routes can be accessed by selecting the ***"User Submitted Routes"*** option, highlighted in purple, when planning a flight.

<table><thead>
  <tr>
    <th>Destination</th>
    <th>Level Restrictions</th>
    <th>Routing</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Tehran FIR Northbound (including OIKB)</td>
    <td>-</td>
    <td>DAVMO M318 GABKO</td>
  </tr>
  <tr>
    <td>Landing OOMS, transiting Muscat FIR Eastbound and Southeast bound</td>
    <td>-</td>
    <td>ANVIX L223 TARDI</td>
  </tr>
  <tr>
    <td rowspan="5">Transiting Sanaa FIR and Jeddah FIR</td>
    <td rowspan="5">-</td>
    <td>SENPA N571 ALPOB</td>
  </tr>
  <tr>
    <td>ANVIX R401 GIDIS G783 TANSU</td>
  </tr>
  <tr>
    <td>ANVIX R401 GIDIS G783 RIGIL M628 PEKEM</td>
  </tr>
  <tr>
    <td>KUTLI L519 ATUDO M318 KATIT</td>
  </tr>
  <tr>
    <td>KUTLI L519 ATUDO M318 GOLGU</td>
  </tr>
  <tr>
    <td>Transiting Bahrain FIR onwards landing/transiting Kuwait, Baghdad, and Tehran FIRs</td>
    <td>-</td>
    <td>RIDAP M557 TUMAK</td>
  </tr>
  <tr>
    <td>Transiting Bahrain FIR onwards landing/transiting Jeddah FIR (including OERK, OEJN)</td>
    <td>-</td>
    <td>SENPA N571 ALPOB</td>
  </tr>
  <tr>
    <td>Landing within Bahrain FIR (including OBBI, OEDF, OEDR)</td>
    <td>Max FL260</td>
    <td>NABIX P699 ORMID</td>
  </tr>
  <tr>
    <td rowspan="2">Landing within Doha TMA (OTHH, OTBD)</td>
    <td rowspan="2">Max FL260</td>
    <td>NABIX P699 OXARI M430 TOSNA</td>
  </tr>
  <tr>
    <td>MIROT Q576 RORON M430 TOSNA</td>
  </tr>
  <tr>
    <td>Landing OIII &amp; OISS</td>
    <td>-</td>
    <td>DCT KUMUN</td>
  </tr>
  <tr>
    <td>Landing OIBK</td>
    <td>-</td>
    <td>RIDAP M557 TOTKU DCT KIVUS DCT LUDAM DCT ORSAR</td>
  </tr>
  <tr>
    <td>Landing OOSH</td>
    <td>At 11,000ft only</td>
    <td>ANVIX L223 TARDI</td>
  </tr>
  <tr>
    <td>Landing OOSA, transiting Muscat FIR Southbound and Southwest bound</td>
    <td>-</td>
    <td>ANVIX R401 GIDIS G783 UKRAG L710 MEMTU</td>
  </tr>
  <tr>
    <td rowspan="2">Transiting Muscat FIR Eastbound onwards landing/transiting Karachi and Mumbai FIRs</td>
    <td rowspan="2">-</td>
    <td>IVURO M677 LALDO</td>
  </tr>
  <tr>
    <td>IVURO M428 GOMTA</td>
  </tr>
  <tr>
    <td>Landing OMAA &amp; OMAD</td>
    <td>Max 10,000 ft</td>
    <td>DCT EMERU</td>
  </tr>
  <tr>
    <td>Landing OMAL</td>
    <td>-</td>
    <td>DCT ANVIX R401 GIDIS G783 VAVIM</td>
  </tr>
  <tr>
    <td>Landing OMSJ, OMDB, OMRK, and OMFJ</td>
    <td>Max 7,000 ft<br>(Radar Departure)</td>
    <td>DCT (RADAR VECTORS)</td>
  </tr>
</tbody></table>
<figure markdown>
  <figcaption>Table 2-2: Standard routes</figcaption>
</figure>

!!!info 
      Should an aircraft file an invalid cruise level, GMC shall advise the aircraft of this when delivering the clearance. In **all** cases, the next lowest valid cruise level should be assigned and the aircraft advised.

!!!note
      Offering two valid levels (one above and below their requested level) is discouraged; a lower level than what is requested can be complied with certainty factoring the aircraft's maximum capable cruise level as per their gross weight. On the other hand, higher levels may be rejected due to aircraft performance or maximum cruise altitude capabilities.

      Thus, resorting to issuing the next lowest valid cruise level minimises radio transmissions and simplifies the correction process between the controller and the aircraft.


## 2.5 Runway change procedure
Runway change shall be coordinated with Al Maktoum AIR

## 2.6 VFR aircraft
VFR flight activity should be planned in accordance to published VFR charts, specifically the “**Dubai CTA VFR**” chart for VFR traffic navigating out of the Al Maktoum CTR into neighbouring airspaces and within the Al Maktoum control zone. GMC may use the appropriate charts as per the requirements of the pilot’s intentions in accordance with 2.6.1, 2.6.2 and 2.6.3.

At any time, AIR control and Approach/Departure control may impose partial or full restrictions to VFR operations out of OMDW during periods of increased IFR activity or due to restrictions and limitations to aircraft type. It is imperative that GMC is in continuous coordination with AIR control and Approach/Departure control for departing VFR traffic.

### 2.6.1 VFR departures into uncontrolled airspace
VFR traffic shall be cleared via the most appropriate VFR route towards their destination. If necessary, the clearance may be amended by AIR prior to departure.

All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

### 2.6.2 VFR departures into controlled airspace
VFR aircraft requesting clearance to climb into approach airspace (above 1500 ft) shall only be cleared after prior coordination with approach/departure control. Otherwise, they shall be instructed to remain outside controlled airspace after leaving the control zone.

All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

!!! example
      **Pilot:** Al Maktoum Ground, A6-CTK, SR22, request eastbound departure on track Fujeirah, altitude 6500ft.

      **Controller:** A6-CTK, Al Maktoum Ground, cleared eastbound departure, altitude 6500ft VFR, Runway 30, Squawk 0611.

      **Pilot:** Cleared eastbound departure, altitude 6500ft VFR, Runway 30, Squawk 0611, A6-CTK.

      **Controller:** A6-CTK, readback correct, information A, QNH 1003, Report ready for start-up.

### 2.6.3 VFR traffic remaining in circuit
VFR traffic wishing to remain in the circuit shall be cleared only after prior coordination with AIR and Approach/Departure control.
All VFR circuit traffic shall be assigned a discrete SSR code so that they may be identified on radar.

All VFR aircraft shall be instructed to conduct circuits to the north of the aerodrome (right-hand circuits for 30 and left-hand circuits for 12) at an altitude of 1000 ft. EFTA aircraft shall be instructed to conduct circuits to the south of the aerodrome (left-hand circuits for 31 and right-hand circuits for 13) at an altitude of 1000 ft, **only** during the academy operational hours. Aircraft may also be cleared to conduct circuits at 1500 ft, if required.

## 2.7 Departure pushback procedures
### 2.7.1 General pushback procedures
Assuming no obstructions, aircraft shall be instructed to pushback immediately.

Aircraft requesting pushback that are not squawking their assigned transponder code shall be instructed to hold position and squawk the correct code; movement of such aircraft is prohibited.

Pushback direction is based primarily on aircraft location and runway configuration.


<table><thead>
  <tr>
    <th>Apron</th>
    <th>Stand(s)</th>
    <th>Taxiway</th>
    <th>Direction</th>
  </tr></thead>
<tbody>
  <tr>
    <td rowspan="1">S2</td>
    <td>S289-S300</td>
    <td>Z5</td>
    <td>Facing north</td>
  </tr>
  <tr>
    <td rowspan="3">S3</td>
    <td>S301-S313</td>
    <td>Z6</td>
    <td>Facing north</td>
  </tr>
  <tr>
    <td>S340-S348</td>
    <td>Z</td>
    <td>Facing east or west</td>
  </tr>
  <tr>
    <td>S324-S332</td>
    <td>Z7</td>
    <td>Facing north</td>
  </tr>
  <tr>
    <td rowspan="3">S4</td>
    <td>S401-S410</td>
    <td>Z8</td>
    <td>Facing north</td>
  </tr>
  <tr>
    <td>S440-S448</td>
    <td>Z</td>
    <td>Facing east or west</td>
  </tr>
  <tr>
    <td>S420-S425</td>
    <td>Z9</td>
    <td>Facing north</td>
  </tr>
  <tr>
    <td rowspan="13">G</td>
    <td>G1-G4</td>
    <td>Z17</td>
    <td>Facing north</td>
  </tr>
  <tr>
    <td>G5-G8</td>
    <td>Z17</td>
    <td>Facing south</td>
  </tr>
  <tr>
    <td>G9 and G10</td>
    <td>Z17</td>
    <td>Facing north</td>
  </tr>
  <tr>
    <td>G11 and G12</td>
    <td>Z17</td>
    <td>Facing south</td>
  </tr>
    <tr>
    <td>G13 and G14</td>
    <td>Z16</td>
    <td>Facing north</td>
  </tr>
  <tr>
    <td>G15 and G16</td>
    <td>Z16</td>
    <td>Facing south</td>
  </tr>
  <tr>
    <td>G17A-G17E</td>
    <td>Z15</td>
    <td>Facing west</td>
  </tr>
  <tr>
    <td>G18A and G18B</td>
    <td>Z16</td>
    <td>Facing north</td>
  </tr>
  <tr>
    <td>G18C and G18D</td>
    <td>Z16</td>
    <td>Facing south</td>
  </tr>
  <tr>
    <td>G19A-G19D</td>
    <td>Z12</td>
    <td>Facing south</td>
  </tr>
  <tr>
    <td>G20 and G20A</td>
    <td>Z20</td>
    <td>Facing west</td>
  </tr>
  <tr>
    <td>G21A-G22E</td>
    <td>Z14</td>
    <td>Facing west</td>
  </tr>
  <tr>
    <td>G100-G108</td>
    <td>Z11</td>
    <td>Facing north</td>
  </tr>
 
</tbody></table>


!!! example
      **Controller:** UAE9212, Al Maktoum Ground, pushback approved, facing north.

      **Pilot:** Pushback approved, facing north, UAE9212.

!!! note
      Conditional pushback instructions may also be issued if an aircraft is taxiing behind another waiting for pushback.

!!! example
      **Controler:** CLX215, Al Maktoum Ground, behind the Execujet Global 7500, passing right to left, pushback approved, facing east, behind.

      **Pilot:** Behind the Execujet Global 7500, passing right to left, pushback approved, facing east, behind, CLX215.

### 2.7.2 Pushback types
#### 2.7.2.1 Standard pushback
This type will normally have the aircraft stop abeam the adjacent stand. The phraseology for this type of pushback is identical to the pushback phraseology as provided in 2.7.1.

#### 2.7.2.2 Short pushback
A short pushback instruction shall require the aircraft to complete the pushback abeam the current stand such that the adjacent stand will not be blocked.

!!! example
    **Pilot**: "Al Maktoum Ground, EJO155, on stand G22B request pushback."

    **Controller**: "EJO155, Al Maktoum Ground, short pushback approved, face west on Z14 to finish abeam stand G22B."

    **Pilot**: "Short pushback approved, facing west on Z14 to finish abeam stand G22B, EJO155."

#### 2.8.2.3 Long pushback
A long pushback instruction shall require aircraft to complete the pushback operation two stands away from where the pushback was commenced. This manoeuvre may be used when aircraft are vacating a stand to be used by another aircraft that is taxiing in.
!!! example
    **Pilot**: "Al Maktoum Ground, UAE9154, on stand S295 request pushback."

    **Controller**: "UAE9154, Al Maktoum Ground, long pushback approved, face north on Z5 to finish abeam stand S297."

    **Pilot**: "Long pushback approved, facing north on Z5 to finish abeam stand S297, UAE9154."
#### 2.8.3 Simultaneous pushback procedure
Simultaneous pushback operations shall be permitted so long as aircraft are separated by at least 2 stands upon completion of their pushback.

!!!warning
      Simultaneous pushback operations are not permitted into the same alleyway for stands 11 to 26 and on stands 1A, 1B and 1C.

## 2.9 Departure taxi procedures
### 2.9.1 General departure taxi procedures
Where aircraft are taxied to runway holding points, transfer of control to AIR should be made early enough such that the aircraft is not required to stop its taxi. 

To deconflict traffic and to reduce the length of taxi clearances, intermediate holding points shall be used wherever possible.

!!! example
      **Pilot:** Al Maktoum Ground, UAE9876, request taxi.

      **Controller:** UAE9876, Al Maktoum Ground, Taxi via Z7, Z, hold ZM.

      **Pilot:** Taxi via Z7, Z, hold ZM, UAE9876.

### 2.9.2 Runway 30 departure taxi procedures
When departing from 30:

<table style="margin: auto; align-content: center;">
  <thead>
    <tr>
      <th>Stands</th>
      <th>Taxi Route (part1)</th>
      <th>Taxi Route (part2)</th>
      <th>Holding Point</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>S289-S313</td>
      <td>Z5/Z6, hold ZA/ZB</td>
      <td rowspan=8>Z, W16</td>
      <td rowspan=9>V16</td>
    </tr>
    <tr>
      <td>S340-S348</td>
      <td rowspan=2> direct to </td>
    </tr>
    <tr>
      <td>S440-S448</td>
    </tr>
    <tr>
      <td>S324-S332</td>
      <td>Z7, hold ZE</td>
    </tr>
    <tr>
      <td>S401-S410</td>
      <td>Z8, hold ZF</td>
    </tr>
    <tr>
      <td>S420-S425</td>
      <td>Z9, hold Z9C</td>
    </tr>
    <tr>
      <td>G100-G108</td>
      <td>Z11, hold Z11A</td>
    </tr>
    <tr>
        <td>S801-S812</td>
        <td>Z, hold ZP</td>
    </tr>
    <tr>
        <td>All other G stands</td>
        <td>To Z12, hold Z12A</td>
        <td>W16</td>
    </tr>
    <tr>
      <td>S289-S313</td>
      <td>Z5/Z6, hold ZA/ZB</td>
      <td rowspan=8>Z, W15</td>
      <td rowspan=9>V13</td>
    </tr>
    <tr>
      <td>S340-S348</td>
      <td rowspan=2> direct to </td>
    </tr>
    <tr>
      <td>S440-S448</td>
    </tr>
    <tr>
      <td>S324-S332</td>
      <td>Z7, hold ZE</td>
    </tr>
    <tr>
      <td>S401-S410</td>
      <td>Z8, hold ZF</td>
    </tr>
    <tr>
      <td>S420-S425</td>
      <td>Z9, hold Z9C</td>
    </tr>
    <tr>
      <td>G100-G108</td>
      <td>Z11, hold Z11A</td>
    </tr>
    <tr>
        <td>S801-S812</td>
        <td>Z, hold ZP</td>
    </tr>
    <tr>
        <td>All other G stands</td>
        <td>To Z12, hold Z12A</td>
        <td>W15</td>
    </tr>
  </tbody>
</table>

!!! note
      Aircraft requesting a departure from V13 shall be instructed to taxi via Z and W15 to holding point V13.

!!! warning
      Eastbound traffic flow on V must be avoided, as this blocks the exit taxiways from runway 30.

*(See 4.1)*
### 2.9.3 Runway 12 departure taxi procedures
When departing from 12:
<table style="margin: auto; align-content: center;">
  <thead>
    <tr>
      <th>Stands</th>
      <th>Taxi Route (part1)</th>
      <th>Taxi Route (part2)</th>
      <th>Holding Point</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>S289-S300</td>
      <td>Z5</td>
      <td>Z5, hold ZA</td>
      <td rowspan=9>V4 or V1</td>
    </tr>
    <tr>
      <td>S301-S313</td>
      <td>Z6, hold ZB</td>
      <td rowspan=7>Z, W7, W</td>
    </tr>
    <tr>
      <td>S340-S348</td>
      <td rowspan=2>direct via</td>
    </tr>
    <tr>
      <td>S440-S448</td>
    </tr>
    <tr>
      <td>S324-S332</td>
      <td>Z7, hold ZE</td>
    </tr>
    <tr>
      <td>S401-S410</td>
      <td>Z8, hold ZF</td>
    </tr>
    <tr>
      <td>S420-S425</td>
      <td>Z9, hold Z9C</td>
    </tr>
    <tr>
      <td>G100-G108</td>
      <td>Z11, hold Z11A</td>
    </tr>
    <tr>
      <td>All other G stands</td>
      <td>To Z12, hold W16A</td>
      <td>W</td>
    </tr>
  </tbody>
</table>

!!! warning
      Westbound traffic flow on V must be avoided, as this blocks the exit taxiways from runway 12.

*(See 4.3)*

## 2.10 Arrival taxi procedures
### 2.10.1 General arrival taxi procedures
GMC shall assign an arrival stand to aircraft when they are on final approach.

Once the aircraft is handed off to GMC, they shall be taxied to their stand in accordance with the procedures laid down in 2.10.4. 


### 2.10.2 Runway 30 arrival taxi procedures
Aircraft shall vacate 30 onto V10, V12 or V6 and are then handed off to GMC.

Aircraft shall be taxied in accordance with 4.2

*(See 4.2)*

### 2.10.3 Runway 12 arrival taxi procedures
Aircraft shall vacate 12 onto V7, V9 or V13 and are then handed off to GMC.

Aircraft shall be taxied in accordance with 4.2

*(See 4.4)*

### 2.10.4 Stand allocation procedure
|             Area             |                 Operator               |
|:----------------------------:|:--------------------------------------:|
|         S289-S313            |             EK Sky Cargo               |
|         S324-S410            |     Other Cargo                        |
|         S340-S348L           |     Small Private Jets                 |
|        S440R-S446L           |     International Carriers             | 
|       S420R-S420L            |         Leased Carriers                |  
|        S420R-S425L           |     Private Companies                  | 
|        G100-G108             |         Falcon                         | 
|        G17 and G20           |        Private Jet Hangars             | 
|        G1-G8                 |               VIP Terminal             | 
|        S801-S812             |               Dubai Airshow            | 
  <figcaption>Table 2-3: Stand allocation procedure</figcaption>
</figure>

### 2.10.5 Stand restrictions
**ONLY** stands S291-S294, S306, S310, S325, S329, G100-G108 and S801-S806 are A380 (code F) capable.

## 2.11 Low visibility operations (LVO)
### 2.11.1 LVO taxi routes
When LVO is in force shall only be issued taxi instructions in accordance with the designated LVO taxi routes.

Only CAT II/III holding points may be used during LVO (3.3.1).
## 2.12 Designated areas of responsibility
### 2.12.1 GMC positions
GMC is responsible for all aprons and associated taxiways.

*(See 5.1)*

### 2.12.2 Handoff procedure
Where transfer of control is to be made between controllers, aircraft shall not be cleared to a point beyond the current controller’s designated zone of responsibility unless there has been prior coordination with the next controller. Intermediate holding points may be used to satisfy this requirement. 
