# 1. General Procedures
## 1.1 Enroute Airspace Structure
|  Airspace  |                           Classification                          | Vertical Limits | Transition Altitude | Transition Level |
|:----------:|:-----------------------------------------------------------------:|:---------------:|:-------------------:|:----------------:|
| Emirates FIR |                   Class A above FL150 on Airways                  |   FL150 - UNL   |      13,000 ft      |      FL 150      |
| Emirates FIR |                   Class C below FL150 on Airways                  |   SFC - FL150   |      13,000 ft      |      FL 150      |
| Emirates FIR | Class G (except within control areas, control zones, and airways) |    SFC - UNL    |      13,000 ft      |      FL 150      |

## 1.2 Air Traffic Units
|  Radio Callsign  | Logon Callsign | Abbreviation | Frequency |
|:----------------:|:--------------:|:------------:|:---------:|
| Abu Dhabi Radar             | OMAA_1_APP       | ADR C          | 124.400     |
| Abu Dhabi Radar             | OMAA_2_APP       | ADR W          | 128.100     |
| Abu Dhabi Radar             | OMAA_3_APP       | ADR N          | 135.150     |
| Abu Dhabi Radar             | OMAA_4_APP       | ADR E          | 133.550     |
| Abu Dhabi Director          | OMAA_F1_APP      | AD DIR S       | 118.000     |
| Abu Dhabi Director          | OMAA_F2_APP      | AD DIR N       | 118.425     |
| Dubai Departures (South)    | OMDB_1_DEP       | DEP 1 (South)  | 121.025     |
| Dubai Departures (North)    | OMDB_2_DEP       | DEP 2 (North)  | 124.675     |
| Dubai Arrivals              | OMDB_APP         | ARR            | 124.900     |
| Dubai Director              | OMDB_F_APP       | DB DIR         | 127.900     |
| Al Maktoum Radar            | OMDW_APP         | AMR            | 124.025     |
| Dubai South Radar           | OMDW_S_APP       | DSR            | 120.400     |
| Minhad Approach             | OMDM_APP         | MIN            | 122.500     |
| UAE Radar                   | OMAE_1_CTR       | ACC North      | 132.150     |
| UAE Radar                   | OMAE_2_CTR       | ACC Alpha      | 128.250     |
| UAE Radar                   | OMAE_3_CTR       | ACC Central    | 124.375     |
| UAE Radar                   | OMAE_4_CTR       | ACC Mike       | 132.550     |
| UAE Radar                   | OMAE_5_CTR       | ACC Bravo      | 125.925     |
| UAE Radar                   | OMAE_D_CTR       | ACC Delta      | 129.900     |
| UAE Radar                   | OMAE_E_CTR       | ACC East       | 125.375     |
| UAE Radar                   | OMAE_G_CTR       | ACC Golf       | 120.525     |
| UAE Radar                   | OMAE_H_CTR       | ACC Hotel      | 128.125     |
| UAE Radar                   | OMAE_L_CTR       | ACC Lima       | 129.500     |
| UAE Radar                   | OMAE_R_CTR       | ACC Romeo      | 124.850     |
| UAE Radar                   | OMAE_S_CTR       | ACC South      | 119.325     |
| UAE Radar                   | OMAE_W_CTR       | ACC West       | 119.300     |
| UAE Radar                   | OMAE_Y_CTR       | ACC Yankee     | 118.925     |

## 1.2 Sector Organization
To effectively manage traffic and reduce controller workload during peak periods, the Emirates FIR may be divided into up to seven sectors. Each sector is assigned responsibility for a specific traffic flow, such as departures, arrivals, or transit flights. Controllers within each sector must strictly adhere to established standard level clearance protocols and handoff procedures to maintain safe and efficient separation between aircraft. Additionally, sector controllers are responsible for continuous monitoring of their assigned traffic, timely coordination with adjacent sectors, and prompt communication of any deviations or potential conflicts. This sectorization approach ensures optimized traffic management, enhanced situational awareness, and maintains the highest standards of safety throughout the FIR.

