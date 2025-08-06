# 3. Departure Clearance Procedures
## 3.1 General Provisions
Airways clearance/Ground Movement Planner (GMP) is responsible for validating routes and shall provide IFR clearance to departing aircraft. The controller shall assign the correct departure procedure to the aircraft based on the first point that is filed on the flight plan.

Where the flight plan contains an invalid route, level, or departure procedure, GMP must ensure that the error is corrected before the aircraft is given its clearance.

GMP is also responsible for minimizing taxiway delays and taxiway congestion for departing aircraft. During times of increased departure activity, aircraft are held at the gate to save fuel and lessen taxiway congestion.

## 3.2 Departure clearance
### 3.2.1 General
GMP is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the following information on first contact: 

- Callsign;
- Aircraft type;
- D-ATIS letter;
- Parking stand;
- Destination;
- Requested flight level;

### 3.2.2 Information contained in a departure clearance
An IFR clearance shall be in the following format:

- Callsign;
- Destination;
- Airways and Muscat FIR exit point;
- Departure procedure;
- Initially cleared altitude;
- Assigned SSR code

GMP shall obtain a full readback of the clearance. If the pilot does not report the current ATIS letter on first contact, GMP shall pass the current ATIS letter and QNH.

Departing aircraft shall be instructed to remain on the delivery frequency and report ready to push before being handed off to GMC. This is so aircraft may be held at the gate, as per the procedures laid down in 2.6.

!!! example
    **Pilot**: "Muscat Clearance Delivery, OMS735, Airbus A320 NEO, information R, stand 105, requesting FL310, to Hyderabad."

    **Controller**: "OMS735, Muscat Clearance Delivery, information R correct, cleared to Hyderabad via N881 to RASKI, ITLAK1N departure, maintain altitude 3,000 ft, squawk 4701."

    **Pilot**: "Cleared to Hyderabad via N881 to RASKI, ITLAK1N departure, maintain altitude 3,000 ft, squawk 4701, OMS735."

    **Controller**: "OMS735, readback correct, QNH 1016, report ready for pushback."

### 3.2.3 Datalink clearance (DCL)
Muscat Aerodrome does not support the issuance of departure clearances via datalink (ACARS). All clearances shall be obtained through voice communication.

### 3.2.4 Aircraft requiring a reroute
Aircraft requiring a reroute shall be communicated through voice communication or via private message.

### 3.2.5 Voice clearance
Aircraft requesting clearance via voice shall be given a voice clearance as per the format in 3.2.2.

## 3.3 Departure Procedures
### 3.3.1 RNAV Standard instrument departures
Muscat has published RNAV Standard Instrument Departures (SIDs), which are the preferred departure procedures for IFR aircraft. However, as of the current publication, these RNAV SIDs are suspended due to ongoing aerodrome and airspace restructuring.

In the interim, only four temporary SIDs are in use. As such, only the following SIDs shall be assigned:

| Runway |   SID   | Initial Climb |
|:------:|:-------:|:-------------:|
|   08L  | MURMA1N |    3,000 ft   |
|   08R  |  S08R D |    3,000 ft   |
|   26L  |  S26L D |    3,000 ft   |
|   26R  | ITLAK1N |    3,000 ft   |

These temporary SIDs require aircraft to maintain runway heading on departure climbing to 3,000 feet. Departing aircraft can expect to receive radar vectors from Muscat Approach to join their filed airways.

In the absence of an online Approach controller, pilots are responsible for self-navigation and must vector themselves to join their respective filed airways.

!!! warning
    Runway 08R/26L is fully operational in the real world. However, in most simulator sceneries, this runway is either nonexistent or still under construction. Therefore, by default, this runway shall not be used and may only be assigned when requested by the pilot and confirmed to be available in their scenery.

## 3.4 Rerouting aircraft
An aircraft shall be issued a reroute by GMP if the pilot’s route doesn’t comply with the standard routes laid out in Table 3-2. 

Several routing restrictions exist within Muscat airspace and are detailed in the Oman Route Manual which must be complied with when issuing a departure clearance. 

If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged.

The Arabian vACC Operations Department maintains an up-to-date route database on SimBrief. These routes can be accessed by selecting the "User Submitted Routes" option, highlighted in purple, when planning a flight. These routes also appear as "blue" routes, that are Eurocontrol IFPS compliant. 

!!! example
    **Controller**: "OMS735, cleared to Hyderabad via the ITLAK1N departure, SEVLA - Q250 - KIPOL - N881 - RASKI, flight planned route. maintain altitude 3,000 ft, squawk 4701."

<table><thead>
  <tr>
    <th>Destination</th>
    <th>Level Restriction</th>
    <th>Airway/Exit Point</th>
  </tr></thead>
