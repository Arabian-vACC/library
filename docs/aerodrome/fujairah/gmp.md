# 2. Departure Clearance Procedures
## 2.1 General provisions
Ground Movement Control (GMC) is responsible for validating routes and shall provide IFR clearance to departing aircraft. The controller shall assign the correct departure procedure to the aircraft based on the first point that is filed on the flight plan.

Where the flight plan contains an invalid route, level, or departure procedure, GMC shall ensure that the error is corrected before the aircraft is given its clearance.

## 2.2 Departure clearance
### 2.2.1 General
The GMC is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the following information on first contact:

- Aircraft Callsign;
- Aircraft type;
- Parking Stand;
- Destination;
- Dubai CTA exit point;
- Speed if unable to comply with minimum speed on the SID;
- ATIS letter & QNH;

### 2.2.2 Information contained in a departure clearance
An IFR clearance shall be in the following format:

- Callsign;
- Destination;
- Departure procedure;
- Initially cleared altitude;
- Assigned SSR code

GMC shall obtain a full readback of the clearance. If the pilot does not report the current ATIS letter on first contact, GMC shall pass the current ATIS letter and QNH.

Departing aircraft shall be instructed to report ready for pushback

!!! example
    **Pilot**: "Fujairah Ground, good evening, IGO1502, Airbus A320, stand 6, requesting IFR clearance to Mumbai."
    
    **Controller**: "IGO1502, cleared to Mumbai via the TONVO4F departure, maintain altitude 8000ft, squawk 0515."
    
    **Pilot**: "Cleared to Mumbai, TONVO4F departure, maintain altitude 8000ft, squawk 0515, IGO1502."

    **Controller**: "IGO1502, readback correct, information Kilo, QNH 1005, report ready for pushback."

### 2.2.3 Aircraft requiring a reroute
If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged.

An aircraft shall be issued a reroute by GMC if the pilot’s route doesn’t comply with the standard routes laid out in Table 3-2.

### 2.2.4 Voice clearance
Aircraft requesting clearance via voice shall be given a voice clearance as per the format in 2.2.2.

## 2.3 Departure Procedures
### 2.3.1 RNAV Standard instrument departures
Fujairah primarily uses RNAV standard instrument departures (SIDs) and is the preferred departure type for IFR aircraft. Departing aircraft shall be assigned an appropriate RNAV departure according to the first fix in the flight plan and the direction of their flight plan.

The table below displays which SID corresponds to each runway. Keep in mind that these SIDs are assigned based on the flight's direction.

<figure markdown>
| SID<br>11R   | Initial Climb | SID<br>29L   | Initial Climb |
|--------------|---------------|--------------|---------------|
| IMPED3F      | 6000ft        | IMPED1R      | 6000ft        |
| NOLSU3F      | 6000ft        | IMPED1S      | 6000ft        |
| KASIS2       | 6000ft        | NOLSU1R      | 6000ft        |
| RAV1F        | 6000ft        | RAV1R        | 6000ft        |
| UMAMI3F      | 6000ft        | UMAMI1R      | 6000ft        |
| GABKO4F      | 7000ft        | UMAMI1S      | 6000ft        |
| SERSA4F      | 7000ft        | GABKO1R      | 7000ft        |
| VAVIM2F      | 7000ft        | SERSA1R      | 7000ft        |
| TONVO4F      | 8000ft        | VAVIM1R      | 7000ft        |
|              |               | VAVIM1S      | 7000ft        |
|              |               | TONVO1R      | 8000ft        |

  <figcaption>Table 2-1: Initial climb table</figcaption>
</figure>

### 2.3.2 Radar departures
The radar departure procedure shall be used when aircraft are unable to accept an RNAV departure, such as one with outdated nav data. Whereas RNAV departures follow a prescribed track until leaving the Fujairah Departures airspace, radar departures are given radar vectors to the first fix.

In the take-off clearance, Air Control (AIR) shall assign a heading to fly after departure appropriate to the Fujairah CTA exit point.

A radar departure clearance shall contain the following information:

- Callsign;
- Destination;
- Departure instructions;
- Initially cleared altitude;
- Frequency handoff;
- Assigned SSR code

!!! note
    Aircraft on a radar departure shall have the text VECTORS inserted to the scratchpad section of their entry on the departure list.

## 2.3 Rerouting aircraft
An aircraft shall be issued a reroute by GMC if the pilot’s route doesn’t comply with the standard routes.

Several routing restrictions exist within UAE airspace and must be complied with when issuing a departure clearance.

!!! example
    **Controller**: "IGO1502, cleared to Mumbai, via TONVO4F, TONVO P307 PARAR N571 BEKUT Q9 EPKOS B211 ANIRO GUANI, flight planned route. Maintain 8000ft, squawk 0522."

!!! note
    The Arabian vACC Operations Department maintains an up-to-date route database on SimBrief. These routes can be accessed by selecting the ***"User Submitted Routes"*** option, highlighted in purple, when planning a flight.


!!!info 
    Should an aircraft file an invalid cruise level, GMC shall advise the aircraft of this when delivering the clearance. In **all** cases, the next lowest valid cruise level Should be assigned and the aircraft advised.

!!!note
    Offering two valid levels (one above and below their requested level) is discouraged; a lower level than what is requested can be complied with certainty factoring the aircraft's maximum capable cruise level as per their gross weight. On the other hand, higher levels may be rejected due to aircraft performance or maximum cruise altitude capabilities.

    Thus, resorting to issuing the next lowest valid cruise level minimises radio transmissions and simplifies the correction process between the controller and the aircraft.

## 2.4 Runway change procedure
Runway change shall be coordinated with Fujairah AIR

## 2.5 VFR aircraft
VFR flight activity should be planned in accordance to published VFR charts, specifically the “Fujairah CTA VFR” chart for VFR traffic navigating out of the Fujairah CTR into neighbouring airspaces and within the Fujairah control zone. GMC may use the appropriate charts as per the requirements of the pilot’s intentions.

### 2.5.1 VFR departures into uncontrolled airspace
VFR traffic shall be cleared via the most appropriate VFR route towards their destination. If necessary, the clearance may be amended by AIR prior to departure.

All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

### 2.5.2 VFR departures into controlled airspace
VFR aircraft requesting clearance to climb into approach airspace (above 5500 ft) shall only be cleared after prior coordination with approach/departure control. Otherwise, they shall be instructed to remain outside controlled airspace after leaving the control zone.

All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

!!! example
    **Pilot:** Fujairah Ground, A6-CGK, C172, request westbound departure on track Al Maktoum, altitude 7500ft.

    **Controller:** A6-CGK, Fujairah Ground, cleared westbound departure, altitude 7500ft VFR, Runway 11R, Squawk 0655.

    **Pilot:** Cleared eastbound departure, altitude 7500ft VFR, Runway 11R, Squawk 0655, A6-CGK.

    **Controller:** A6-CGK, readback correct, information A, QNH 1003, Report ready for start-up.

### 2.5.3 VFR traffic remaining in circuit
VFR traffic wishing to remain in the circuit shall be cleared only after prior coordination with AIR and Approach/Departure control. All VFR circuit traffic shall be assigned a discrete SSR code so that they may be identified on radar.

All VFR aircraft shall be instructed to conduct right-hand circuits runway 11R, and left-hand circuits runway 29L, with an altitude restriction of not above 1500ft.