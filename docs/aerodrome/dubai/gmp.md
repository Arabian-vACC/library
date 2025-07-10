# 3. Departure Clearance Procedures
## 3.1 General provisions
Airways clearance/Ground Movement Planner (GMP) is responsible for validating routes and shall provide IFR clearance to departing aircraft. The controller shall assign the correct departure procedure to the aircraft based on the first point that is filed on the flight plan.

Where the flight plan contains an invalid route, level, or departure procedure, GMP must ensure that the error is corrected before the aircraft is given its clearance.

GMP is also responsible for minimizing taxiway delays and taxiway congestion for departing aircraft. During times of increased departure activity, aircraft are held at the gate to save fuel and lessen taxiway congestion.

## 3.2 Departure clearance
### 3.2.1 General
GMP is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the following information on first contact: 

- Callsign;
- Aircraft type;
- Parking Stand;
- Requested flight level;
- Destination;
- SID;
- Speed if unable to comply with minimum speed on the SID

### 3.2.2 Information contained in a departure clearance
An IFR clearance shall be in the following format:

- Callsign;
- Destination;
- Departure procedure;
- Initially cleared altitude;
- Assigned SSR code

GMP shall obtain a full readback of the clearance. If the pilot does not report the current ATIS letter on first contact, GMP shall pass the current ATIS letter and QNH.

Departing aircraft shall be instructed to remain on the delivery frequency and report ready to push before being handed off to GMC. This is so aircraft may be held at the gate, as per the procedures laid down in 2.6.

!!! example
    **Pilot**: "Dubai Delivery, good evening, UAE1GP, Boeing 777-300ER, stand A8, requesting FL360, to Nice, NABIX3F departure, with information F on board."

    **Controller**: "UAE1GP, information F correct, cleared to Nice via the NABIX3F departure, maintain altitude 4000ft, squawk 0542."

    **Pilot**: "Cleared to Nice, NABIX3F departure, maintain altitude 4000ft, squawk 0542, UAE1GP."

    **Controller**: "UAE1GP, readback correct, QNH 1008, report ready for pushback."

### 3.2.3 Datalink clearance (DCL)
Aircraft clearance may also be delivered by DCL. This type of clearance reduces controller workload and frequency congestion. For suitably equipped aircraft, this will be through the ACARS system on board the aircraft.

!!! info
    Controllers shall ensure that DCL is available to be used at all times.

### 3.2.4 Aircraft requiring a reroute
Aircraft requiring a reroute shall not be given a DCL. Instead, a voice clearance must be used. This shall be communicated by ACARS datalink message or on frequency.

### 3.2.5 Voice clearance
Aircraft requesting clearance via voice shall be given a voice clearance as per the format in 2.2.2.

## 3.3 Departure Procedures
### 3.3.1 RNAV Standard instrument departures
Dubai primarily uses RNAV standard instrument departures (SIDs) and is the preferred departure type for IFR aircraft. Departing aircraft shall be assigned an appropriate RNAV departure according to the first fix in the flight plan and runways in use.

SIDs which have an identifier ending in **F** are valid for **30L/R**. SIDs with an identifier ending in **G** are valid for **12L/R**. All departures have an initial climb of 4000ft (Table 3-1).

| First Fix | 30L/30R | 12L/12R |
|:---------:|:-------:|:-------:|
|   ANVIX   |    7F   |    5G   |
|   DAVMO   |    4F   |    4G   |
|   EMERU   |    2F   |    2G   |
|   IVURO   |    1F   |    1G   |
|   KUTLI   |    4F   |    4G   |
|   MIROT   |    3F   |    3G   |
|   NABIX   |    3F   |    3G   |
|   RIDAP   |    2F   |    3G   |
|   SENPA   |    2F   |    3G   |
<figure markdown>
  <figcaption>Table 3-1: RNAV SIDs</figcaption>
</figure>

### 3.3.2 Omnidirectional departures
The omnidirectional departure procedure shall be used when aircraft are unable to accept an RNAV departure. Whereas RNAV departures follow a prescribed track until leaving the Dubai Departures airspace, omnidirectional departures are given radar vectors to the first fix.

In the take-off clearance. Air Control (AIR) may assign a heading from within a “heading fan” of valid headings.

An Omnidirectional departure clearance shall contain the following information:

- Callsign;
- Destination;
- Omnidirectional departure;
- Initial climb;
- Initial heading (which may be changed by AIR);
- Assigned SSR code

Aircraft on an omnidirectional departure shall have the text OMNI inserted to the scratchpad section of their entry on the departure list.