<tbody>
  <tr>
    <td>VAGO, VCBI, VOBL, VOCB, VOCI, VOCL, VOML, VOTR, VOTV</td>
    <td>-</td>
    <td>KITAL, LOTAV, REXOD, TOTOX</td>
  </tr>
  <tr>
    <td>VAPO &amp; VOMM</td>
    <td>-</td>
    <td>PARAR, TOTOX</td>
  </tr>
  <tr>
    <td>VOHS</td>
    <td>-</td>
    <td>RASKI</td>
  </tr>
  <tr>
    <td>VABB</td>
    <td>-</td>
    <td>RASKI, PARAR</td>
  </tr>
  <tr>
    <td>Transiting Tehran FIR</td>
    <td>-</td>
    <td>N718 ITRAX</td>
  </tr>
  <tr>
    <td>OMRK, OMSJ</td>
    <td>FL200</td>
    <td>T508 DAPOK T509 PASOV B540 KUPMA</td>
  </tr>
  <tr>
    <td>OMDB</td>
    <td>FL200</td>
    <td>T508 SOLUD GISMO</td>
  </tr>
  <tr>
    <td>OMDM, OMDW</td>
    <td>FL200</td>
    <td>T508 DAPOK L559 TAPRA M762 VAXAS</td>
  </tr>
  <tr>
    <td>Northern U.A.E Airports</td>
    <td>FL200</td>
    <td>T508 DAPOK L559/T509</td>
  </tr>
  <tr>
    <td>OOKB</td>
    <td>-</td>
    <td>Z890 BUBAS</td>
  </tr>
</tbody></table>

## 3.5 Requested cruising level
### 3.5.1 Level restrictions
Aircraft routes out of the aerodrome must comply with all routing and level restrictions as described in section 3.1 of Arabian MATS P1, Arabian Route Manual and Table 3-2. This is based on direction and type of flight. 

Should an aircraft file an invalid cruise level, GMP shall advise the aircraft of this when delivering the clearance. In all cases, the next lowest valid cruise level shall be assigned, and the aircraft advised.

## 3.6 Runway change procedure
AIR shall provide ample notice to GMP before changing runway configuration. The last departure using the old configuration shall be coordinated between AIR, GMP, GMC and approach/departure. 

Aircraft that have already been cleared to depart using the old configuration shall be re-cleared if they have not already requested pushback.

## 3.8 VFR aircraft
VFR traffic clearances are managed by AIR at the holding point. When an aircraft first contacts the delivery frequency, it must provide the following information:

- Callsign;
- Aircraft type;
- Current position;
- Person(s) on board;
- Current ATIS;
- Intentions;

After the initial call with all required information, GMP will issue a start-up clearance and relay the details to GMC & AIR for coordination.

!!! example
    **Pilot**: "Muscat Clearance Delivery, A4O-OAD, Diamond DA40, at the general aviation apron, 2 POB, with information C, for local flight to the north-west, request start-up."

    **Controller**: "A4O-OAD, Muscat Clearance Delivery, information C is correct, start-up is approved, report ready for taxi."

    **Pilot**: "Start-up is approved, wilco, A4O-OAD."

    -

    **Pilot**: "A4O-OAD, request taxi."

    **Controller**: "A4O-OAD, contact Muscat Ground on 121.875."

Upon handoff from the delivery controller, the Ground controller shall taxi the aircraft to the assigned departure runway, as previously coordinated.

Once the aircraft reaches the designated holding point, it shall be transferred to the Tower frequency, where the pilot will receive their VFR departure clearance.

### 3.8.1 VFR departures into uncontrolled airspace
VFR flight activity should be planned in accordance to published VFR charts, specifically the “**Muscat Visual Approach**” chart for VFR traffic navigating out of the Muscat CTR into neighbouring airspaces. GMP may use the appropriate charts as per the requirements of the pilot’s intentions in accordance with 3.7.1 and 3.7.2.

### 3.7.1 VFR Departures into Controlled Airspace
VFR traffic shall be cleared via the most appropriate VFR route towards their destination. As Muscat Approach operates within the Muscat CTR (Class C), coordination with Muscat Approach is required when online for all VFR departures.

All VFR departures shall initially be assigned a squawk code of 7000. Muscat Approach may issue a discrete squawk code for identification purposes if necessary.

!!! example
      **Pilot:** Muscat Tower, A4O-OAD, holding point Y6, runway 26R.

      **Controller:** A4O-OAD, Muscat Tower, cleared to exit the Muscat CTR via the NW departure, altitude 4,500 ft VFR, squawk 7000.

      **Pilot:** Cleared to exit the Muscat CTR via the NW departure, altitude 4,500 ft VFR, Squawk 7000, A4O-OAD.

      **Controller:** A4O-OAD, readback correct. QNH 1004, Report ready for departure.

### 3.7.2 VFR Traffic Remaining in Circuit
All VFR aircraft shall be instructed to conduct circuits to the north of the aerodrome (left-hand circuits for 08L and right-hand circuits for 26R) at an altitude of 1,000 ft.

All VFR departures shall initially be assigned a squawk code of 7000. Muscat Tower may issue a discrete squawk code for identification purposes if necessary.