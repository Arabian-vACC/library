# 2. Ground Movement Control ("Sharjah Ground")
## 2.1 General provisions
Ground Movement Control (GMC) is responsible for validating routes and shall provide IFR clearance 
to departing aircraft. The controller shall assign the correct departure procedure to the aircraft 
based on the first point that is filed on the flight plan.

Where the flight plan contains an invalid route, level, or departure procedure, GMC shall ensure that 
the error is corrected before the aircraft is given its clearance.

GMC is also responsible for managing aircraft movements on all aerodrome movement areas except 
for runways and their associated taxiways. Departing aircraft are given pushback instructions and 
instructions to taxi to the runway holding point. Arriving aircraft are assigned a stand and instructed 
to taxi as appropriate. 

## 2.2 Departure clearance
#### 2.2.1 General
GMC is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the 
following information on first contact:

- Callsign;
- Aircraft type;
- Parking stand;
- Destination
- Requested Flight level
- Departure D-ATIS letter and QNH;
  
#### 2.2.2 Information contained in a departure clearance
An IFR clearance shall be in the following format:

- Callsign;
- Destination;
- Departure procedure;
- Initially cleared altitude;
- Frequency handoff;
- Assigned SSR code

!!!example
      **Pilot:** Sharjah ground, ABY463, Airbus A321neo, information X, stand 4, requesting IFR clearance to Delhi, FL350.

      **Controller:** ABY463, Sharjah ground, cleared to Delhi via DAVMO 3R, maintain altitude 3000ft, when airborne contact Dubai departures on 124.675, squawk 1743.

     **Pilot:** Cleared to Delhi via DAVMO 3R, maintain altitude 3000ft, when airborne contact Dubai departures on 124.675, squawk 1743, ABY463.

     **Controller:** ABY463, readback correct. QNH 1013, report ready for pushback.

!!!note
      GMC must obtain a full readback of the clearance. If the pilot does not report the current ATIS letter on first contact, GMC shall pass the current ATIS letter and QNH.

#### 2.2.3 Aircraft requiring a reroute
If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged. 

An aircraft shall be issued a reroute by GMC if the pilot’s route doesn’t comply with the standard routes laid out in Table 2-2. 

## 2.3 Departure procedures
### 2.3.1 RNAV instrument departures
Sharjah primarily uses RNAV standard instrument departures (SIDs) and is the preferred departure 
type for IFR aircraft. Departing aircraft shall be assigned an appropriate RNAV departure according to 
the first fix in the flight plan and runways in use.

!!!info
      SIDs which have an identifier ending in **R** are valid for **30.** SIDs with an identifier ending in **Q** are valid for **12.** *(Table 2-1)*

| First Fix |   30    |   12    |
|:---------:|:-------:|:-------:|
|   ANVIX   |    5R   |    4Q   |
|   DAVMO   |    3R   |    4Q   |
|   EMERU   |    1R   |    2Q   |
|   IVURO   |    1R   |    1Q   |
|   KUTLI   |    3R   |    3Q   |
|   MIROT   |    2R   |    3Q   |
|   NABIX   |    2R   |    3Q   |
|   RIDAP   |    2R   |    3Q   |
|   SENPA   |    2R   |    3Q   |
<figure markdown>
  <figcaption>Table 2-1: RNAV SIDs</figcaption>
</figure>

### 2.3.2 Radar Departure Procedure
The radar departure procedure shall be used when aircraft are unable to accept an RNAV departure, such as one with outdated nav data. Whereas RNAV departures follow a prescribed track until leaving the Dubai Departures airspace, radar departures are given radar vectors to the first fix. 

In the take-off clearance, Air Control (AIR) shall assign a heading to fly after departure appropriate to the Dubai CTA exit point.

A radar departure clearance shall contain the following information:

- Callsign;
- Destination;
- Departure instructions;
- Initially cleared altitude;
- Frequency handoff;
- Assigned SSR code

!!! example
      **Controller:** SQC216, Sharjah Ground, cleared to Amsterdam, expect radar vectors, maintain altitude 2000ft, when airborne contact Dubai departures on 124.675, Squawk 3427.

!!! info
      All aircraft travelling westbound on departure from 30 shall be assigned an initial climb of **2000ft**. All other departures from 30 shall be assigned an initial climb of **3000ft**.

!!! note
      Aircraft on a radar departure shall have the text *VECTORS* inserted to the scratchpad section of their entry on the departure list.

!!! info
      All IFR departures shall be instructed to contact DEP 2 when airborne.

## 2.4 Rerouting aircraft
An aircraft shall be issued a reroute by GMP if the pilot’s route doesn’t comply with the standard routes laid out in Table 2-2. 

Several routing restrictions exist within UAE airspace and must be complied with when issuing a departure clearance.

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
    <td>Landing OMDW, OMDB, OMRK, and OMFJ</td>
    <td>Max 7,000 ft<br>(Omni-directional Departure)</td>
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

## 2.6 Runway change procedure

Runway change shall be coordinated between Dubai AIR and Sharjah AIR due to the runway dependencies as provided in 3.2.

