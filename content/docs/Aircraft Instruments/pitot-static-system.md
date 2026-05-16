---
weight: 1
---

## Pitot-static System
> **The pitot-static system is a combined system that utilizes the static air pressure and the dynamic pressure due to the motion of the aircraft through the air. These combined pressures are utilized for the operation of the airspeed indicator (ASI), altimeter, and vertical speed indicator (VSI)**

![Pitot-static System and Instrument](/images/pitotstatic.png "Pitot-static System and Instrument")

The **pitot tube** accepts ram air from the atmosphere as the aircraft is moving forward, also called impact or *ram* air pressure. The pitot tube is usually mounted on the wing or on the nose section, so the opening is exposed to the *relative* wind

The **static port** is sensing static air pressure, which is normally flush-mounted on the side of the fuselage in an area of relatively undisturbed air.

> [!note]
>  An alternate static source is provided in some aircraft.When the alternate static source pressure is used, the following instrument indications are observed: (PHAK 8-3)
> 1. The altimeter indicates a slightly higher altitude than actual. 
> 2. The ASI indicates an airspeed greater than the actual airspeed.
> 3. The VSI shows a momentary climb and then stabilizes if the altitude is held constant.

## Pitot-static Instruments
### Airspeed Indicator (ASI)
![Airspeed Indicator](/images/asi.png "Airspeed Indicator")

> **The ASI is a differential pressure gauge that measures and promptly indicates the difference between pitot (impact/ram) and static pressure.**

This is the one instrument in the pitot-static system that receives *both* pitot air and static pressure air. The ASI introduces the static pressure into the airspeed case while the pitot pressure (dynamic) is introduced into the diaphragm. The *dynamic pressure expands or contracts one side of the diaphragm*, which is attached to an indicating system. The system drives the mechanical linkage and the airspeed needle.

#### Types of Airspeeds
1. Indicated airspeed (IAS)
The direct instrument reading obtained from the ASI.

2. Calibrated airspeed (CAS)
IAS corrected for *installation error and instrument error*.

3. True airspeed (TAS)
CAS corrected for altitude and *nonstandard temperature.*
	 - For a given CAS, TAS increases as altitude increases; 
	 - For a given TAS, CAS decreases as altitude increases

4. Equivalent airspeed (EAS)
CAS corrected for compressibility effects that occur at *higher*
*speeds and altitudes.*

5. Ground speed (GS)
TAS adjusted for wind. It is the actual speed of the airplane over the ground. 

```
	[ Indicated Airspeed (IAS) ]
                 |
                 |  + Position & Instrument Error
                 v
    [ Calibrated Airspeed (CAS) ]
                 |
                 |  + Compressibility (High Spd/Alt)
                 v
    [ Equivalent Airspeed (EAS) ]
                 |
                 |  + Air Density (Alt & Tmp)
                 v
    [   True Airspeed (TAS)   ]
                 |
                 |  + Wind
                 v
    [     Ground Speed (GS)    ]
```


#### Airspeed Indicator Markings 
> [!TIP]
> So → Fe → S1 → No → Ne *(“So fancy, no need!”)*
> ![Airspeed Indicator Markings](/images/asiindicator.png "Airspeed Indicator Markings")

- White Arc **(Flap Operating Range)**: 
    - Bottom: Defined by \(V_{SO}\). This is the **stalling speed in the landing configuration** (flaps and gear down).
    - Top: Defined by \(V_{FE}\). This is the speed we need to be **at or below with the flaps fully extended.**
        
- Green Arc (Normal Operating Range): 
    - Bottom: Defined by \(V_{S1}\). This is the stalling speed in a **specific/clean, meaning flaps and gear up,  configuration.**
    - Top: Defined by \(V_{NO}\). This is the maximum *structural cruising speed.* You should only exceed this in smooth air.
        
- Yellow Arc (Caution Range): \
   This range starts at \(V_{NO}\) and ends at the red line \(V_{NE}\). You should only fly in this range *in smooth air and with caution.*
    
- Red Line (Never Exceed Speed): \
  Defined by \(V_{NE}\). Operating above this speed may result in *structural damage or failure.*

