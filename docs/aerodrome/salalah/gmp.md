# 3. Departure Clearance Procedures
## 3.1 General Provisions
Ground Movement Control (GMC) is responsible for validating routes and shall provide IFR clearance to departing aircraft. The controller shall assign the correct departure procedure to the aircraft based on the first point that is filed on the flight plan.

Where the flight plan contains an invalid route, level, or departure procedure, GMC shall ensure that the error is corrected before the aircraft is given its clearance.

## 3.2 Departure Clearance
#### 3.2.1 General
GMC is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the following information on first contact:

- Callsign;
- Aircraft type;
- Parking stand;
- Destination
- ATIS letter and QNH;
  
#### 3.2.2 Information Contained in a Departure Clearance
An IFR clearance shall be in the following format:

- Callsign;
- Destination;
- Departure procedure;
- Initially cleared altitude;
- Assigned SSR code

!!! example
    **Pilot**: "Salalah Ground, QTR1131, Airbus A320, information B, stand 12, clearance to Doha-Hamad."

    **Controller**: "QTR1131, Salalah Ground, information B correct, cleared to Doha-Hamad via the DAXAM1S departure, initial climb 10,000 ft, squawk 4701."

    **Pilot**: "Cleared to Doha-Hamad via the DAXAM1S departure, initial climb 10,000 ft, squawk 4701, QTR1131."

    **Controller**: "QTR1131, readback correct, QNH 1004, report ready for pushback."

!!! note
    GMC must obtain a full readback of the clearance. If the pilot does not report the current ATIS letter on first contact, GMC shall pass the current ATIS letter and QNH.

#### 3.2.3 Aircraft Requiring a Reroute
If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged. 

An aircraft shall be issued a reroute by GMC if the pilot’s route doesn’t comply with the standard routes laid out in Table 3-2. 

## 3.3 Departure Procedures
### 3.3.1 RNAV Instrument Departures
Salalah primarily uses RNAV standard instrument departures (SIDs) and is the preferred departure type for IFR aircraft. Departing aircraft shall be assigned an appropriate RNAV departure according to the first fix in the flight plan and runways in use. 

!!! info
    RNAV SIDs which have an identifier ending in **Q** are valid for **07.** RNAV SIDs with an identifier ending in **S** are valid for **25.** *(Table 3-1)*

