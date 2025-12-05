# 4. Radio & Radar Coverage
## 4.1 Primary Surveillance Radar (PSR)
Primary Surveillance Radar (PSR) detects aircraft by transmitting pulses and receiving reflected signals, allowing identification of aircraft without the need for a transponder. PSR is essential for detecting non-transponder-equipped aircraft and provides a backup layer of surveillance in the event of secondary radar or transponder failures.

Within the **Doha FIR**, there are **three PSR stations** each providing coverage extending up to approximately **200 nautical miles**. These PSRs primarily serve terminal and low-level enroute traffic around their respective regions.

While PSR does not provide altitude or identification data, it plays a critical role in short-range surveillance and conflict alerting near major airports. Controllers must be aware of PSR limitations, especially at lower altitudes and in areas with terrain masking or clutter.

## 4.2 Monopulse Secondary Surveillance Radar (MSSR)
Monopulse Secondary Surveillance Radar (MSSR) is the primary means of enroute and terminal surveillance in the Doha FIR. It provides highly accurate position, identification, and altitude data by interrogating aircraft transponders (Modes A, C, and S).

The **Doha FIR is equipped with four MSSR stations**. These stations collectively offer comprehensive coverage across the FIR, with a surveillance range of up to **200 nautical miles** from each site, depending on terrain and aircraft altitude.

MSSR data is fully integrated into the **TopSky ATM system**, supporting automated tagging, conflict detection, and coordination functions. Controllers are responsible for monitoring the accuracy of Mode C/S data and ensuring timely correlation of squawk codes. In the event of radar contact loss or transponder malfunction, fallback procedural separation shall be applied.

## 4.3 CPDLC/ADS-C Areas
The **Doha Flight Information Region (FIR)** does not currently have operational **Controller–Pilot Data Link Communications (CPDLC)** or **Automatic Dependent Surveillance–Contract (ADS-C)** services in place. However, preparations are underway to support future implementation.

Although CPDLC is not officially active, **sector files are configured to support CPDLC-capable aircraft operating above FL295**, particularly those equipped with **Hoppie ACARS**. This configuration is intended to align with the increasing trend of datalink-equipped aircraft and ensures system readiness for eventual integration of CPDLC services.

As of now, **ADS-C services are not available** within the Doha FIR. Therefore, **all aircraft must adhere to traditional voice procedures** for position reporting, especially in non-radar or procedural airspace. There are no automatic position reporting systems implemented at this time.

In summary, while CPDLC and ADS-C services are not yet operational, the Doha FIR is technically equipped to accommodate CPDLC-equipped aircraft. Until full implementation.

## 4.4 Radio Frequency Coverage
All VHF frequencies are **managed via sector files and Track Audio configurations**, ensuring appropriate frequency allocation for each sector based on traffic volume, geographical coverage, and controller assignment. Controllers must ensure timely transfer of communication, especially near FIR boundaries or in areas with marginal radio performance.

There is **no UHF or HF radio coverage simulated on VATSIM** for the Doha FIR. All communication is conducted via **VHF only**, and fallback or relay procedures may be required if communication cannot be established in fringe coverage areas.

Controllers and pilots should be aware of potential communication delays in these zones and apply appropriate separation and coordination procedures accordingly.

## 4.5 Squawk Code Management
Squawk codes are distributed based on flight type and routing.

### 4.5.1 Operational Notes
- **Squawk codes are assigned automatically** by the system upon flight plan activation or radar identification.
- Controllers must ensure aircraft squawk the correct code and that it correlates with the radar return.
- In case of **duplicate, garbled, or missing codes**, manual reassignment from the appropriate range may be necessary.
- **Military, VFR, or special-use flights** may use codes outside the standard allocation, subject to coordination.