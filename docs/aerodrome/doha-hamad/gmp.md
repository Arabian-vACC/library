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
- Departure D-ATIS letter;
- Parking stand;
- Requested flight level;
- Destination;

### 3.2.2 Information contained in a departure clearance
An IFR clearance shall be in the following format:

- Callsign;
- Destination;
- Departure procedure;
- Initially cleared altitude;
- Assigned SSR code

GMP shall obtain a full readback of the clearance. If the pilot does not report the current ATIS letter on first contact, GMP shall pass the current ATIS letter and QNH.

Departing aircraft shall be instructed to remain on the delivery frequency and report ready to push before being handed off to GMC. This is so aircraft may be held at the gate, as per the procedures laid down in 3.6.

!!! example
    **Pilot**: "Hamad Clearance Delivery, QTR6M, Boeing 777-300ER, information X, stand B3, requesting FL310, to Melbourne."

    **Controller**: "QTR6M, Hamad Clearance Delivery, information X correct, cleared to Melbourne via the BUNDU2E departure, climb via the SID to altitude 4000ft, squawk 2613."

    **Pilot**: "Cleared to Melbourne via the BUNDU2E departure, climb via the SID to altitude 4000ft, squawk 2613, QTR6M."

    **Controller**: "QTR6M, readback correct, QNH 1016, report ready for pushback."

!!! info
    The initial cleared altitude is stated as "Climb via the SID." At Doha-Hamad, SIDs do not include a preset initial climb. The clearance issued corresponds to the first hard altitude restriction. It's crucial for controllers to understand the difference between standard "initial climb" phraseology and correctly use "climb via the SID" at Doha-Hamad.

!!! warning
    As per the Qatari eAIP "***Requests for the runway in use should be avoided.***" This must be adhered to on frequency, as outlined in section 3.3.1, where each SID is specific to its assigned runway.

### 3.2.3 Datalink clearance (DCL)
Aircraft clearance may also be delivered by DCL. This type of clearance reduces controller workload and frequency congestion. For suitably equipped aircraft, this will be through the ACARS system on board the aircraft.

!!! info
    Controllers shall ensure that DCL is available to be used at all times.

### 3.2.4 Aircraft requiring a reroute
Aircraft requiring a reroute shall not be given a DCL. Instead, a voice clearance must be used. This shall be communicated by ACARS datalink message or on frequency.

### 3.2.5 Voice clearance
Aircraft requesting clearance via voice shall be given a voice clearance as per the format in 3.2.2.

## 3.3 Departure Procedures
### 3.3.1 RNAV Standard instrument departures
Doha-Hamad primarily uses RNAV standard instrument departures (SIDs) and is the preferred departure type for IFR aircraft. Departing aircraft shall be assigned an appropriate RNAV departure according to the first fix in the flight plan and the direction of their flight plan.

Check the table below to see which SID corresponds to each runway. Keep in mind that these SIDs are assigned based on the flight's direction. 

For instance, flights departing the TMA toward the northeast will use runway 16L/34R, while those heading southwest will use runway 16R/34L. Note that the initial climb instructions are stated as "Climb via the SID."

!!! warning
    Controllers must ensure that the correct SID is assigned based on the specific runway and the flight's direction. If a runway does not have an assigned SID on the departure list, it is not an error. SIDs are runway-specific and depend on the flight’s direction. 
    
    Assigning an incorrect runway for a given direction will cause EuroScope to default to a radar-vectored departure, such as KASIS, IVENA, PARES, or DEMBO. If one of these four departures appears, it indicates that the runway assigned does not match the intended direction of flight, and the runway assignment should be reviewed and corrected accordingly.

!!! note
    The TULUB departure is available for both runways and should be assigned based on runway capacity and the current departure rate. Coordination with the relevant APP controller is required.

<table><thead>
  <tr>
    <th>SID<br>16L</th>
    <th>Initial Climb</th>
    <th>SID<br>16R</th>
    <th>Initial Climb</th>
    <th>SID<br>34L</th>
    <th>Initial Climb</th>
    <th>SID<br>34R</th>
    <th>Initial Climb</th>
  </tr></thead>