## 2.7 VFR aircraft
VFR flight activity should be planned in accordance to published VFR charts, specifically the “**Dubai CTA VFR**” chart for VFR traffic navigating out of the Dubai CTR into neighbouring airspaces and within the Sharjah control zone. GMC may use the appropriate charts as per the requirements of the pilot’s intentions in accordance with 2.7.1, 2.7.2 and 2.7.3.

At any time, AIR control and Approach/Departure control may impose partial or full restrictions to VFR operations out of OMSB during periods of increased IFR activity or due to restrictions and limitations to aircraft type. It is imperative that GMC is in continuous coordination with AIR control and Approach/Departure control for departing VFR traffic.


### 2.7.1 VFR Departures into uncontrolled airspace
VFR traffic shall be cleared via the most appropriate VFR route towards their destination. If necessary, the clearance may be amended by AIR prior to departure. 

All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

!!! example
      **Pilot:** Sharjah ground, A6-CTK, SR22, request clearance to Al Maktoum, information C.

      **Controller:** A6-CTK, Sharjah ground, cleared to exit Sharjah control zone via Sharjah Univesity, Runway 30, Altitude 1000ft VFR, Squawk 0611.

      **Pilot:** Cleared to exit Sharjah control zone via Sharjah Univesity, Runway 30, Altitude 1000ft VFR, Squawk 0611, A6-CTK.

      **Controller:** A6-CTK, readback correct. QNH 1003, Report ready for start-up.

### 2.7.2 VFR Departures into controlled airspace
VFR aircraft requesting clearance to climb into approach airspace (above 1500 ft) shall only be cleared after prior coordination with approach/departure control. Otherwise, they shall be instructed to remain outside controlled airspace after leaving the control zone. 

All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

!!! example
      **Pilot:** Sharjah ground, A6-CTK, SR22, request eastbound departure on track Fujeirah, altitude 6500ft.

      **Controller:** A6-CTK, Sharjah ground, cleared eastbound departure, altitude 6500ft VFR, Runway 30, Squawk 0611.

      **Pilot:** Cleared eastbound departure, altitude 6500ft VFR, Runway 30, Squawk 0611, A6-CTK.

      **Controller:** A6-CTK, readback correct. QNH 1003, Report ready for start-up.

### 2.7.3 VFR traffic remaining in circuit
VFR traffic wishing to remain in the circuit shall be cleared only after prior coordination with AIR and Approach/Departure control.

As per possible restrictions mentioned in 2.8, VFR traffic may be encouraged to carry out circuits at neighbouring aerodromes such as OMDW, and OMRK during periods of increased IFR activity and due to restrictions to aircraft type. GMP must coordinate with AIR control and Arrivals/Departures control in such cases and relay the information to the pilot in accordance with 2.7.1 or 2.7.2.

VFR circuits shall not be permitted out of OMSB if any of the aforementioned restrictions from AIR and Approach/Departure control is in effect. 

All VFR circuit traffic shall be assigned a discrete SSR code so that they may be identified on radar.

All VFR aircraft shall be instructed to conduct circuits to the north of the aerodrome (right-hand circuits for 30 and left-hand circuits for 12R) at an altitude of 1000 ft. Aircraft may also be cleared to conduct circuits at 1500 ft, if required.

## 2.8 Departure pushback procedures
### 2.8.1 General pushback procedures
Assuming no obstructions, aircraft shall be instructed to pushback immediately.

Aircraft requesting pushback that are not squawking their assigned transponder code shall be instructed to hold position and squawk the correct code; movement of such aircraft is prohibited.

Pushback direction is based primarily on aircraft location and runway configuration.

On aprons F and A, all traffic shall be instructed to pushback on taxiway Z. 

Aircraft on stands 1A, 1B, 1C, stands 11 to 26 and stands 50 to 62 shall be instructed to pushback *"facing North".*

Aircraft on stands 2 to 7 shall be instructed to pushback *"facing East".*

Aircraft on stands 2 to 7 shall be instructed to pushback *"facing East".*

!!! example
      **Controller:** RJA613, Sharjah ground, pushback approved, facing east.

      **Pilot:** Pushback approved, facing east, RJA613.

!!! note
      Conditional pushback instructions may also be issued if an aircraft is taxiing behind another waiting for pushback.

!!! example
      **Controler:** RJA613, Sharjah ground, behind the AirArabia A320 passing right to left, pushback approved, facing east, behind.

      **Pilot:** Behind the AirArabia A320 passing right to left, pushback approved, facing east, behind, RJA613.

### 2.8.2 Pushback types
#### 2.8.2.1 Standard pushback
This type will normally have the aircraft stop abeam the adjacent stand. The phraseology for this type of pushback is identical to the pushback phraseology as provided in 2.8.1.

#### 2.8.2.2 Short pushback
A short pushback instruction shall require the aircraft to complete the pushback abeam the current stand such that the adjacent stand will not be blocked.