|**Color Arc**|**Speed Range Name**|**Description**|
|---|---|---|
|**White Arc**|Flap Operating Range|Starts at **\(V_{SO}\)** (Stall speed in landing configuration) and ends at **\(V_{FE}\)** (Maximum flap extended speed).|
|**Green Arc**|Normal Operating Range|Starts at **\(V_{S1}\)** (Stall speed in a clean configuration) and ends at **\(V_{NO}\)** (Maximum structural cruising speed).|
|**Yellow Arc**|Caution Range|Range between **\(V_{NO}\)** and **\(V_{NE}\)**. Operate within this range only in smooth air and with caution.|
|**Red Line**|Never Exceed Speed|**\(V_{NE}\)**; exceeding this speed may cause structural failure.|

##### Other Airspeed Limitations
- **Design maneuvering speed \(V_A\)**
	- The maximum speed at which the structural design’s limit load can be imposed without causing structural damage.
	- \(V_{A}\) is not marked because it **changes with the weight** of the aircraft. 
	- **As weight goes down, \(V_{A}\) goes down.**
	- *Read more at [load-factor](/docs/Aerodynamics/load-factor)*

- **Best angle-of-climb speed \(V_X\)**:\
  The airspeed at which an aircraft gains the **greatest amount of altitude in a given distance**. It is used during a short-field takeoff to clear an obstacle.

- **Best rate-of-climb speed \(V_Y\)**:\
  The airspeed that provides the **most altitude gain in a given period of time**.

![Vx vs Vy](/images/vxvy.png "Vx vs Vy")

### Altimeter
> **The altimeter is an instrument that measures the height of an aircraft above a given pressure level**

![Altimeter](/images/altimeter.png "Altimeter")