!!! example
    **Pilot**: "Dubai Delivery, good evening, TCM1TM, Airbus A320, stand C59, requesting FL360, to Beirut, unable RNAV, with information X on board."

    **Controller**: "TCM1TM, information X correct, cleared to Beirut via the omnidirectional departure, maintain altitude 4000ft, squawk 0527."

    **Pilot**: "Cleared to Beirut, omnidirectional departure, maintain altitude 4000ft, squawk 0527."

    **Controller**: "TCM1TM, readback correct, QNH 1014, report ready for pushback."

## 3.4 Rerouting aircraft
An aircraft shall be issued a reroute by GMP if the pilot’s route doesn’t comply with the standard routes laid out in Table 3-2. 

Several routing restrictions exist within UAE airspace and are detailed in the UAE Route Manual which must be complied with when issuing a departure clearance. 

If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged.

The Arabian vACC Operations Department maintains an up-to-date route database on SimBrief. These routes can be accessed by selecting the "User Submitted Routes" option, highlighted in purple, when planning a flight.

!!! example
    **Controller**: "RJA615, cleared to Amman, via SENPA1G, SENPA N571 ALPOB L768 ULADA, flight planned route. Maintain 4000ft, squawk 0553."

<table><thead>
  <tr>
    <th>Destination</th>
    <th>Level Restrictions</th>
    <th>Routing</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Tehran FIR Northbound</td>
    <td>-</td>
    <td>DAVMO M318 GABKO</td>
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
    <td>Landing within Bahrain FIR (including OBBI)</td>
    <td>Max FL260</td>
    <td>NABIX P699 ORMID</td>
  </tr>
  <tr>
    <td>Landing OEDF, OEDR</td>
    <td>- </td>
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
    <td rowspan="2">Landing/transiting Sanaa FIR and south Jeddah FIR</td>
    <td rowspan="2">-</td>
    <td>KUTLI L519 ATUDO M318 GOLGU M550 RIBOT</td>
  </tr>
  <tr>
    <td>KUTLI L519 ATUDO M318 KATIT</td>
  </tr>
  <tr>
    <td>Landing OOMS, transiting Muscat FIR Eastbound and Southeast bound</td>
    <td>-</td>
    <td>ANVIX L223 TARDI</td>
  </tr>
  <tr>
    <td>Landing OOSA, transiting Muscat FIR Southbound and Southwest bound</td>
    <td>-</td>
    <td>ANVIX R401 GIDIS G783 UKRAG L710 MEMTU</td>
  </tr>
  <tr>
    <td>Landing OOSH</td>
    <td>At 11,000 ft</td>
    <td>ANVIX L223 TARDI</td>
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
    <td>OMAA &amp; OMAD</td>
    <td>Max 10,000 ft</td>
    <td>DCT EMERU</td>
  </tr>
  <tr>
    <td>OMAL</td>
    <td>-</td>
    <td>DCT ANVIX R401 GIDIS G783 VAVIM</td>
  </tr>
  <tr>
    <td>OMDW, OMSJ, OMRK, and OMFJ</td>
    <td>Max 7,000 ft</td>
    <td>DCT (RADAR VECTORS) (Omnidirectional departure)</td>
  </tr>
</tbody></table>
<figure markdown>
  <figcaption>Table 3-2: Standard routes</figcaption>
</figure>

## 3.5 Requested cruising level
### 3.5.1 Level restrictions
Aircraft routes out of the aerodrome must comply with all routing and level restrictions as described in section 3.1 of Arabian MATS P1, Arabian Route Manual and Table 3-2. This is based on direction and type of flight. 

Should an aircraft file an invalid cruise level, GMP shall advise the aircraft of this when delivering the clearance. In all cases, the next lowest valid cruise level shall be assigned, and the aircraft advised.

## 3.6 Delay mitigation
### 3.6.1 Target off-block time (TOBT)
When A-CDM procedures are active, pilots must report their confirmed TOBT on vacdm.vatsim.me, which is then displayed in the controller's client on the departure list. A fully green time indicates a confirmed TOBT. If a pilot has not confirmed their TOBT, the controller should request it on frequency and update the departure list accordingly.

The TOBT system allows aircraft to push back, taxi to the runway holding point, and depart on schedule without extended delays in the departure queue. If an aircraft reports ready for pushback before its assigned TOBT, it will be instructed to hold position and will be given its place in the pushback sequence, unless aerodrome conditions permit and a slot is available. If an aircraft is cleared for push and start but does not begin pushing within 2-5 minutes, the pushback clearance is canceled, and a new TOBT is assigned.

