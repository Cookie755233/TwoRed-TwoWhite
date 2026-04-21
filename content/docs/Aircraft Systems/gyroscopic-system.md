## Gyroscopic Principles
### Rigidity in Space
**DEFINITION:**\
**The gyro spun rapidly remains in the fixed position in which it was originally spinning**
### Precession
**DEFINITION:**\
**Precession is the tilting or turning of a gyro in response to pressure. The reaction to this force occurs in the direction of rotation, approximately 90° ahead of the point where the force was applied.**

## Sources of Power
![Typical Vacuum system](/images/vacuumsystem.png "Typical Vacuum system")

The three primary gyroscopic instruments are powered by two different sources to ensure redundancy in the event of a system failure:

### Vacuum (Suction) System
- Instruments: 
	- Attitude Indicator 
	- Heading Indicator.
- Mechanism: An **engine-driven pump** creates a vacuum that *pulls filtered air across the gyros, spinning them at high speeds.*
- Monitoring: A suction gauge, sometimes referred to as a pressure gauge, and a regulator valve allow the pilot and mechanics to monitor and maintain the correct vacuum levels.

### Electrical System
- Instrument: Turn Coordinator.
- Mechanism: Powered by a small **electric motor**.
- Purpose: This instrument is intentionally powered separately so that if the engine-driven vacuum pump fails, the pilot still has at least one functional gyroscopic instrument to maintain aircraft control.

## Turn Coordinator/ Turn-and-slip Indicator
![Turn indicators rely on controlled precession for their operation](/images/tunrcoord.png "Turn indicators rely on controlled precession for their operation")

The gyro in the turn and slip indicator is mounted horizontally, and on the turn coordinator, that mounting is *canted* slightly at about 30 degrees; therefore, its gyro can sense *both rate of roll and rate of turn.*

A standard-rate turn is defined as a turn rate of *3° per second* (2 min/circle)

> [!CAUTION]
> The turn coordinator indicates only the rate and direction of turn; it does **NOT** display a specific angle of bank. It tells us only the rate of turn in degrees per second, and that's *affected by the aircraft's speed.*\
> If you're turning slower, at a slower airspeed, the radius of the turn is smaller and it's more degrees per second. \
> If the aircraft is traveling faster, it's a larger radius and it's fewer degrees per second. 

### Inclinometer
**DEFINITION:**\
**The inclinometer is used to depict aircraft YAW, which is the side-to-side movement of the aircraft’s nose**

![Inclinometer](/images/inclinometer.png "Inclinometer")

The inclinometer indicates that the nose of the aircraft is **inside or outside of the aircraft's flight path.**
- Coordinated Turn
	- The longitudinal axis of the aircraft is aligned with its flight path
	- The ball is centered.
- Slipping Turn
	- Aircraft is outside of the aircraft's flight path; 
	- The ball is going inside of the turn.
- Skidding Turn
	- Aircraft is inside of the aicraft’s flight path;
	- The ball is going outside of the turn.


## Attitude Indicator
**DEFINITION:**\
**The attitude indicator uses an artificial horizon and miniature airplane to depict the position of your airplane in relation to the true horizon.** 

![Attitude Indicator](/images/attitudeindicatorblowup.png "Attitude Indicator")

The attitude indicator displays a picture of the attitude of the aircraft with the help of *three* gimbals around a fast-spinning gyro. 

![Attitude representation by the attitude indicator corresponds to the relation of the aircraft to the real horizon.](/images/attitudeindicator.png "Attitude representation by the attitude indicator corresponds to the relation of the aircraft to the real horizon.")

> [!NOTE]
> Attitude Indicator is the only instrument in the pilot's cockpit that gives the pilot two pieces of information—*pitch* and *bank*.

> [!CAUTION]
> Attitude Indicator does NOT indicate if the aircraft is climbing or descending; it is the Vertical Speed Indicator (VSI) does.


### Mirco-Electronic Mechanical System (MEMS) 
![MEMS Gyro](/images/mems.png "MEMS Gyro")

A MEMS (Micro-Electro-Mechanical Systems) Gyroscope is a compact, highly reliable device used to measure angular velocity or maintain orientation in a wide range of applications. Unlike traditional gyroscopes, MEMS technology combines mechanical and electrical components at a microscopic scale, resulting in a smaller, more cost-effective solution without compromising on performance.


## Heading Indicator (Directional Gyro)
**DEFINITION:**\
**The heading indicator senses airplane movement and displays heading based on a 360° azimuth, with the final zero omitted. **

![Heading Indicator](/images/headingindicator.png "Heading Indicator")

 The air-driven heading indicator is **NOT** automatically tuned to *magnetic north*. For the heading indicator to display the correct heading, you must align it with the magnetic compass before flight. 
 
 However, *precession can cause the selected heading to drift* from the set value. For this reason, you must regularly, at approximately 15-minutes intervals, align the indicator with the magnetic compass.

### Flux Gate Compass System
![The Flux Gate Compass System](/images/fluxgatecompasssys.png "The Flux Gate Compass System")

The fluxgate magnetometer senses the earth’s flux lines and updating the heading indicator, which will *automatically* align the compass to the magnetic north.

> [!note]
> A coil wound around the iron spacer in the center of the frame has 400 Hz alternating current (AC) flowing through it. A coil wound around the iron spacer in the center of the frame has 400 Hz alternating current (AC) flowing through it.\
> Read more at [fluxgate magnetometer](https://www.youtube.com/watch?v=77Fj7oUx9Es)
