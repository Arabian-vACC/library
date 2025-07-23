# 4. Radio & Radar Coverage
## 4.1 Primary Surveillance Radar (PSR)
Primary Surveillance Radar (PSR) detects aircraft by transmitting pulses and receiving reflected signals, allowing identification of aircraft without the need for a transponder. PSR is essential for detecting non-transponder-equipped aircraft and provides a backup layer of surveillance in the event of secondary radar or transponder failures.

Within the **Muscat FIR**, there are **two PSR stations** located at **Muscat** and **Salalah**, each providing coverage extending up to approximately **100 nautical miles**. These PSRs primarily serve terminal and low-level enroute traffic around their respective regions.

While PSR does not provide altitude or identification data, it plays a critical role in short-range surveillance and conflict alerting near major airports. Controllers must be aware of PSR limitations, especially at lower altitudes and in areas with terrain masking or clutter.

## 4.2 Monopulse Secondary Surveillance Radar (MSSR)
Monopulse Secondary Surveillance Radar (MSSR) is the primary means of enroute and terminal surveillance in the Muscat FIR. It provides highly accurate position, identification, and altitude data by interrogating aircraft transponders (Modes A, C, and S).

The **Muscat FIR is equipped with eight MSSR stations**, located at **Adam, Al-Hadd, Duqm, Muscat, Qaran Hairiti, Salalah, Widam,** and **Thumrait**. These stations collectively offer comprehensive coverage across the FIR, with a surveillance range of up to **256 nautical miles** from each site, depending on terrain and aircraft altitude.

MSSR data is fully integrated into the **TopSky ATM system**, supporting automated tagging, conflict detection, and coordination functions. Controllers are responsible for monitoring the accuracy of Mode C/S data and ensuring timely correlation of squawk codes. In the event of radar contact loss or transponder malfunction, fallback procedural separation shall be applied.

## 4.3 CPDLC/ADS-C Areas
The **Muscat Flight Information Region (FIR)** does not currently have operational **Controller–Pilot Data Link Communications (CPDLC)** or **Automatic Dependent Surveillance–Contract (ADS-C)** services in place. However, preparations are underway to support future implementation.

Although CPDLC is not officially active, **sector files are configured to support CPDLC-capable aircraft operating above FL295**, particularly those equipped with **Hoppie ACARS**. This configuration is intended to align with the increasing trend of datalink-equipped aircraft and ensures system readiness for eventual integration of CPDLC services.

As of now, **ADS-C services are not available** within the Muscat FIR. Therefore, **all aircraft must adhere to traditional voice procedures** for position reporting, especially in non-radar or procedural airspace. There are no automatic position reporting systems implemented at this time.

In summary, while CPDLC and ADS-C services are not yet operational, the Muscat FIR is technically equipped to accommodate CPDLC-equipped aircraft. Until full implementation, **voice communication remains the primary and mandatory method for coordination and reporting**.

## 4.4 Radio Frequency Coverage
**VHF radio coverage** within the Muscat FIR is generally reliable at cruising levels across the majority of controlled airspace. However, **coverage can degrade or become intermittent** the farther aircraft operate from the **coastline of Oman**, particularly in oceanic or remote desert regions.

All VHF frequencies are **managed via sector files and Track Audio configurations**, ensuring appropriate frequency allocation for each sector based on traffic volume, geographical coverage, and controller assignment. Controllers must ensure timely transfer of communication, especially near FIR boundaries or in areas with marginal radio performance.

There is **no UHF or HF radio coverage simulated on VATSIM** for the Muscat FIR. All communication is conducted via **VHF only**, and fallback or relay procedures may be required if communication cannot be established in fringe coverage areas.

Controllers and pilots should be aware of potential communication delays in these zones and apply appropriate separation and coordination procedures accordingly.

## 4.5 Areas with No/Degraded Coverage
Certain portions of the Muscat FIR, particularly in **remote desert regions and areas beyond coastal radar/radio coverage**, experience **limited or degraded surveillance and communication capability**.

In these areas:

- **Procedural separation** standards must be applied.
- **Voice position reporting** is required at designated waypoints.
- **CPDLC and ADS-C** services are not currently operational and cannot be relied upon.

Controllers should proactively coordinate with adjacent FIRs and maintain increased situational awareness when managing traffic in or near these degraded areas.

## 4.6 Squawk Code Management
Squawk codes are distributed based on flight type and routing as follows:

- **Transit Through Muscat FIR**  
  `3501–3577`
  *Applicable for overflights transiting the FIR.*

- **Arrivals into Muscat FIR**  
  `6500–6577`
  *Assigned to inbound flights with destinations within Oman.*

- **International Departures from Muscat FIR – Primary Range**  
  `4001–4077`
  *Assigned to IFR departures from Oman destined outside the FIR.*  

- **International Departures from Muscat FIR – Secondary Range**  
  `4701–4777`  
  *Used as a secondary block for international IFR flights.*   

- **Domestic Flights within Muscat FIR – Primary Range**  
  `1201–1277`  
  *Assigned to domestic flights entirely within Oman.*  

- **Domestic Flights within Muscat FIR – Secondary Range**  
  `4601–4677`  
  *Used as a secondary block for domestic IFR flights.*  

### 4.4.1 Operational Notes
- **Squawk codes are assigned automatically** by the system upon flight plan activation or radar identification.
- Controllers must ensure aircraft squawk the correct code and that it correlates with the radar return.
- **Aircraft entering procedural airspace or outside radar coverage** may be instructed to squawk **2000** unless otherwise coordinated.
- In case of **duplicate, garbled, or missing codes**, manual reassignment from the appropriate range may be necessary.
- **Military, VFR, or special-use flights** may use codes outside the standard allocation, subject to coordination.