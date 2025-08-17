# 7. Horizontal Speed Control
## 7.1 General
Speed control is one of the most desirable ways to achieve or maintain a desired separation between aircraft. In general, it results in the smallest increase in controller workload and is particularly useful when sequencing aircraft (such as towards a TMA entry point). 

The primary variable affecting the future position, and consequently, separation between aircraft is ground speed. However, it is generally impractical to instruct aircraft to maintain a certain ground speed. Therefore, speed assignments are made with reference to indicated airspeed (IAS) or Mach number. 

## 7.2 Use of horizontal speed control
Speeds may be used to:

- Adjust separation (different speeds applied between aircraft)
- Maintain separation (the same speed applied between aircraft)
- Absorb delay by reducing speed en route (as an alternative to holding)
- Avoid or reduce vectoring:
    - As an alternative to vectoring 
    - In combination with vectoring to reduce the number and magnitude of heading changes required

## 7.3 Considerations
### 7.3.1 Applying speed control
Most jet turbine aircraft will be unable to quickly increase or decrease speed, especially at higher altitude, so due consideration must be given to the time taken for an aircraft to reach a desired speed. In certain cases, the speed control may need to be applied, one or two nautical miles prior to when the desired spacing is achieved.

Due consideration must also be given to prevailing winds aloft, as a headwind will decrease an aircraft’s ground speed and a tailwind will increase an aircraft’s ground speed. This may affect the magnitude of the speed instruction that is given to an aircraft.

!!! example
    **ATC:** "QTR843, MAINTAIN MACH DECIMAL 82"<br>
    OR<br>
    **ATC:** "AIC930, MAINTAIN SPEED 300 KNOTS"


Soft speed restrictions may be applied to two aircraft in sequence if there is no traffic ahead of the preceding aircraft and no traffic behind the succeeding aircraft using `OR GREATER` or `OR LESS` instructions.

!!! example
    **ATC:** "ABY197, MAINTAIN SPEED 290 KNOTS OR GREATER"<br>
    **Pilot 1:** "MAINTAIN SPEED 290 KNOTS OR GREATER, ABY197"<br>
    **ATC:** "UAE34E, MAINTAIN SPEED 290 KNOTS OR LESS"<br>
    **Pilot 2:** "MAINTAIN SPEED 290 KNOTS OR LESS, UAE34E"

As a reminder, wherever speed control is applied, it **must be applied to all concerned aircraft**. This is essential to avoid speed deviations which may result in a loss of the desired separation between aircraft. This is especially important wherever a sequence exists.

It is also important to note that speed instructions of greater than 290 knots for most medium category aircraft will result in a significant reduction in climb rate. 

### 7.3.2 Monitoring the result of speed control
The result of speed control should be closely monitored to gauge whether it is having the desired effect. This is done by checking the aircraft's ground speed.

!!! important
    **The difference in *ground speed* between two aircraft is the key metric which will determine whether or not the separation will stay the same, increase or decrease. <br>Ground speed is only quantity which will determine the separation between aircraft.**

It is key to **avoid over-controlling the speed** or issuing speed changes that are too drastic. Only as much speed change as required to achieve the desired separation must be issued. This ensures an efficient flow of traffic and is usually in the order of 10 to 20 knots of indicated airspeed difference.

Consideration must also be given to the difference in altitude between aircraft because the true airspeed, and therefore ground speed of the aircraft, is dependent on altitude. This is discussed in more detail in 7.3.6 and 7.3.7.

### 7.3.3 Aircraft performance characteristics
Speeds in excess of the maximum or minimum speeds shall not be assigned to aircraft. Due consideration must be given to the performance characteristics of different aircraft. This ensures that aircraft do not operate too close to high speed/low-speed buffet regions of the flight envelope, especially for aircraft at higher levels (FL350 and above).

(See Table 7-1)