!!! example
    **Controller**: "FDB53, hold position. Number 3 for startup, expect pushback at time 45."

## 3.7 Runway change procedure
AIR shall provide ample notice to GMP before changing runway configuration. The last departure using the old configuration shall be coordinated between AIR, GMP, GMC and approach/departure. 

Aircraft that have already been cleared to depart using the old configuration shall be re-cleared if they have not already requested pushback.

## 3.8 VFR aircraft
VFR flight activity should be planned in accordance to published VFR charts, specifically the “**Dubai Creek VFR Routes**” chart for traffic navigating within the CTR and the “**Dubai CTA VFR**” chart for VFR traffic navigating out of the Dubai CTR into neighbouring airspaces. GMP may use the appropriate charts as per the requirements of the pilot’s intentions in accordance with 2.8.1, 2.8.2 and 2.8.3.  

At any time, AIR control and Approach/Departure control may impose partial or full restrictions to VFR operations out of OMDB during periods of increased IFR activity or due to restrictions and limitations to aircraft type. It is imperative that GMP is in continuous coordination with AIR control and Approach/Departure control for departing VFR traffic.

### 3.8.1 VFR departures into uncontrolled airspace
VFR traffic shall be cleared via the most appropriate VFR route towards their destination. If necessary, the clearance may be amended by AIR prior to departure.

All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

!!! example
    **Pilot**: "Dubai Delivery A6-CTL, Cirrus SR22, request clearance to Al-Maktoum, information charlie."

    **Controller**: "A6-CTL, Dubai Delivery, cleared to Al-Maktoum via Water Tank - VR7 - Road Crossing - VR6 - Club Intersection, Altitude 1000ft VFR, squawk 0611."

    **Pilot**: "Cleared to Al-Maktoum via Water Tank - VR7 - Road Crossing - VR6 - Club Intersection, altitude 1000ft VFR, squawk 0611, A6-CTL."

    **Controller**: "ATL, [readback] correct, information charlie correct, QNH 1003, report ready for start-up."

    **Pilot**: "QNH 1003, Wilco ATL"

### 3.8.2 VFR departures into controlled airspace
VFR aircraft requesting clearance to climb into approach airspace (above 1500 ft) shall only be cleared after prior coordination with Approach/Departure control. Otherwise, they shall be instructed to remain outside controlled airspace after leaving the control zone.

All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

!!! example
    **Pilot**: "Dubai Delivery A6-CTZ, Cirrus SR22, request departure to the south on track Abu Dhabi, altitude 6500ft."

    **Controller**: "A6-CTZ, Dubai Delivery, cleared on track Abu Dhabi, altitude 6500ft VFR, squawk 0415."

    **Pilot**: "Cleared on track Abu Dhabi, altitude 6500ft VFR, squawk 0415, A6-CTZ."

    **Controller**: "ATZ, [readback] correct, information sierra current, QNH 1003, report ready for start-up."

    **Pilot**: "QNH 1003, Wilco ATZ"

### 3.8.3 VFR traffic remaining in circuit
VFR traffic wishing to remain in the circuit shall be cleared only after prior coordination with AIR and Approach/Departure control.

As per possible restrictions mentioned in 2.8, VFR traffic may be encouraged to carry out circuits at neighbouring aerodromes such as OMDW, OMSJ and OMRK during periods of increased IFR activity and due to restrictions to aircraft type. GMP must coordinate with AIR control and Arrivals/Departures control in such cases and relay the information to the pilot in accordance with 2.8.1 or 2.8.2.

VFR circuits shall not be permitted out of OMDB if any of the aforementioned restrictions from AIR and Approach/Departure control is in effect. 

All VFR circuit traffic shall be assigned a discrete SSR code so that they may be identified on radar.

All VFR aircraft shall be instructed to conduct circuits to the south of the aerodrome from the southern runway (left-hand circuits for 30L and right-hand circuits for 12R) at an altitude of 1000 ft. Aircraft may also be cleared to conduct circuits at 1500 ft, if required.

!!! example
    **Pilot**: "Dubai Delivery A6-CTL, Cirrus SR22, request clearance for circuit patterns, information alpha."

    **Controller**: "A6-CTL, Dubai Delivery, cleared left-hand circuit, altitude 1000ft VFR, squawk 6022."

    **Pilot**: "Cleared left-hand circuit, altitude 1000ft VFR, squawk 6022, A6-CTL."

    **Controller**: "ATL, [readback] correct, information alpha correct, QNH 1003, report ready for start-up."

    **Pilot**: "QNH 1003, Wilco ATL"
