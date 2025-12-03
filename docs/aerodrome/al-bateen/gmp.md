# 2. Departure Clearance Procedures
## 2.1 General provisions
Ground Movement Controller (GMC) is responsible for validating routes and shall provide IFR clearance to departing aircraft. The controller shall assign the correct departure procedure to the aircraft based on the first point that is filed on the flight plan.

Where the flight plan contains an invalid route, level or departure procedure, GMC must ensure that the error is corrected before the aircraft is given its clearance.

## 2.2 Departure clearance
### 2.2.1 General
GMP is responsible for issuing clearances for departing aircraft. Pilots may be expected to report the following information on first contact:

-   Callsign
-   Aircraft type
-   Apron aircraft is parked on
-   Destination and requested flight level
-   Souls on board

To facilitate the most expeditious movement of ready aircraft, pilots not ready to pushback and start when instructed to do so by ATC shall expect to wait for further pushback instructions.

### 2.2.2 Information contained in a departure clearance
An IFR clearance shall be in the following format:

-   Callsign
-   Destination
-   Departure procedure
-   Initially cleared altitude
-   Assigned SSR code

Departing aircraft shall be instructed to report ready for pushback.

!!! example
    **Pilot:** Al Bateen Ground, IFA6487, Bombardier Global Express, apron C, Information A, requesting IFR clearance to Verona, fully ready for push and start.

    **Controller:** IFA6487, Al Bateen Ground, cleared to Verona via DAXIB1Q, maintain altitude 3000ft, Squawk 3432.

    **Pilot:** Cleared to Verona via DAXIB1Q, maintain altitude 3000ft, Squawk 3432. IFA6487.

    **Controller:** IFA6487, Correct, report ready for Start-up.

!!! Info
    GMC must obtain a full readback of the clearance. If the pilot does not report the current ATIS letter on first contact, GMC shall pass the current ATIS letter and QNH.

### 2.2.3 Aircraft requiring a reroute
Aircraft requiring a reroute shall be given a voice clearance. This shall be communicated on frequency.

!!! Info
    Controllers shall use best judgement and task prioritisation to notify pilots of invalid flightplans.

### 2.2.3 Voice clearance
Aircraft requesting clearance via voice should be given a voice clearance as per the format in 2.2.2.

## 2.3 Departure Procedures
### 2.3.1 RNAV Standard instrument departures
Al Bateen primarily uses RNAV standard instrument departures (SIDs) and is the preferred departure type for IFR aircraft. Departing aircraft shall be assigned an appropriate RNAV departure according to the first fix in the flight plan and runways in use.

The Table below shows all the RNAV SIDs and their initial climb.

<figure markdown>
|  SID 13  |  Initial Climb  |  SID 31  |  Initial Climb  |
|----------|-----------------|----------|-----------------|
| ATUDO1R  |     3000ft      | ATUDO1Q  |     3000ft      |
| BOSEV1R  |     3000ft      | BOSEV1Q  |     3000ft      |
| DAXIB2R  |     3000ft      | DAXIB1Q  |     3000ft      |
| KANIP1R  |     3000ft      | KANIP1Q  |     3000ft      |
| LORID2R  |     3000ft      | LORID1Q  |     3000ft      |
| MEKRI1R  |     3000ft      | MEKRI1Q  |     3000ft      |
| ORNEL1R  |     3000ft      | ORNEL1Q  |     3000ft      |
| TULON1R  |     3000ft      | TULON1Q  |     3000ft      |

  <figcaption>Table 2-1: RNAV SIDs</figcaption>
</figure>

### 2.3.2 Radar departures
The radar departure procedure shall be used when aircraft are unable to accept an RNAV departure, such as one with outdated nav data. Whereas RNAV departures follow a prescribed track until leaving the Abu Dhabi Departures airspace, radar departures are given radar vectors to the first fix.

In the take-off clearance. Air Control (AIR) may assign a heading based on the departure runway to facilitate independent departure operations.

A radar departure clearance shall contain the following information:

-   Callsign
-   Destination
-   Radar departure
-   Runway
-   Initial climb
-   Assigned SSR code

!!! Example
    **Controller:** IFA6487, Al Bateen Ground, cleared to Verona, runway 31, expect radar vectors, maintain altitude 3000ft, squawk 3421.

