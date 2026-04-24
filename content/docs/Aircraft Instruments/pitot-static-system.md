## Pitot-static System
![Pitot-static System and Instrument](/images/pitotstatic.png "Pitot-static System and Instrument")

This **pitot tube** accepts ram air from the atmosphere as the aircraft is moving forward, also called impact or *ram* air pressure. The pitot tube is usually mounted on the wing or on the nose section, so the opening is exposed to the *relative* wind

The **static port** is sensing static air pressure, which is normally flush-mounted on the side of the fuselage in an area of relatively undisturbed air.

> [!note]
>  An alternate static source is provided in some aircraft.When the alternate static source pressure is used, the following instrument indications are observed:
> 1. The altimeter indicates a slightly higher altitude than actual. 
> 2. The ASI indicates an airspeed greater than the actual airspeed.
> 3. The VSI shows a momentary climb and then stabilizes if the altitude is held constant.

## Pitot-static Instruments
### Airspeed Indicator (ASI)
![Airspeed Indicator](/images/asi.png "Airspeed Indicator")

**DEFINITION:**\
**The ASI is a differential pressure gauge that measures and promptly indicates the difference between pitot (impact/ram) and static pressure.**

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
![Airspeed Indicator Markings ](/images/asiindicator.png "Airspeed Indicator Markings ")

- White Arc **(Flap Operating Range)**: 
    - Bottom: Defined by V<sub>SO</sub>. This is the **stalling speed in the landing configuration** (flaps and gear down).
    - Top: Defined by V<sub>FE</sub>. This is the speed we need to be **at or below with the flaps fully extended.**
        
- Green Arc (Normal Operating Range): 
    - Bottom: Defined by V<sub>S1</sub>. This is the stalling speed in a **specific/clean, meaning flaps and gear up,  configuration.**
    - Top: Defined by V<sub>NO</sub>. This is the maximum *structural cruising speed.* You should only exceed this in smooth air.
        
- Yellow Arc (Caution Range): \
   This range starts at V<sub>NO</sub> and ends at the red line V<sub>NE</sub>. You should only fly in this range *in smooth air and with caution.*
    
- Red Line (Never Exceed Speed): \
  Defined by V<sub>NE</sub>. Operating above this speed may result in *structural damage or failure.*

> [!TIP]
> So → Fe → S1 → No → Ne \
> *(“So fancy, no need!”)*

|**Color Arc**|**Speed Range Name**|**Description**|
|---|---|---|
|**White Arc**|Flap Operating Range|Starts at **V<sub>SO</sub>** (Stall speed in landing configuration) and ends at **V<sub>FE</sub>** (Maximum flap extended speed).|
|**Green Arc**|Normal Operating Range|Starts at **V<sub>S1</sub>** (Stall speed in a clean configuration) and ends at **V<sub>NO</sub>** (Maximum structural cruising speed).|
|**Yellow Arc**|Caution Range|Range between **V<sub>NO</sub>** and **V<sub>NE</sub>**. Operate within this range only in smooth air and with caution.|
|**Red Line**|Never Exceed Speed|**V<sub>NE</sub>**; exceeding this speed may cause structural failure.|

#### Other Airspeed Limitations
- Design maneuvering speed (V<sub>A</sub>)
	- The maximum speed at which the structural design’s limit load can be imposed without causing structural damage.
	- V<sub>A</sub> is not marked because it **changes with the weight** of the aircraft. 
	- **As weight goes down, V<sub>A</sub> goes down.**
	- *Read more at [load-factor](/Aerodynamics/load-factor)*

- Best angle-of-climb speed (V<sub>X</sub>)
  The airspeed at which an aircraft gains the **greatest amount of altitude in a given distance**. It is used during a short-field takeoff to clear an obstacle.

- Best rate-of-climb speed  (V<sub>Y</sub>)
  The airspeed that provides the **most altitude gain in a given period of time**.
![Vx vs Vy](/images/vxvy.png "Vx vs Vy")

### Altimeter
**DEFINITION:**\
**The altimeter is an instrument that measures the height of an aircraft above a given pressure level**

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
**DEFINITION:**\
**The Vertical Speed Indicator indicates the rate of climb, in feet per minutes, using the the pressure differential between static port and calibrated leak.**

> [!info]
> The static port goes to the diaphragm.\
> The difference between the case and the diaphragm is the rate of descent/climb.


The time period from the initial change in the rate of climb, until the
VSI displays an accurate indication of the new rate, is called the lag. Some aircraft are equipped with an instantaneous vertical speed indicator (IVSI), which incorporates accelerometers to compensate for the lag in the typical VSI.

![IVSI](/images/ivsi.png "IVSI")

