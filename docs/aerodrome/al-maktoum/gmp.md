# 3. Departure Clearance Procedures
## 3.1 General provisions
Ground Movement Control (GMC) is responsible for validating routes and shall provide IFR clearance to departing aircraft. The controller shall assign the correct departure procedure to the aircraft based on the first point that is filed on the flight plan.

Where the flight plan contains an invalid route, level, or departure procedure, GMC shall ensure that the error is corrected before the aircraft is given its clearance.

## 3.2 Departure clearance
### 3.2.1 General
The GMC is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the following information on first contact:

- Aircraft Callsign;
- Aircraft type;
- Parking Stand;
- Destination;
- Dubai CTA exit point;
- Speed if unable to comply with minimum speed on the SID;
- ATIS letter & QNH

### 3.2.2 Information contained in a departure clearance
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



### 3.2.3 Datalink clearance (DCL)
Aircraft clearance may also be delivered by DCL. This type of clearance reduces controller workload and frequency congestion. For suitably equipped aircraft, this will be through the ACARS system on board the aircraft.

### 3.2.4 Aircraft requiring a reroute
If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged.

An aircraft shall be issued a reroute by GMC if the pilot’s route doesn’t comply with the standard routes laid out in Table 3-2.

### 3.2.5 Voice clearance
Aircraft requesting clearance via voice shall be given a voice clearance as per the format in 3.2.2.

## 3.3 Departure Procedures
### 3.3.1 RNAV Standard instrument departures
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
  <figcaption>Table 3-1: RNAV SIDs</figcaption>
</figure>

!!! info
      All aircraft shall be assigned an initial climb of **3000ft**. 


### 3.3.2 Radar departures
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


## 3.4 Rerouting aircraft


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
  <figcaption>Table 3-2: Standard routes</figcaption>
</figure>

!!!info 
      Should an aircraft file an invalid cruise level, GMC shall advise the aircraft of this when delivering the clearance. In **all** cases, the next lowest valid cruise level should be assigned and the aircraft advised.

!!!note
      Offering two valid levels (one above and below their requested level) is discouraged; a lower level than what is requested can be complied with certainty factoring the aircraft's maximum capable cruise level as per their gross weight. On the other hand, higher levels may be rejected due to aircraft performance or maximum cruise altitude capabilities.

      Thus, resorting to issuing the next lowest valid cruise level minimises radio transmissions and simplifies the correction process between the controller and the aircraft.


## 3.5 Runway change procedure
Runway change shall be coordinated with Al Maktoum AIR

## 3.6 VFR aircraft
VFR flight activity should be planned in accordance to published VFR charts, specifically the “**Dubai CTA VFR**” chart for VFR traffic navigating out of the Al Maktoum CTR into neighbouring airspaces and within the Al Maktoum control zone. GMC may use the appropriate charts as per the requirements of the pilot’s intentions in accordance with 2.6.1, 3.6.2 and 3.6.3.

At any time, AIR control and Approach/Departure control may impose partial or full restrictions to VFR operations out of OMDW during periods of increased IFR activity or due to restrictions and limitations to aircraft type. It is imperative that GMC is in continuous coordination with AIR control and Approach/Departure control for departing VFR traffic.

### 3.6.1 VFR departures into uncontrolled airspace
VFR traffic shall be cleared via the most appropriate VFR route towards their destination. If necessary, the clearance may be amended by AIR prior to departure.

All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

### 3.6.2 VFR departures into controlled airspace
VFR aircraft requesting clearance to climb into approach airspace (above 1500 ft) shall only be cleared after prior coordination with approach/departure control. Otherwise, they shall be instructed to remain outside controlled airspace after leaving the control zone.

All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

!!! example
      **Pilot:** Al Maktoum Ground, A6-CTK, SR22, request eastbound departure on track Fujeirah, altitude 6500ft.

      **Controller:** A6-CTK, Al Maktoum Ground, cleared eastbound departure, altitude 6500ft VFR, Runway 30, Squawk 0611.

      **Pilot:** Cleared eastbound departure, altitude 6500ft VFR, Runway 30, Squawk 0611, A6-CTK.

      **Controller:** A6-CTK, readback correct, information A, QNH 1003, Report ready for start-up.

### 3.6.3 VFR traffic remaining in circuit
VFR traffic wishing to remain in the circuit shall be cleared only after prior coordination with AIR and Approach/Departure control.
All VFR circuit traffic shall be assigned a discrete SSR code so that they may be identified on radar.

All VFR aircraft shall be instructed to conduct circuits to the north of the aerodrome (right-hand circuits for 30 and left-hand circuits for 12) at an altitude of 1000 ft. EFTA aircraft shall be instructed to conduct circuits to the south of the aerodrome (left-hand circuits for 31 and right-hand circuits for 13) at an altitude of 1000 ft, **only** during the academy operational hours. Aircraft may also be cleared to conduct circuits at 1500 ft, if required.