!!! Note
    Aircraft on radar departure shall have the text RDR inserted to the scratchpad section of their entry on the departure list.

### 2.4 Rerouting aircraft and standard routes
An aircraft shall be issued a reroute by GMc if the pilot’s route doesn’t comply with the standard routes laid out in Table 2-2.

Several routing restrictions exist within UAE airspace and must be complied with when issuing a departure clearance.

If an aircraft requires a reroute, they shall be informed of such as soon as they have connected to the network by private message or on frequency. The use of “.rte" and “.rtef" aliases are encouraged.

!!! Note
    The Arabian vACC Operations Department maintains an up-to-date route database on SimBrief. These routes can be accessed by selecting the "User Submitted Routes" option, highlighted in purple, when planning a flight.

<figure markdown>
| Destination                                                    | Level Restriction         | Routing                                         | Remarks                                           |
|---------------------------------------------------------------|--------------------------|-------------------------------------------------|---------------------------------------------------|
| OIKB and beyond                                               | -                        | TULON M318 GABKO                                | -                                                 |
| Muscat FIR and beyond                                         | -                        | KANIP N318 LABRI                                | Does not apply to traffic landing at OOMS, OOMN and OOSH |
| OOMS, OOMN and OOSH                                           | -                        | ORNEL N685 RETAS                                | -                                                 |
| Sanaa FIR and Jeddah FIR                                      | -                        | ORNEL T560 ELUDA G783 TANSU                     | -                                                 |
| Sanaa FIR and Jeddah FIR                                      | -                        | ORNEL T560 ELUDA G783 RIGIL M628 PEKEM          | -                                                 |
| Sanaa FIR and Jeddah FIR                                      | -                        | ATUDO M318 KATIT                                | -                                                 |
| Sanaa FIR and Jeddah FIR                                      | -                        | ATUDO M318 GOLGU M550 RIBOT                     | -                                                 |
| Doha FIR and Jeddah FIR and beyond overflying Riyadh VOR (KIA)| -                        | MEKRI P899 TOVOX                                | Conditions apply via Bahrain's standard routing    |
| Bahrain FIR Northbound and Westbound to Tehran FIR, Kuwait FIR and Baghdad FIR | - | DAXIB Q563 UKUVO G462 TUMAK                     | -                                                 |
| Jeddah FIR via COPPI and Bopan VOR (BPN) and destinations OERK and OEJN | - | BOSEV N563 ALPOB                                | -                                                 |
| OBBI, OBBS, OBKH, OEDF and OEDR                              | -                        | BOSEV N563 IMGUX P699 ORMID                     | -                                                 |
| OIBK                                                          | -                        | DAXIB Q563 UKUVO DCT KIVUS DCT LUDAM DCT ORSAR  |                                                   |
| OISS, OIII and beyond                                         | -                        | TULON M318 TOVIV P574 KUMUN                     | -                                                 |
| OMAL                                                          | 9,000ft or below        | KANIP                                           | Use appropriate KANIP SID                         |
| OMDB, OMDW and OMSJ                                           | 10,000ft or below        | LORID                                           | Use appropriate LORID SID; Subject to delays during high IFR activity |
| OMFJ                                                          | -                        | KANIP DCT VAMIM DCT PEDOG DCT MURGU Q308 RUDAT DCT IMVAT | -                                         |
| OMFJ                                                          | -                        | KANIP DCT VAMIM DCT PEDOG DCT MURGU Q308 RUDAT DCT FJV   | -                                         |
| OMRK                                                          | -                        | KANIP DCT VAMIM DCT PEDOG DCT MURGU Q308 ORKOB DCT FJV DCT LAGLI DCT RAV | -      |

  <figcaption>Table 2-2: Standard Routes</figcaption>
</figure>

!!! Note
    Any other flight plans departing OMAD into other airports within UAE airspace can expect radar vectors subject to ATC approval and possible delays.

## 2.5 Requested cruising level
### 2.5.1 Level restrictions
Aircraft routes out of the aerodrome must comply with all routing and level restrictions as described in section 3.1 of Arabian MATS P1 under foundations and Table 2-5. This is based on direction and type of flight.

Should an aircraft file an invalid cruise level, GMC shall advise the aircraft of this when delivering the clearance. In all cases, the next lowest valid cruise level shall be assigned, and the aircraft advised.

