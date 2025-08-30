# 17. Contigency & Emergency Procedures
## 17.1 Communication Failure
In the event of a **pilot communication failure**:

- **Attempt contact on all available frequencies**, including guard (121.5 MHz), any previous frequency, or through CPDLC if available.
- Expect the aircraft to **squawk 7600**.
- Monitor the aircraft’s route for adherence to expected flight plan behavior. ICAO DOC 4444 prescribes that aircraft should continue under the last clearance received and acknowledged.
- If under radar control, continue to provide separation based on observed radar returns and expected routing.
- **Coordinate with adjacent FIRs** if the aircraft is approaching a boundary.

In the event of a **controller voice communication failure** (e.g., station audio failure):

- Attempt to re-establish service via backup frequencies, text, or via coordination with adjacent sectors to relay instructions.

## 17.2 Radar Failure
A partial or full **radar outage** may require a transition from radar to **procedural control**:

- Notify all aircraft under control of the failure and request position reports at designated waypoints.
- Apply **procedural separation minima** (e.g., 10 or 15 minutes longitudinal separation depending on direction and speed).
- Temporarily suspend new clearances requiring radar vectors, altitude changes, or close separation.
- Coordinate with adjacent FIRs for transfer via procedural means if applicable.
- Once radar is restored, verify all targets against position reports before resuming standard surveillance-based separation.

## 17.3 CPDLC/Surveillance Failure
Although CPDLC is not yet operational within the Doha, Emirates and Muscat FIRs, sector files are CPDLC-ready. If using Hoppie or simulated CPDLC services and a failure occurs:

- **Revert to standard voice communication** procedures.
- Advise pilots to disregard any pending uplinks and resume voice contact.
- Monitor for any anomalies in CPDLC message acknowledgements or failures in ADS-C contracts if simulated.

In the event of a **surveillance failure** (loss of radar data):

- Transition to procedural separation based on position reports.
- Request squawk code re-entry or set 2000 as needed.
- Treat affected aircraft as non-radar for the duration of the outage.

## 17.4 Aircraft Emergency Handling
When a pilot declares an emergency (e.g., MAYDAY or PAN PAN):

- Acknowledge immediately and provide **priority handling**.
- Determine the **nature of the emergency**, intentions, and current capabilities.
- Offer vectors or descent/climb clearance as needed to ensure terrain clearance and safety.
- **Coordinate with adjacent sectors** and affected airports for possible diversion.

Common scenarios:
- **Engine failure**: Provide direct routing and assistance with altitude.
- **Medical emergency**: Expedite descent and coordinate for nearest suitable airport.
- **Fuel emergency**: Provide direct route and prioritize approach.

!!! info
    As per VATSIM Code of Conduct Section B6, controllers may deny or terminate emergency situations at their discretion. If an emergency is not permitted or must be discontinued, the pilot may be instructed to disconnect from the network to maintain orderly traffic flow and network integrity.

## 17.5 Weather Diversions
In the case of **significant weather** (e.g., CB activity, sandstorms, or low visibility at destination):

- Allow deviation from cleared routing where safe, preferably with prior coordination.
- Assign alternate routing or holding if airspace congestion requires sequencing.
- If a diversion is declared:
  - **Coordinate immediately** with the new destination airport and update flight data.
  - Inform adjacent FIRs as necessary.
  - Amend flight plan routing as appropriate.

Controllers shall actively monitor METARs and available weather information for key aerodromes and regions within the FIR, providing timely advisories to pilots when adverse conditions are observed or forecasted. The TopSky ATM system offers a basic weather radar overlay, which highlights convective activity and weather cells within the FIR to support situational awareness.

## 17.6 Lost Aircraft or Aircraft Deviation
If an aircraft deviates from its cleared route, altitude, or squawk code:

- Attempt to re-establish communication immediately.
- If no response is received, treat the aircraft as a possible **lost comms** case.
- Monitor for course corrections or abnormal behavior that could indicate equipment malfunction or navigation error.
- Notify adjacent FIRs and consider broadcasting general advisories on guard frequency if required.

If the aircraft becomes **completely unidentifiable**, last known position and heading must be noted, and procedural separation must be increased for any conflicting traffic.