<tbody>
  <tr>
    <td>ALSEM2M</td>
    <td>5000ft</td>
    <td>BUNDU2C</td>
    <td>7000ft</td>
    <td>DATRI1W</td>
    <td>4000ft</td>
    <td>ALSEM2E</td>
    <td>4000ft</td>
  </tr>
  <tr>
    <td>ALVEN2M</td>
    <td>5000ft</td>
    <td>DATRI1C</td>
    <td>7000ft</td>
    <td>LUBET1A</td>
    <td>10000ft</td>
    <td>ALVEN3E</td>
    <td>4000ft</td>
  </tr>
  <tr>
    <td>KASIS2</td>
    <td>5000ft</td>
    <td>IVENA2</td>
    <td>5000ft</td>
    <td>LUBET1W</td>
    <td>4000ft</td>
    <td>BUNDU2E</td>
    <td>4000ft</td>
  </tr>
  <tr>
    <td>KUPRO1M</td>
    <td>5000ft</td>
    <td>LUBET1C</td>
    <td>6000ft</td>
    <td>PARES2</td>
    <td>4000ft</td>
    <td>DEMBO3</td>
    <td>4000ft</td>
  </tr>
  <tr>
    <td>LUBET1M</td>
    <td>5000ft</td>
    <td>TULUB1C</td>
    <td>6000ft</td>
    <td><b>TULUB1A</b></td>
    <td>10000ft</td>
    <td>KUPRO1E</td>
    <td>4000ft</td>
  </tr>
  <tr>
    <td>LUBET1Y</td>
    <td>5000ft</td>
    <td>ULIKA1C</td>
    <td>7000ft</td>
    <td>TULUB1W</td>
    <td>4000ft</td>
    <td>LUBET2E</td>
    <td>4000ft</td>
  </tr>
  <tr>
    <td>TULUB1M</td>
    <td>5000ft</td>
    <td></td>
    <td></td>
    <td><b>ULIKA1A</b></td>
    <td>4000ft</td>
    <td>LUBET2Z</td>
    <td>4000ft</td>
  </tr>
  <tr>
    <td>VAXIN2M</td>
    <td>5000ft</td>
    <td></td>
    <td></td>
    <td>ULIKA1W</td>
    <td>4000ft</td>
    <td>TULUB2E</td>
    <td>4000ft</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td>VAXIN2E</td>
    <td>4000ft</td>
  </tr>
</tbody></table>
<figure markdown>
  <figcaption>Table 2-1: RNAV SIDs</figcaption>
</figure>

!!! warning
    The TULUB1A, LUBET1A and ULIKA1A are temporary procedures, so always check the latest NOTAMs for updates. The ULIKA1A departure is available from 22:00 to 01:00 UTC the following day, while the TULUB1A and LUBET1A are available from 07:00 to 04:00 UTC the following day .

### 3.3.2 RNP radar departure
The RNP radar departure procedure shall be used when aircraft are unable to accept a one of the published RNP departures. Whereas regular RNP departures follow a prescribed track until leaving the Doha TMA, the RNP radar departures proceed to a fix beyond the extended runway centerline before continuing along the transition out of the TMA.

An RNP radar departure clearance shall contain the following information:

- Callsign;
- Destination;
- RNP radar departure + transition;
- Initial climb;
- Assigned SSR code

Aircraft on an RNP radar departure shall have the appropriate SID inserted on the departure list (**e.g. KASIS2xBUNDU**). The KASIS and IVENA procedures have an initial climb altitude of **5000 feet**, whereas the DEMBO and PARES procedures have an initial climb altitude of **4000 feet**.

!!! example
    **Pilot**: "Hamad Clearance Delivery, IGO1346, Airbus A320, information T, stand G1, requesting FL310, to Delhi, unable standard SIDs."

    **Controller**: "IGO1346, Hamad Clearance Delivery, information T correct, cleared to Delhi via the KASIS2 departure, BUNDU transition, climb via the SID to altitude 5000ft, squawk 2612."

    **Pilot**: "Cleared to Delhi via the KASIS2 departure, BUNDU transition, climb via the SID to altitude 5000ft, squawk 2612, IGO1346."

    **Controller**: "IGO1346, readback correct, QNH 1016, report ready for pushback."

### 3.3.3 Radar vector departure
The radar vector departure procedure shall be used when aircraft are unable to accept an RNP departure, such as one with outdated nav data. Whereas RNP departures follow a prescribed track until leaving the Doha TMA, radar vector departures are given radar vectors to the first fix.

A radar departure clearance shall contain the following information:

- Callsign;
- Destination;
- Departure instructions;
- Initial climb;
- Assigned SSR code

Aircraft on a radar vectors departure shall have the text RDV inserted to the scratchpad section of their entry on the departure list. Aircraft assigned a radar vector departure should be given the runway that best matches their direction of flight. 

Runway 16L/34R should be used for eastbound departures, while runway 16R/34L is designated for westbound departures. The initial climb for runway 16L/34R shall be set to **4000 feet**, while for runway 16R/34L, it shall be set to **3000 feet**.

Departures heading eastbound shall be handed over to Doha Approach (East), while those heading westbound shall be transferred to Doha Approach (West).

