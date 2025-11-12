# 2. Departure Clearance Procedures
## 2.1 General provisions
The Ground Movement Controller (GMC) is responsible for validating routes and shall provide IFR clearance to departing aircraft. The controller shall assign the correct departure procedure to the aircraft based on the first point that is filed on the flight plan.

Where the flight plan contains an invalid route, level, or departure procedure, GMC must ensure that the error is corrected before the aircraft is given its clearance.

GMC is also responsible for minimizing taxiway delays and taxiway congestion for departing aircraft. During times of increased departure activity, aircraft are held at the gate to save fuel and lessen taxiway congestion.

## 2.2 Departure clearance
### 2.2.1 General
GMC is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the following information on first contact: 

- Callsign;
- Aircraft type;
- Parking Stand;
- Requested flight level;
- Destination;
- SID;
- Speed if unable to comply with minimum speed on the SID

### 2.2.2 Information contained in a departure clearance
An IFR clearance shall be in the following format:

- Callsign;
- Destination;
- Departure procedure;
- Initially cleared altitude;
- Assigned SSR code

GMC shall obtain a full readback of the clearance. If the pilot does not report the current ATIS letter on first contact, GMC shall pass the current ATIS letter and QNH.

!!! example
    **Pilot**: "Al-Ain Ground, good evening, PK143, Airbus A320, stand 7, requesting FL380, to Islamabad, GIDIS1H departure, with information F on board."

    **Controller**: "PK413, information F correct, cleared to Islamabad via the GIDIS1H departure, maintain altitude 3000ft, squawk 0542."

    **Pilot**: "Cleared to Islamabad, GIDIS1H departure, maintain altitude 3000ft, squawk 0542, PK413."

    **Controller**: "PK413, readback correct, QNH 1008, report ready for pushback."

### 2.2.3 Datalink clearance (DCL)
Aircraft clearance may also be delivered by DCL. This type of clearance reduces controller workload and frequency congestion. For suitably equipped aircraft, this will be through the ACARS system on board the aircraft.

!!! info
    Controllers shall ensure that DCL is available to be used at all times.

### 2.2.4 Aircraft requiring a reroute
Aircraft requiring a reroute shall not be given a DCL. Instead, a voice clearance must be used. This shall be communicated by ACARS datalink message or on frequency.

### 2.2.5 Voice clearance
Aircraft requesting clearance via voice shall be given a voice clearance as per the format in 2.2.2.

## 2.3 Departure Procedures
### 2.3.1 RNAV Standard instrument departures
Al-Ain primarily uses RNAV standard instrument departures (SIDs) and is the preferred departure type for IFR aircraft. Departing aircraft shall be assigned an appropriate RNAV departure according to the first fix in the flight plan and runways in use.

SIDs which have an identifier ending in **H** are valid for **01**. SIDs with an identifier ending in **J** are valid for **19**. All departures have an initial climb of 3000ft (Table 3-1).

<figure markdown>
| First Fix |    01   |    19   |
|:---------:|:-------:|:-------:|
|   GIDIS   |    1H   |    1J   |
|   LABRI   |    2H   |    2J   |
|   MURGU   |    1H   |    1J   |
|   RETAS   |    2H   |    2J   |
|   ROVOS   |    1H   |    1J   |

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
    **Pilot**: "Al-Ain Ground, good evening, TCM1TM, Airbus A320, stand 8, requesting FL360, to Beirut, unable RNAV, with information X on board."

    **Controller**: "TCM1TM, information X correct, cleared to Beirut via the omnidirectional departure, maintain altitude 3000ft, squawk 0527."

    **Pilot**: "Cleared to Beirut, omnidirectional departure, maintain altitude 3000ft, squawk 0527."

    **Controller**: "TCM1TM, readback correct, QNH 1014, report ready for pushback."

## 2.4 VFR Aircraft
VFR flight activity should be planned in accordance to published VFR charts, specifically the “VFR Helicopter Entry/Exit Points” chart for VFR traffic navigating out of the Al Ain CTR into neighbouring airspaces and within the Al Ain control zone. GMC may use the appropriate charts as per the requirements of the pilot’s intentions in accordance with xxx

At any time, AIR control and Approach/Departure control may impose partial or full restrictions to VFR operations out of OMDW during periods of increased IFR activity or due to restrictions and limitations to aircraft type. It is imperative that GMC is in continuous coordination with AIR control and Approach/Departure control for departing VFR traffic.

### 2.4.1 VFR Departures into uncontrolled airspace
VFR traffic shall be cleared via the most appropriate VFR route towards their destination. If necessary, the clearance may be amended by AIR prior to departure.

All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

### 2.4.2 VFR Departures into controlled airspace
VFR aircraft requesting clearance to climb into approach airspace (above 2500 ft) shall only be cleared after prior coordination with approach/departure control. Otherwise, they shall be instructed to remain outside controlled airspace after leaving the control zone.

All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

!!! example
      **Pilot:** Al-Ain Ground, A6-CTK, DA40 , request south-eastbound departure on track Abu Dhabi, altitude 5500ft.

      **Controller:** A6-CTK, Al-Ain Ground, cleared eastbound departure, altitude 5500ft VFR, Runway 19, Squawk 0646.

      **Pilot:** Cleared eastbound departure, altitude 5500ft VFR, Runway 19, Squawk 0646, A6-CTK.

      **Controller:** A6-CTK, readback correct, information T, QNH 1001, Report ready for start-up.

### 2.4.3 VFR traffic remaining in circuit
VFR traffic wishing to remain in the circuit shall be cleared only after prior coordination with AIR and Approach/Departure control. All VFR circuit traffic shall be assigned a discrete SSR code so that they may be identified on radar.