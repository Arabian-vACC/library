# 13. Aerodrome Techniques
## 13.1 Taxi clearances
### 13.1.1 "Red-carpet rule"
When issuing taxi instructions, controllers shall apply the "red-carpet rule". 

The red carpet rule essentially means that when a taxi clearance is issued to one aircraft, the second aircraft shall not be given a clearance that intersects or joins the projected path of the first.

The reccommended practice is to issue taxi clearances to hold short of any intersection, and issue further taxi once the aircraft approaches the intersection, once the traffic situation becomes more apparent.

This technique reduces potential conflicts, as well as allows for efficient sequencing of departing traffic towards a runway holding point.

## 13.2 Departure separation
### 13.2.1 General
Departure separation often has a major effect on the handling capacity of an aerodrome. Effective use of departure separation and departure sequence planning maximises efficiency while still complying with minimum time-based separation requirements.

### 13.2.2 Applying separation
It is often impractical to try to time the separation based on the rotation of the aircraft, as the controller must know exactly when each aircraft will rotate and requires them to keep a close eye on the take-off roll of the aircraft which is often impractical, especially during times of high traffic workload.

In order to minimise workload while still maximising efficiency, the separation must be applied to the start of the take-off roll, as opposed to the rotation point. This is much easier to do and allows the controller to focus elsewhere in between take-off clearances. The integrated runway departure timer available in GroundRadarPlugin reliese on this concept and commences elapsed timing based on the start of the takeoff roll.

This allows the take-off clearance to be given such that the second aircraft commences their takeoff roll exactly after the specified time interval after the first with no time loss, which in turn maximises departure throughput.

The time taken for an pilot to read back the instruction and commence a take-off roll is usually around 20 seconds, so the take-off clearance in this example must be delivered 1 minute and 40 seconds after the first aircraft has commenced its take-off roll to ensure efficient use of departure separation.

## 13.3 Departure sequencing
### 13.3.1 General
Effective planning of the departure sequence ensures that the average delay experienced on the aerodrome is minimised, maximising aircraft throughput. If done correctly, this ensures that in most instances the separation required between successive take-offs is minimised.

### 13.3.2 Planning the departure sequence
In general, ensuring that aircraft on the same departure are always paired with an aircraft on a departure in a different direction will minimise average delay, regardless of wake turbulence category. Where there are different weight categories of aircraft, aircraft should in general be paired with an aircraft of the same category.

Whenever there is a choice between sending two aircraft on the same SID, versus sending two aircraft on different SIDs, the latter option shall always be used regardless of wake turbulence category. This approach will always minimise the overall departure delay.

Planning of the departure sequence should start at the taxi phase, with controllers aiming to alternate departure SIDs wherever possible without causing unreasonable delay to traffic. 