| First Fix |       07      |   Initial Climb   |     25    |   Initial Climb   |
|:---------:|:-------------:|:-----------------:|:---------:|:-----------------:|
|   DAXAM   |    1Q/**1U**  |      10,000 ft    |     1S    |      10,000 ft    |
|   LADAR   |       1Q      |      10,000 ft    |     1S    |      10,000 ft    |
|   MUTVA   |       1Q      |      10,000 ft    |     1S    |      10,000 ft    |
|   SILTA   |       1Q      |      10,000 ft    |     1S    |      10,000 ft    |
<figure markdown>
  <figcaption>Table 3-1: RNAV SIDs</figcaption>
</figure>

!!! warning
    The DAXAM1S and LADAR1Q departures require radar surveillance and must not be assigned if radar coverage is unavailable. Assignment of the MUTVA1Q departure depends on the activation status of the OO(D)-65 danger area. The DAXAM departure offers two routing options: DAXAM1Q and DAXAM1U, DAMXAM1U routes aircraft over the sea to avoid terrain. Aircraft unable to meet the required climb gradients must inform ATC during the clearance request to avoid being assigned a straight-out departure over the terrain.

### 3.3.2 Conventional Instrument Departures
Aircraft unable to comply with RNAV Standard Instrument Departures (SIDs) shall be assigned a conventional (non-RNAV) Instrument Departure procedure as an alternative.

!!! info
    Conventional SIDs which have an identifier ending in **P** are valid for **07.** Conventional SIDs with an identifier ending in **R** are valid for **25.** *(Table 3-2)*

| First Fix |       07      |   Initial Climb   |     25    |   Initial Climb   |
|:---------:|:-------------:|:-----------------:|:---------:|:-----------------:|
|   DAXAM   |    1P/**1T**  |      10,000 ft    | 1R/**1V** |      10,000 ft    |
|   LADAR   |       1P      |      10,000 ft    |     1R    |      10,000 ft    |
|   MUTVA   |       1P      |      10,000 ft    |     1R    |      10,000 ft    |
|   SILTA   |       1P      |      10,000 ft    |     1R    |      10,000 ft    |
<figure markdown>
  <figcaption>Table 3-2: Conventional SIDs</figcaption>
</figure>

!!! warning
    Assignment of the MUTVA1P departure depends on the activation status of the OO(D)-65 danger area. The DAXAM departure offers two routing options: DAXAM1P/DAXAM1T and DAXAM1R/DAXAM1V, DAMXAM1T and DAXAM1V routes aircraft over the sea to avoid terrain. Aircraft unable to meet the required climb gradients must inform ATC during the clearance request to avoid being assigned a straight-out departure over the terrain.

## 3.4 Rerouting Aircraft
An aircraft shall be issued a reroute by GMC if the pilot’s route doesn’t comply with the standard routes laid out in Table 3-3. 

Several routing restrictions exist within the Muscat airspace and must be complied with when issuing a departure clearance.

!!! note
    The Arabian vACC Operations Department maintains an up-to-date route database on SimBrief. These routes can be accessed by selecting the ***"User Submitted Routes"*** option, highlighted in purple, when planning a flight.

| Destination                       | Level Restrictions | Routing                                           |
|-----------------------------------|--------------------|---------------------------------------------------|
| OOMS & OOMM                       |          -         | DAXAM Y414 MCT                                    |
| OOSH                              |          -         | DAXAM Y414 DEDSO R401 VELIK Y515 EMISO Q730 LADBI |
| Landing Northern U.A.E Airports   |          -         | DAXAM Y414 DEDSO R401 MUSAP                       |
| Landing Southern U.A.E Airports   |          -         | DAXAM Y414 DEDSO R401 DOLFI P558 SODEX            |
| Exiting the Muscat FIR Northbound |          -         | DAXAM Y414 DEDSO R401 HAI then as filled          |
<figure markdown>
  <figcaption>Table 3-3: Standard routes</figcaption>
</figure>

!!! info 
    Should an aircraft file an invalid cruise level, GMC shall advise the aircraft of this when delivering the clearance. In **all** cases, the next lowest valid cruise level should be assigned and the aircraft advised.

    Offering two valid levels (one above and below their requested level) is discouraged; a lower level than what is requested can be complied with certainty factoring the aircraft's maximum capable cruise level as per their gross weight. On the other hand, higher levels may be rejected due to aircraft performance or maximum cruise altitude capabilities.

    Thus, resorting to issuing the next lowest valid cruise level minimises radio transmissions and simplifies the correction process between the controller and the aircraft.

## 3.6 Runway Change Procedure

AIR shall provide ample notice to GMC before changing runway configuration. The last departure using the old configuration shall be coordinated between AIR, GMC, and RDR. 

Aircraft that have already been cleared to depart using the old configuration shall be re-cleared if they have not already requested pushback.

## 3.7 VFR Aircraft
VFR flight activity should be planned in accordance to published VFR charts, specifically the “**Salalah Visual Approach**” chart for VFR traffic navigating out of the Salalah ATZ into neighbouring airspaces. GMC may use the appropriate charts as per the requirements of the pilot’s intentions in accordance with 3.7.1 and 3.7.2.

### 3.7.1 VFR Departures into Controlled Airspace
VFR traffic shall be cleared via the most appropriate VFR route towards their destination. As Salalah Radar operates within the Salalah ATZ (Class D) and its own CTR (Class C), coordination with Salalah Radar is required when online for all VFR departures.

All VFR departures shall initially be assigned a squawk code of 7000. Salalah Radar may issue a discrete squawk code for identification purposes if necessary.

!!! example
      **Pilot:** Salalah Ground, A4O-OAD, Diamond DA40, request eastbound departure on track Mukhaizna, altitude 7,500 ft.

      **Controller:** A4O-OAD, Salalah Ground, cleared eastbound departure, altitude 7,500 ft VFR, Runway 07, squawk 7000.

      **Pilot:** Cleared eastbound departure, altitude 7,500 ft VFR, Runway 07, Squawk 7000, A4O-OAD.

      **Controller:** A4O-OAD, readback correct. QNH 1004, Report ready for start-up.

### 3.7.2 VFR Traffic Remaining in Circuit
All VFR aircraft shall be instructed to conduct circuits to the south of the aerodrome (left-hand circuits for 25 and right-hand circuits for 07) at an altitude of 1,100 ft.

All VFR departures shall initially be assigned a squawk code of 7000. Salalah Tower may issue a discrete squawk code for identification purposes if necessary.