!!! example
    **Pilot**: "Sharjah Ground, ABY8KC, on stand 3 request pushback."

    **Controller**: "ABY8KC, Sharjah Ground, short pushback approved, face east on A to finish abeam stand 64."

    **Pilot**: "Short pushback approved, facing east on A to finish abeam stand 4, ABY8KC."

#### 2.8.2.3 Long pushback
A long pushback instruction shall require aircraft to complete the pushback operation two stands away from where the pushback was commenced. This manoeuvre may be used when aircraft are vacating a stand to be used by another aircraft that is taxiing in.

!!! example
    **Pilot**: "Sharjah Ground, ABY8KC, on stand 4 request pushback."

    **Controller**: "ABY8KC, Sharjah Ground, long pushback approved, face east on A to finish abeam stand 6."

    **Pilot**: "Long pushback approved, facing east on A to finish abeam stand 6, ABY8KC."

#### 2.8.3 Simultaneous pushback procedure
Simultaneous pushback operations shall be permitted so long as aircraft are separated by at least 2 stands upon completion of their pushback.

!!!warning
      Simultaneous pushback operations are not permitted into the same alleyway for stands 11 to 26 and on stands 1A, 1B and 1C.

## 2.9 Departure taxi procedures
### 2.9.1 General departure taxi procedures
Where aircraft are taxied to runway holding points, transfer of control to AIR should be made early enough such that the aircraft is not required to stop its taxi. 

To deconflict traffic and to reduce the length of taxi clearances, intermediate holding points shall be used wherever possible.

!!! example
      **Controller:** ABY436, Taxi via A, A20, holding point B20, Runway 30.

      **Pilot:** Taxi via A, A20, holding point B20, Runway 30, ABY436.

### 2.9.2 Runway 30 departure taxi procedures
When departing from 30, aircraft taxiing from passenger apron (stands 1A to 26) shall be instructed to taxi via A and A20 to holding point B20. 

Aircraft on the cargo apron (stands 50 to 62) shall be instructed to taxi via Z8, A8 and B to holding point B20.

!!! warning
      Eastbound traffic flow on B must be avoided between B2 and B7, as this blocks the exit taxiways from runway 30.

*(See 4.1)*
### 2.9.3 Runway 12 departure taxi procedures
When departing from 12, aircraft taxiing from passenger apron (stands 1A to 26) shall be instructed to taxi via A and A2 to holding point B2.

Aircraft on the cargo apron (stands 50 to 62) shall be instructed to taxi via Z8, A8 and B to holding point B2. 

!!! warning
      Westbound traffic flow on B must be avoided between B14 and B11, as this blocks the exit taxiways from runway 12.

*(See 4.4)*

## 2.10 Arrival taxi procedures
### 2.10.1 General arrival taxi procedures
GMC shall assign an arrival stand to aircraft when they are on final approach.

Once the aircraft is handed off to GMC, they shall be taxied to their stand in accordance with the procedures laid down in 2.10.4. 

*(See 4.2)*

### 2.10.2 Runway 30 arrival taxi procedures
Aircraft shall vacate 30 onto B7 or B6 and are then handed off to GMC.

Aircraft shall be taxied via A6 and A to the appropriate stand. 

*(See 4.2)*

### 2.10.3 Runway 12 arrival taxi procedures
Aircraft shall vacate 30 onto B11 or B14 and are then handed off to GMC.

Aircraft shall be taxied via A14 and A to the appropriate stand.

!!! warning
      Aircraft shall not be instructed to make a right turn on A12 after vacating B11. They shall always make a left turn onto B.

*(See 4.3)*

### 2.10.4 Stand allocation procedure
|             Area             |                 Operator               |
|:----------------------------:|:--------------------------------------:|
|         1A, 1B and 1C        |             ABY                        |
|             2 to 8           |     ABY, all international             |
|            11 to 26          |     ABY, low-cost (overflow)           |
|  51, 53, 55, 57, 59, 61      |     ABY, SQC, GEC, UPS                 | 
|  50, 52, 54, 56, 58, 60, 62  |  ABY, other cargo, low-cost (overflow) |  

  <figcaption>Table 2-3: Stand allocation procedure</figcaption>
</figure>

### 2.10.5 Stand restrictions
Stands 1A, 1B, 1C, and stands 11 to 26 are medium (code C) capable only. 

Stands 2 to 8 are heavy (code E) capable only. 

Stands 50 to 62 are A380 (code F) capable. 
## 2.11 Low visibility operations (LVO)
### 2.11.1 LVO taxi routes
When LVO is in force shall only be issued taxi instructions in accordance with the designated LVO taxi routes.

Only CAT II/III holding points may be used during LVO (3.3.1).
## 2.12 Designated areas of responsibility
### 2.12.1 GMC positions
GMC is responsible for all aprons and associated taxiways.

*(See 6.1)*

### 2.12.2 Handoff procedure
Where transfer of control is to be made between controllers, aircraft shall not be cleared to a point beyond the current controller’s designated zone of responsibility unless there has been prior coordination with the next controller. Intermediate holding points may be used to satisfy this requirement. 