A stack of sealed *aneroid wafers* comprise the main component of the altimeter. An aneroid wafer is a sealed wafer that is evacuated to an internal pressure of 29.92 inches of mercury ("Hg). These wafers are free to expand and contract with changes to the static pressure. A higher
static pressure presses down on the wafers and causes them to collapse. A lower static pressure allows the wafers to expand. A mechanical linkage connects the wafer movement to the needles on the indicator face, which translates compression of the wafers into a decrease in altitude and translates an expansion of the wafers into an increase in altitude.

Adjustments for nonstandard pressures are accomplished by setting the corrected pressure into a barometric scale located on the face of the altimeter. 

#### Effect of Nonstandard Pressure and Temperature
> [!CAUTION]
> High to Low , Look out Below!\
> Hot to Cold, Look out Below!

If an aircraft is flown from a high pressure area to a low pressure area without adjusting the altimeter, a constant altitude will be displayed, but the actual height of the aircraft above the ground would be lower than the indicated altitude.

Since cold air is denser than warm air, when operating in temperatures
that are colder than standard, the altitude is lower than the altimeter indication.

![Effects of nonstandard temperature on an altimeter](/images/hottocold.png "Effects of nonstandard temperature on an altimeter")

#### Types of Altitudes
1. **Indicated altitude**—read directly from the altimeter (uncorrected) when it is set to the current altimeter setting.
    
2. **True altitude**—the vertical distance of the aircraft above sea level—the actual altitude. It is often expressed as feet above mean sea level (MSL). Airport, terrain, and obstacle elevations on aeronautical charts are true altitudes.
    
3. **Absolute altitude**—the vertical distance of an aircraft above the terrain, or above ground level (AGL).
    
4. **Pressure altitude**—the altitude indicated when the altimeter setting window (barometric scale) is adjusted to 29.92 "Hg. This is the altitude above the standard datum plane, which is a theoretical plane where air pressure (corrected to 15 °C) equals 29.92 "Hg. Pressure altitude is used to compute density altitude, true altitude, true airspeed (TAS), and other performance data.
    
5. **Density altitude**—pressure altitude corrected for variations from standard temperature. When conditions are standard, pressure altitude and density altitude are the same. If the temperature is above standard, the density altitude is higher than pressure altitude. If the temperature is below standard, the density altitude is lower than pressure altitude. This is an important altitude because it is directly related to the aircraft’s **performance**.

### Vertical Speed Indicator (VSI)
> **The Vertical Speed Indicator indicates the rate of climb, in feet per minutes, using the the pressure differential between static port and calibrated leak.**

> [!info]
> The static port goes to the diaphragm.\
> The difference between the case and the diaphragm is the rate of descent/climb.


The time period from the initial change in the rate of climb, until the
VSI displays an accurate indication of the new rate, is called the lag. Some aircraft are equipped with an instantaneous vertical speed indicator (IVSI), which incorporates accelerometers to compensate for the lag in the typical VSI.

![IVSI](/images/ivsi.png "IVSI")

   
## Pitot Tube Errors
Now let's jump into some possible errors that might be introduced into this system. Let's start with a **blocked pitot tube**.

### Scenario 1: Pitot Tube Blocked, Drain Hole Open
*Moisture in the system drains out of that pitot tube system through drain hole.*

With the pitot tube blocked and the drain hole open, that airspeed indicator is not going to get that ram air, and so it's **not going to be able to indicate—the needle drops to zero**. Meanwhile, the case pressure is operating just fine. 

```
	[ RAM AIR SOURCE ]
            |
            X <--- BLOCKAGE (Insects, Ice, Dirt)
            |
    [   PITOT TUBE   ]
            |
            +------> [ DRAIN HOLE (OPEN) ]
            |                |
            |                v
            |          Remaining air pressure 
            |          bleeds out to atmosphere
            |
    [ AIRSPEED INDICATOR ]
            |
            v
    [ DIAPHRAGM / WAFER ] <--- Pressure drops to ambient
            |
            |  (Diaphragm collapses because 
            v   Internal Pressure = Case Pressure)
            |
    [ NEEDLE DROPS TO 0 ]
```

### Scenario 2: Pitot Tube AND Drain Hole Both Blocked
If the pitot and the drain were to somehow block in flight, the diaphragm inside the airspeed indicator would be blocked off. That would be like taking that diaphragm—think of it as a balloon—we blow it up, we tie it off, and *we've got fixed pressure inside that diaphragm.*

As the aircraft climbs or descends in altitude, there's nothing wrong with the static air. Imagine the diaphragm inside the airspeed indicator squeezed off like a balloon, *yet the static air can still travel in and out of the case.*

- **In a Climb**: Static air pressure drops. There's less static air pressure inside the airspeed instrument case. That "balloon" (diaphragm) can expand. In normal operation, when that diaphragm expands, that means airspeed is going up. So if I go up in altitude, the diaphragm will expand into lower case pressure; that will appear as **increasing airspeed**.
- **In a Descent**: Static pressure increases in the case and shrinks that diaphragm. In normal operation, when that diaphragm shrinks, that indicates lower and lower airspeed.

Sometimes you'll hear flight instructors talk about this error causing the airspeed to **act as an altimeter**. If I go up in altitude with this error, I go up in airspeed. If I go down in altitude, I go down in airspeed.

```
[ RAM AIR INLET ]         [ DRAIN HOLE ]
           X                        X
           |                        |
           +-----------[BLOCKAGE]---+
                       |
                       v
          [ TRAPPED AIR PRESSURE ]
          (Fixed volume in Diaphragm)
                       |
                       |
        +--------------+--------------+
        |                             |
    [ CLIMB ]                    [ DESCENT ]
        |                             |
  Static Pressure               Static Pressure
   in Case DROPS                 in Case RISES
        |                             |
  Diaphragm EXPANDS             Diaphragm SHRINKS
        |                             |
  Needle moves UP               Needle moves DOWN
        |                             |
        v                             v
 [ INDICATED SPEED             [ INDICATED SPEED 
     INCREASES ]                   DECREASES ]
```

## Static Port Errors
What if the **static port** were to be blocked?

- **Altimeter**: The pressure in the altimeter's case is going to be locked. The altimeter is just going to **freeze**; it's not going to work.
- **VSI**: The static line runs to the diaphragm inside the vertical speed indicator. If that port is sealed off, the air in that line is trapped. The vertical speed indicator is just going to sit on **zero**.
- **Airspeed Indicator**: If the static port becomes blocked and the aircraft is **above** the altitude where the port became blocked, the airspeed will indicate **lower**. Why? Because that trapped static air pressure is higher than it should be for that higher altitude.
    