# 1. General Procedures
## 1.1 Enroute Airspace Structure
|  Airspace  |                           Classification                          | Vertical Limits | Transition Altitude | Transition Level |
|:----------:|:-----------------------------------------------------------------:|:---------------:|:-------------------:|:----------------:|
| Muscat FIR |                   Class A above FL150 on Airways                  |   FL150 - UNL   |      13,000 ft      |      FL 150      |
| Muscat FIR |                   Class C below FL150 on Airways                  |   SFC - FL150   |      13,000 ft      |      FL 150      |
| Muscat FIR | Class G (except within control areas, control zones, and airways) |    SFC - UNL    |      13,000 ft      |      FL 150      |

!!! info
    **Radar-Derived Flight Information Service (FIS) in Class G Airspace**

    Upon request, and where feasible within the coverage area of available radar facilities, Muscat ACC shall provide radar-derived Flight Information Service (FIS) to both IFR and VFR aircraft operating in Class G airspace. This service is provided as far as practicable, and within the limitations of radar coverage and controller workload.

## 1.2 Air Traffic Units
|  Radio Callsign  | Logon Callsign | Abbreviation | Frequency |
|:----------------:|:--------------:|:------------:|:---------:|
|   Khasab Radar   |    OOKB_APP    |      KR      |  125.000  |
|  Muscat Approach |    OOMS_APP    |      MSA     |  121.200  |
| Salalah Approach |    OOSA_APP    |      SA      |  119.100  |
|  Muscat Control  |   OOMM_1_CTR   |      MN      |  128.150  |
|  Muscat Control  |   OOMM_2_CTR   |      MA      |  135.600  |
|  Muscat Control  |   OOMM_3_CTR   |      MB      |  126.550  |
|  Muscat Control  |   OOMM_4_CTR   |      MM      |  118.325  |
|  Muscat Control  |   OOMM_5_CTR   |      MS      |  123.950  |
|  Muscat Control  |   OOMM_6_CTR   |      MC      |  124.700  |
|  Muscat Control  |   OOMM_7_CTR   |      MW      |  119.800  |

## 1.2 Sector Organization
To effectively manage traffic and reduce controller workload during peak periods, the Muscat FIR may be divided into up to seven sectors. Each sector is assigned responsibility for a specific traffic flow, such as departures, arrivals, or transit flights. Controllers within each sector must strictly adhere to established standard level clearance protocols and handoff procedures to maintain safe and efficient separation between aircraft. Additionally, sector controllers are responsible for continuous monitoring of their assigned traffic, timely coordination with adjacent sectors, and prompt communication of any deviations or potential conflicts. This sectorization approach ensures optimized traffic management, enhanced situational awareness, and maintains the highest standards of safety throughout the FIR.

## 1.3 Use of Radar & Surveillance Systems
The Muscat Flight Information Region (FIR) is equipped with a total of eight MSSR (Monopulse Secondary Surveillance Radar) stations and two PSR (Primary Surveillance Radar) stations. The two primary PSR stations are strategically positioned in Muscat and Salalah, each offering a detection range of up to 100 nautical miles (NM). Meanwhile, the eight MSSR stations, located at Adam, Al-Hadd, Dukhum, Muscat, Qaran Hairiti, Salalah, and Widam, provide enhanced surveillance capabilities with a range extending up to 256 NM.

## 1.4 Use of CPDLC/ADS-C
The Muscat Flight Information Region (FIR) does not have operational CPDLC services in place. However, due to the increasing number of aircraft equipped with Hoppie ACARS, our sector files are configured to support CPDLC services enroute above FL295. This proactive configuration aims to accommodate the growing trend of aircraft utilizing CPDLC for communication, ensuring compatibility and readiness for future implementation.

Currently, the Muscat FIR does not have ADS-C services implemented. Consequently, aircraft are required to comply with traditional voice reporting procedures for position reporting and coordination. There are no automatic position reporting systems in place within the FIR at this time.

In summary, while CPDLC and ADS-C services are not yet operational in the Muscat FIR, the sector files are configured to support CPDLC services to align with the increasing number of equipped aircraft. However, ADS-C services are not currently available, and traditional voice communication remains the primary means for position reporting and coordination.

## 1.5 Use of Flight Data Processing Systems
The Muscat FIR utilizes the TopSky Air Traffic Management (ATM) system to support controllers in efficiently managing and tracking flights. TopSky consolidates flight plan information, continuously updates aircraft position data, and provides advanced conflict detection and resolution tools. Controllers rely on this system to maintain situational awareness, coordinate sector handoffs, and optimize traffic flow.

It is critical that aircraft tags within TopSky are kept current at all times. This includes accurate updates of cleared flight levels (CFL), direct routing to waypoints (COPX), headings, vertical speed rates, and speed or Mach number assignments. Maintaining these updates enables TopSky to perform reliable conflict prediction and issue timely alerts, thereby ensuring safe and efficient air traffic management throughout the FIR.

## 1.6 Controller Responsibilities
Controllers operating within the Muscat FIR are responsible for ensuring the safe, orderly, and expeditious flow of air traffic within their designated sectors. This includes:

- Maintaining continuous surveillance and communication with all assigned aircraft.
- Issuing clearances, instructions, and traffic information in accordance with standard operating procedures.
- Monitoring compliance with level restrictions, route clearances, and separation minima.
- Coordinating timely handoffs with adjacent sectors to maintain seamless traffic flow.
- Managing traffic sequencing during peak periods and sector splits.
- Reporting any operational irregularities or emergencies promptly.
- Ensuring the effective use of available surveillance and communication technologies, including FDPS and CPDLC-enabled services where applicable.

## 1.7 Flight Plan Management
Flight plan management within the Muscat FIR is conducted through coordination between the ATC units and myVATSIM. Upon receipt of flight plans, controllers verify route accuracy, level assignments, and compliance with applicable airspace restrictions. Any amendments or deviations requested by pilots are evaluated for safety and efficiency before approval. Controllers must ensure that flight plans are updated promptly to reflect changes such as reroutes or altitude adjustments. Effective flight plan management is crucial for maintaining optimum traffic flow, anticipating potential conflicts, and facilitating smooth handoffs across sectors.

Aircraft entering the Muscat FIR are issued an airways clearance by the first controlling sector, valid through to their FIR exit point. This ensures the aircraft can proceed along its planned route without requiring further route amendments within the FIR.

!!! example
    **Controller**: "QTR958, Muscat Control, radar contact, cleared N318 - TOLDA - L555 TOTOX, maintain FL350."