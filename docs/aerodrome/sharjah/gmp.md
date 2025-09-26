# 2. Departure Clearance Procedures
## 2.1 General provisions
Ground Movement Control (GMC) is responsible for validating routes and shall provide IFR clearance 
to departing aircraft. The controller shall assign the correct departure procedure to the aircraft 
based on the first point that is filed on the flight plan.

Where the flight plan contains an invalid route, level, or departure procedure, GMC shall ensure that 
the error is corrected before the aircraft is given its clearance.

## 2.2 Departure clearance
#### 2.2.1 General
GMC is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the 
following information on first contact:

- Callsign;
- Aircraft type;
- Parking stand;
- Destination;
- Requested Flight level;
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

    **Controller:** ABY463, Sharjah ground, cleared to Delhi via DAVMO3R, maintain altitude 3000ft, when airborne contact Dubai departures on 124.675, squawk 1743.

    **Pilot:** Cleared to Delhi via DAVMO3R, maintain altitude 3000ft, when airborne contact Dubai departures on 124.675, squawk 1743, ABY463.

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

<figure markdown>
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
    **Pilot:** Sharjah Ground, ABY45C, Airbus A320, Stand 4, Information M, request clearance to Moscow, unable RNAV SIDs.

    **Controller:** ABY45C, Sharjah Ground, cleared to Moscow, expect radar vectors, maintain altitude 2000ft, when airborne contact Dubai departures on 124.675, Squawk 3427.

    **Pilot:** Cleared to Moscow, radar vectors, maintain altitude 2000ft, when airborne contact Dubai Departures on 124.675, Squawk 3427, ABY45C.
    
    **Controller:** ABY45C, Readback correct, report ready for push and start, QNH1016.

<figure markdown>
|  SID 30   |  Initial Climb  |  SID 12   |  Initial Climb  |
|-----------|-----------------|-----------|-----------------|
|  ANVIX5R  |     3000ft      |  ANVIX4Q  |     2000ft      |
|  DAVMO3R  |     3000ft      |  DAVMO4Q  |     3000ft      |
|  EMERU1R  |     3000ft      |  EMERU1Q  |     3000ft      |
|  IVURO1R  |     3000ft      |  IVURO1Q  |     3000ft      |
|  KUTLI3R  |     3000ft      |  KUTLI3Q  |     3000ft      |
|  MIROT2R  |     2000ft      |  MIROT3Q  |     3000ft      |
|  NABIX2R  |     2000ft      |  NABIX3Q  |     3000ft      |
|  RIDAP2R  |     2000ft      |  RIDAP3Q  |     3000ft      |
|  SENPA2R  |     2000ft      |  SENPA3Q  |     3000ft      |

  <figcaption>Table 2-2: Initial Climbs</figcaption>
</figure>
 
!!! note
    Aircraft on a radar departure shall have the text *VECTORS* inserted to the scratchpad section of their entry on the departure list.

!!! info
    All IFR departures shall be instructed to contact DEP 2 when airborne.

## 2.4 Rerouting aircraft
An aircraft shall be issued a reroute by GMP if the pilot’s route doesn’t comply with the standard routes laid out in Table 2-2. 

Several routing restrictions exist within UAE airspace and must be complied with when issuing a departure clearance.

!!! note
    The Arabian vACC Operations Department maintains an up-to-date route database on SimBrief. These routes can be accessed by selecting the ***"User Submitted Routes"*** option, highlighted in purple, when planning a flight.

<figure markdown>
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

  <figcaption>Table 2-3: Standard routes</figcaption>
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
      **Pilot:** Sharjah ground, A6-CTK, SR22, request eastbound departure on track Fujairah, altitude 6500ft.

      **Controller:** A6-CTK, Sharjah ground, cleared eastbound departure, altitude 6500ft VFR, Runway 30, Squawk 0611.

      **Pilot:** Cleared eastbound departure, altitude 6500ft VFR, Runway 30, Squawk 0611, A6-CTK.

      **Controller:** A6-CTK, readback correct. QNH 1003, Report ready for start-up.

### 2.7.3 VFR traffic remaining in circuit
VFR traffic wishing to remain in the circuit shall be cleared only after prior coordination with AIR and Approach/Departure control.

As per possible restrictions mentioned in 2.8, VFR traffic may be encouraged to carry out circuits at neighbouring aerodromes such as OMDW, and OMRK during periods of increased IFR activity and due to restrictions to aircraft type. GMP must coordinate with AIR control and Arrivals/Departures control in such cases and relay the information to the pilot in accordance with 2.7.1 or 2.7.2.

VFR circuits shall not be permitted out of OMSB if any of the aforementioned restrictions from AIR and Approach/Departure control is in effect. 

All VFR circuit traffic shall be assigned a discrete SSR code so that they may be identified on radar.

All VFR aircraft shall be instructed to conduct circuits to the north of the aerodrome (right-hand circuits for 30 and left-hand circuits for 12R) at an altitude of 1000 ft. Aircraft may also be cleared to conduct circuits at 1500 ft, if required.