## 1.3 Radar & Surveillance Systems
The Emirates Flight Information Region (FIR) is equipped with a total of seven MSSR (Monopulse Secondary Surveillance Radar) stations and two PSR (Primary Surveillance Radar) stations. The two primary PSR stations are strategically positioned in Dubai and Al Ain, each offering a detection range of up to 100 nautical miles (NM). Meanwhile, the seven MSSR stations, located at Al Ain, Abu Dhabi, Al Maktoum, Dubai, Ras Al Khaimah, Sharjah, and Tarif, provide enhanced surveillance capabilities with a range extending up to 256 NM, allowing radar coverage within the entire FIR.

## 1.4 CPDLC/ADS-C
The Emirates Flight Information Region (FIR) does not have operational CPDLC services in place. However, due to the increasing number of aircraft equipped with Hoppie ACARS, our sector files are configured to support CPDLC services enroute above FL295. This proactive configuration aims to accommodate the growing trend of aircraft utilizing CPDLC for communication, ensuring compatibility and readiness for future implementation.

Currently, the Emirates FIR does not have ADS-C services implemented. Consequently, aircraft are required to comply with traditional voice reporting procedures for position reporting and coordination. There are no automatic position reporting systems in place within the FIR at this time.

In summary, while CPDLC and ADS-C services are not yet operational in the Emirates FIR, the sector files are configured to support CPDLC services to align with the increasing number of equipped aircraft. However, ADS-C services are not currently available, and traditional voice communication remains the primary means for position reporting and coordination.

## 1.5 Flight Data Processing Systems
The Emirates FIR utilizes the TopSky Air Traffic Management (ATM) system to support controllers in efficiently managing and tracking flights. TopSky consolidates flight plan information, continuously updates aircraft position data, and provides advanced conflict detection and resolution tools. Controllers rely on this system to maintain situational awareness, coordinate sector handoffs, and optimize traffic flow.

It is critical that aircraft tags within TopSky are kept current at all times. This includes accurate updates of cleared flight levels (CFL), direct routing to waypoints (COPX), headings, vertical speed rates, and speed or Mach number assignments. Maintaining these updates enables TopSky to perform reliable conflict prediction and issue timely alerts, thereby ensuring safe and efficient air traffic management throughout the FIR.

## 1.6 Controller Responsibilities
Controllers operating within the Emirates FIR are responsible for ensuring the safe, orderly, and expeditious flow of air traffic within their designated sectors. This includes:

- Maintaining continuous surveillance and communication with all assigned aircraft.
- Issuing clearances, instructions, and traffic information in accordance with standard operating procedures.
- Monitoring compliance with level restrictions, route clearances, and separation minima.
- Coordinating timely handoffs with adjacent sectors to maintain seamless traffic flow.
- Managing traffic sequencing during peak periods and sector splits.
- Reporting any operational irregularities or emergencies promptly.
- Ensuring the effective use of available surveillance and communication technologies, including FDPS and CPDLC-enabled services where applicable.

## 1.7 Flight Plan Management
Flight plan management within the Emirates FIR is conducted through coordination between the ATC units and myVATSIM. Upon receipt of flight plans, controllers verify route accuracy, level assignments, and compliance with applicable airspace restrictions. Any amendments or deviations requested by pilots are evaluated for safety and efficiency before approval. Controllers must ensure that flight plans are updated promptly to reflect changes such as reroutes or altitude adjustments. Effective flight plan management is crucial for maintaining optimum traffic flow, anticipating potential conflicts, and facilitating smooth handoffs across sectors.

Aircraft entering the Emirates FIR are issued an airways clearance by the first controlling sector, valid through to their FIR exit point. This ensures the aircraft can proceed along its planned route without requiring further route amendments within the FIR.

!!! example
    **Controller**: "QTR958, UAE Radar, identified, cleared via N571 ALPOB, maintain FL350."