## 2.6 Runway change procedure
AIR shall provide ample notice to GMC before changing runway configuration. The last departure using the old configuration shall be coordinated between AIR, and GMC and approach/departure.

Aircraft that have already been cleared to depart using the old configuration shall be re-cleared if they have not already requested pushback.

## 2.7 VFR aircraft 
VFR flight activity should be planned in accordance to published VFR charts, specifically the **"Abu Dhabi - CTA VFR and CTA VFR Route information for navigating within the Abu Dhabi CTA and for flying out of the CTA into neighboring airspaces.**

GMC may use the appropriate charts as per the requirements of the pilot's intentions.

!!! Warning
    At any time, AIR control and/or Approach/Departure control may impose partial or full restrictions to VFR operations out of the aerodrome during periods of increased IFR activity or due to restrictions and limitations to aircraft type.

    It is imperative that GMC is in continuous coordination with AIR control and Abu Dhabi Approach control for departing VFR traffic.

### 2.7.1 VFR departures into uncontrolled airspace
VFR traffic shall be cleared via the most appropriate VFR route towards their destination. If necessary, the clearance may be amended by AIR prior to departure.

!!! Example
    **Pilot:** Al Bateen Ground, A6-MXC, Apron B, request clearance to Dubai, information C.

    **Controller:** A6-MXC, cleared to exit the Abu Dhabi CTR, via Eastern Mangroves (EMN), AD1. Hanjurah West (HAW), not above altitude 1500ft VFR, squawk 0672.

    **Pilot:** Cleared to exit the Abu Dhabi CTR, via Eastern Mangroves (EMN), AD1. Hanjurah West (HAW), not above altitude 1500ft VFR, squawk 0672, A6-MXC

    **Controller:** A6-MXC, Readback correct, information C report ready for start-up.

!!! Note
    All VFR departures shall be assigned a discrete SSR code so that they may be identified on radar.

### 2.7.1 VFR departures into controlled airspace

!!! Note 
    VFR aircraft intending to climb into Abu Dhabi CTA (above 1500 ft) shall only be cleared after prior coordination with Approach/Departure control. Otherwise, they shall be instructed to remain outside controlled airspace after leaving the control zone.

    Unless an altitude higher than the Abu Dhabi CTR has been requested by the pilot.

VFR traffic shall be cleared via the most appropriate VFR route towards their destination. If necessary, the clearance may be amended by AIR prior to departure.

!!! Example
    **Pilot:** Al Bateen Ground, A6-MXC, Apron B, request clearance to Dubai, information C.

    **Controller:** A6-MXC, cleared to exit the Abu Dhabi CTR, via Eastern Mangroves (EMN), AD1. Hanjurah West (HAW), not above altitude 1500ft VFR, squawk 0672.

    **Pilot:** Cleared to exit the Abu Dhabi CTR, via Eastern Mangroves (EMN), AD1. Hanjurah West (HAW), not above altitude 1500ft VFR, squawk 0672, A6-MXC

    **Controller:** A6-MXC, Readback correct, information C report ready for start-up.

### 2.7.2 VFR traffic remaining in circuit

!!! Note
    VFR traffic wishing to remain in the circuit shall be cleared only after prior coordination with AIR.

- **Left-hand** circuits shall be carried out by VFR traffic departing on runway 31
- **Right-hand** circuits shall be carried out by VFR traffic departing on runway 13
- Circuits shall be conducted at an altitude of ****1500ft**
- Only one aircraft is permitted in the circuit

!!! Note
    All VFR circuit traffic shall be assigned a discrete SSR code so that they may be identified on radar.

!!! Note
    VFR circuits shall not be permitted at the aerodrome during times of increased IFR departure or arrival activity.

!!! Example
    **Pilot:** Al Bateen Ground, A6-GGM type C172, Apron C, Information M, requesting clearance for circuits.

    **Controller:** A6-GGM, Al Bateen Ground, cleared left-hand circuit, runway 31, not above altitude 1500ft VFR, squawk 0655.

    **Pilot:** Cleared left-hand circuits runway 31, not above 1500ft VFR, squawk 0655, A6-GGM.

    **Controller:** A6-GGM, Readback correct, Information M, report ready for start-up.