!!! example
    **Pilot**: "Doha Ground, TCM1TM, Airbus A320, stand 512, clearance to Jeddah, unable RNAV, with information Z on board."

    **Controller**: "TCM1TM, Hamad Clearance Delivery, information Z correct, cleared to Jeddah via runway 34L, fly runway heading, expect radar vectors after departure, maintain altitude 3000ft, squawk 2610."

    **Pilot**: "Cleared to Jeddah via runway 34L, fly runway heading, expect radar vectors after departure, maintain altitude 3000ft, squawk 2610, TCM1TM."

    **Controller**: "TCM1TM, readback correct, QNH 1014, report ready for pushback."

## 3.4 Rerouting aircraft
An aircraft shall be issued a reroute by GMP if the pilot’s route doesn’t comply with the standard routes laid out in Table 2-2. 

Several routing restrictions exist within Qatari airspace and are detailed in the Qatari Route Manual which must be complied with when issuing a departure clearance. 

If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged.

The Arabian vACC Operations Department maintains an up-to-date route database on SimBrief. These routes can be accessed by selecting the "User Submitted Routes" option, highlighted in purple, when planning a flight.

!!! example
    **Controller**: "QTR30N, cleared to Zagreb via the TULUB2E departure, ALSEM - B457 - KINID, flight planned route. Climb via the SID altitude 4000ft, squawk 2612."

<table><thead>
  <tr>
    <th>Destination</th>
    <th>Level Restriction</th>
    <th>Routing</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Northern Emirates (OMDB, OMDW, OMFJ, OMFJ, OMRK, OMDM) (FL210 @ ASTOG)</td>
    <td>FL210</td>
    <td>ALSEM L305 ASTOG</td>
  </tr>
  <tr>
    <td>Southern Emirates (OMAA, OMAD, OMAM, OMAL) (Max FL210)</td>
    <td>FL270</td>
    <td>KUPRO</td>
  </tr>
  <tr>
    <td>Transiting Tehran FIR (FL230 @ DASUT)</td>
    <td>FL230</td>
    <td>VAXIN T800 DASUT</td>
  </tr>
  <tr>
    <td>Transiting Tehran FIR (FL190 @ RAGAS)</td>
    <td>FL190</td>
    <td>ALVEN T430 RAGAS</td>
  </tr>
  <tr>
    <td>Bahrain (OBBI, OBBS, OBKH)</td>
    <td>12,000ft</td>
    <td>TULUB B457 / M444 / T444 KINID</td>
  </tr>
  <tr>
    <td>Transiting Bahrain FIR onwards landing Kuwait FIR</td>
    <td>FL260</td>
    <td>TULUB B457 KINID</td>
  </tr>
  <tr>
    <td>Transiting Jeddah FIR onwards landing Kuwait FIR</td>
    <td>FL260</td>
    <td>TULUB M444 KINID</td>
  </tr>
  <tr>
    <td rowspan="2">Transiting Kuwait FIR</td>
    <td>FL260</td>
    <td>LUBET T934 IMLAD</td>
  </tr>
  <tr>
    <td>FL260</td>
    <td>LUBET L934 IMLAD</td>
  </tr>
</tbody></table>
<figure markdown>
  <figcaption>Table 2-2: Standard routes</figcaption>
</figure>

## 3.5 Requested cruising level
### 3.5.1 Level restrictions
Aircraft routes out of the aerodrome must comply with all routing and level restrictions as described in section 3.1 of Arabian MATS P1, Arabian Route Manual and Table 2-2. This is based on direction and type of flight. 

Should an aircraft file an invalid cruise level, GMP shall advise the aircraft of this when delivering the clearance. In all cases, the next lowest valid cruise level shall be assigned, and the aircraft advised.

## 3.6 Delay mitigation
### 3.6.1 Target off-block time (TOBT)
When A-CDM procedures are active, pilots must report their confirmed TOBT on vacdm.vatsim.me, which is then displayed in the controller's client on the departure list. A fully green time indicates a confirmed TOBT. If a pilot has not confirmed their TOBT, the controller should request it on frequency and update the departure list accordingly.

The TOBT system allows aircraft to push back, taxi to the runway holding point, and depart on schedule without extended delays in the departure queue. If an aircraft reports ready for pushback before its assigned TOBT, it will be instructed to hold position and will be given its place in the pushback sequence, unless aerodrome conditions permit and a slot is available. If an aircraft is cleared for push and start but does not begin pushing within 2-5 minutes, the pushback clearance is canceled, and a new TOBT is assigned.

!!! example
    **Controller**: "QTR1, hold position. Number 5 for startup, expect pushback at time 15."

## 3.7 Runway change procedure
AIR shall provide ample notice to GMP before changing runway configuration. The last departure using the old configuration shall be coordinated between AIR, GMP, GMC and approach/departure. 

Aircraft that have already been cleared to depart using the old configuration shall be re-cleared if they have not already requested pushback.

## 3.8 VFR aircraft
VFR traffic is not allowed at Hamad International Airport. Pilots intending to fly VFR are advised to operate from Doha International Airport (OTBD) instead.