!!! info
    Controllers can access detailed aircraft performance characteristics through the [EuroControl Aircraft Performance Database](https://contentzone.eurocontrol.int/aircraftperformance/default.aspx?)

|       Aircraft Cateogory       | Safe operating Mach | Maximum IAS (below FL250) |
|:------------------------------:|---------------------|:-------------------------:|
| SUPER (A380)                   |     0.82 - 0.87     |            330            |
| HEAVY (B747, B787, A350)       |     0.82 - 0.87     |            330            |
| HEAVY (B777, B767, A330, MD11) |     0.81 - 0.85     |            320            |
| MEDIUM (A320, B737)            |     0.75 - 0.79     |            300            |
<figure markdown>
  <figcaption>Table 7-1: Safe operating speed and Mach number ranges</figcaption>
</figure>

### 7.3.4 Speed control during climb or descent
Instructions for aircraft to maintain a high rate of descent and a low speed, or a high rate of climb and high speed, are generally incompatible. 

When aircraft are instructed to increase speed during a climb or decrease speed during a descent, they can be expected to maintain a short period of level or near-level flight in order to comply with the speed instruction. Conversely, when aircraft are instructed to reduce speed during a climb or increase speed during a descent, they can be expected to increase their rate of climb or descent, respectively.

### 7.3.5 Effectiveness
Speed control generally takes more time to achieve the desired separation as compared to other techniques such as vectoring, so due consideration must also be given to the volume of airspace available to achieve the desired separation. 

The longer the controller waits before applying speed control, the more drastic the speed change needs to be in order to achieve the desired separation at the handover point. Should this be the case, the controller should revert to vectoring to achieve the desired separation.

Therefore, if speed control is to be used, it requires **early intervention** so that only small changes in speed are able to achieve the required result.

### 7.3.6 Relationship between Mach number and true airspeed
When aircraft are flown with reference to Mach number, the true airspeed of an aircraft will decrease with increasing altitude. This must be considered when applying Mach number control between aircraft at different flight levels, as aircraft at higher levels will be flying slower than those at lower levels despite reporting the same Mach number.

### 7.3.7 Relationship between indicated airspeed and true airspeed
When aircraft are being flown with reference to indicated airspeed, their true airspeed will increase with increasing altitude. Therefore, aircraft at higher altitude will be flying faster than those at lower altitude, despite reporting the same indicated airspeed.

As an aircraft descends, it's true airspeed will decrease. Thus, during a descent to an altitude restriction, if a succeeding aircraft has been instructed to maintain a lower speed that its preceding aircraft, eventually the separation between these aircraft will start to increase, even if their current ground speed is the same.

Similarly, for two aircraft in succession which are climbing out from a departure airport, if they have been assigned the same indicated airspeed, it is to be expected that the preceding aircraft will usually have the higher ground speed provided they are maintaining similar rates of climb throughout.

In the case where a succeeding aircraft is maintaining a much higher rate of climb, it may result in them catching up with the preceding aircraft due to the differences in true airspeed as the second aircraft climbs to a higher level than the first. Here, if the second aircraft is instructed to reduce speed, it will result in their rate of climb further increasing which will only make the situation worse.

To resolve this, two solutions are possible. The is to restrict the climb of the succeeding aircraft. Since having an aircraft level off in the climb is usually not desirable, it may be better to instead vector the second aircraft off track to facilitate a continuous climb and allow them first preference on the higher level.

### 7.3.8 Mach/airspeed crossover
Aircraft climbing under speed control should be given a Mach number to maintain during the crossover point between indicated airspeed and Mach number to ensure that they maintain a safe operating margin and do not unexpectedly increase speed during the climb. Typically this should be done before the aircraft passes approximately FL250.

!!! example
    **ATC:** "UAE35, DESCEND FL250, ON CONVERSION MAINTAIN SPEED 300 KNOTS"

Conversely, descending aircraft should be given an indicated airspeed to maintain during the crossover, so their speed does not continue to increase as the aircraft descends. Typically this should be done before the aircraft passes approximately FL300.

!!! example
    **ATC:** "UAE4KC, CLIMB FL300, ON CONVERSION MAINTAIN MACH DECIMAL 84"

Ensure that the speeds and Mach numbers assigned lie within the safe operating range for each aircraft as defined in 7.3.3. Typically most heavy and medium category aircraft can maintain speeds of up to 320 knots safely.

Expect descent rates to reduce when aircraft transitions from Mach number to speed, and climb rates to temporarily increase when an aircraft transitions from speed to Mach number.

## 7.4 Rules of thumb
- 0.01 Mach = 6 knots
- Speed difference of 6 knots gives 1 NM of separation change every 10 minutes
- Speed difference of 30 knots gives 1 NM of separation change every 2 minutes
- Speed difference of 60 knots gives 1 NM of separation change every minute
- True airspeed (TAS) = Indicated airspeed (IAS) + 6 knots per 1000 ft above MSL