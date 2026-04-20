## Types of Aviation Weather Information
The FAA has identified three distinct types of weather information available to pilots and operators: **Observations** (raw sensor/human data), **Analyses** (interpreted current conditions), and **Forecasts** (predicted future weather).

- **Observation**
	- *Aviation Routine Weather Report (METARS)* - Radar Summary Chart
	- *Pilot Reports (PIREPs)* - *In-Flight Weather Advisories (AIRMETs & SIGMETs)*
- **Analyses**
	- Surface Analysis Chart
- **Forecasts**
	- *Terminal Aerodrome Forecast (TAF)* - Meteorological Impact Statements (MIS) 
	- Prognostic Charts
	- Convective Outlook
	- Wind and Temperature Aloft (FB) 

We will be talking about some of the *printed* reports in this section. Graphical reports are further introduced in [Weather Services (Graphs)](weather-services-graphs).

## METAR
The METAR, originated from French *Meteorologique Aviation Régulière*, is an **Aviation Routine Weather Report**. What that means is the airport is looking at the local weather and is going to put it into a standardized meteorological format on an hourly basis. These METARs are lettered as they come out; so you might be listening to ATIS Information Alpha, and that would include the METAR for that hour. The next hour it's going to be Bravo, the hour after that Charlie, and etc. on down the phonetic alphabet.

### METAR Standardized Format

![Sample METAR report](/images/metarsample.png "Sample METAR report")

- **Type of Report:** \
  It might say **METAR** or it might say **SPECI**. SPECI means a special report, coming out more frequently than on the hour if something meteorologically significant took place.

- **Station Identifier:** For example, **KTPA**. \
  *In the example above, "K" means it's an airport in the United States, and "TPA" is the three-letter identifier for Tampa International Airport.*

- **Date/Time:** - The **day of the month** and time of observation in **Zulu time**. 
	- When a METAR is created by a totally automated weather observation station, the modifier AUTO follows the date/time element.
	- *This example was issued on the 12th of the month at 2150Z*

- **Wind:**
	- It is oriented to **True North**, not Magnetic North.
	- If the wind direction varies 60 degrees or more and the speed is above 6 knots, a variable group follows the wind group. The extremes of wind direction are shown separated by a V. (e.g. 020V090)
	- *In this example, wind from 080 at 20 knots, gusts to 38 knots*

- **Visibility:** - Prevailing visibility is the greatest distance an observer can see and identify objects through at least half of the horizon, and is reported in **Statute Miles (SM)**.
	- **Runway Visual Range (RVR)** might be reported following prevailing visibility. RVR is designated with an R, followed by the runway number, a slant(/), and the visual range.
	- *In this example, R36L/2400FT means Runway 36 Left visual range is 2,400 feet.*

- **Weather Phenomena:** - A minus sign `-` for light or a plus sign `+` for heavy. A description of the precipitation or obscurations is reported as a two-letter code. 
	- Weather phenomena covers nine types of precipitation, eight kinds of obscurations, as well as six, rather uncommon, weather events. *(e.g. RA, GS, FG, etc)*
	- *In this example, a heavy thunderstorm (TS) was reported.*

- **Sky Condition:** Showing amount, height, type, and vertical visibility.
	- The amount of clouds covering the sky is reported in eighths, or octas, of sky cover.
	- A cloud type may be included if towering cumulus clouds (TCU) or cumulonimbus clouds (CB) are present. The code follows the height of their reported base.
	- *In this example, broken clouds (BKN) at 800 ft AGL, and overcast (OVC) at 1,200 ft AGL with cumulonimbus was reported.*

- **Temperature and Dew Point:** The temperature and dewpoint were reported respectively, usually in Celsius.\
  *In this example, it was 20/18 degree Celsius*
    
- **Altimeter:** Preceded by a capital **A**.\
   *In this example, the altimeter setting was reported as 29.95 in. Hg.*
    
- **Remarks:** - Certain remarks are included to report weather considered significant to aircraft operations.
	- The beginning of an event is shown by a "B", followed by the time in **minutes after the hour**. If the event ended before the observation, the ending time in minutes past the hour is noted by an "E".

![Commonly Seen METAR Remarks](/images/metarremarks.png "Commonly Seen METAR Remarks")

## Pilot Weather Report (PIREP)
A Pilot Report (PIREP) is a report of actual weather, braking, or atmospheric conditions encountered **by an aircraft** in flight, transmitted to air traffic control (ATC) or flight service stations (FSS).
\
Types of PIREPs:
- **UA:** Routine PIREP.
- **UUA:** Urgent PIREP (reporting potentially hazardous conditions).

### The PIREP Sequence
The sequence includes: Location, Time (Zulu), Altitude, Aircraft Type, Sky Cover, Visibility, Temperature, Wind, Turbulence, Icing, and Remarks.
\
If that feels like a lot to remember, just keep **PTA** in mind:
- **P**osition
- **T**ime
- **A**ltitude



## Terminal Aerodrome Forecast (TAF)
The weather in the **future** at/around a specific airport is the terminal aerodrome forecast (TAF).
- It predicts the weather, typically a 5 SM radius, at/around an airport.
- **Time of Issuance and Valid Period:**
	- Day of month in 2 digits; time at it was issued in 4 digits. 
	- Normally valid for 24 hours; The first two digits represent the valid date. Next is the beginning **hour** of the valid time in Zulu, and the last two digits are the ending **hour**.
	- *e.g. `221555Z 221612` stands for **Issued at 22nd of month at 15:55 Zulu, valid from 22nd 16:00 Zulu until 23rd 12:00 Zulu***
- Normally scheduled 4 times daily (0000Z, 0600Z, 1200Z, 1800Z).

### Forecast Change Groups
`FM0400 VRBO5KT 3SM BR SCT010 OVC020 BECMG 0610 P6SMNSW` \
→ Starting **From (FM)** 0400 Zulu, the wind is forecast to be **Variable (VRB)** at **5 Knots (05KT)** with a visibility of **3 Statute Miles (3SM)** in **Mist (BR)**, featuring a **Scattered (SCT)** cloud layer at **1,000 feet (010)** and an **Overcast (OVC)** ceiling at **2,000 feet (020)**; subsequently, there is a **Becoming (BECMG)** period between 0600 and 1000 Zulu where conditions improve to **Plus 6 Statute Miles (P6SM)** visibility and **No Significant Weather (NSW)**.

`...TEMPO 1923 VRB08G18KT 3SM -TSRA OVCO10CB`\
→ There will be **Temporary (TEMPO)** fluctuations between 1900 and 2300 Zulu where the wind becomes **Variable at 8 knots gusting to 18 knots (VRB08G18KT)**, visibility drops to **3 Statute Miles (3SM)** with **Light Thunderstorms and Rain (-TSRA)**, and a vertical ceiling of **Overcast at 1,000 feet (OVC010)** with **Cumulonimbus (CB)** clouds present.

`...PROB30 0004 M1/2SM TSRA OVC010CB`\
→ There is a **30% Probability (PROB30)** between 0000 and 0400 Zulu of conditions dropping to **Less than 1/2 Statute Miles (M1/2SM)** visibility in **Thunderstorms and Rain (TSRA)** with an **Overcast (OVC)** ceiling at **1,000 feet (010)** and **Cumulonimbus (CB)** clouds.

## Winds and Temperatures Aloft Forecast (FD)
A winds and temperatures aloft forecast (FD) provides an estimate of wind direction in relation to **true north**, wind speed in knots, and the temperature in degrees Celsius for selected altitudes. Depending on the station elevation, winds and temperatures are usually forecast for nine levels between 3,000 and 39,000 feet. 

![Winds and Temperatures Aloft Forecast Table](/images/fdforecast.png "Winds and Temperatures Aloft Forecast Table")

- Wind speeds between 100 and 199 knots are encoded so direction and speed can be represented by four digits. This is done by adding 50 to the two-digit wind direction and subtracting 100 from the velocity. 
	- e.g. `730540` indicates **Wind 230 at 105 knots with -40°C**
- A code of 9900 indicates **light and variable winds** (less than five knots).

## AIRMETs and SIGMETs
### AIRMET (WA)
AIRMET (WA) is an acronym for **Airman's Meteorological Information (WA)**.
- Issues every **6** hours.
- **Types of AIRMETs:**
	- **Sierra (S) → *See*** - Deal with IFR conditions.
		- Wide areas of obstructed visibility.
	- **Tango (T) → *Turbulence***
		- Turbulence occurrences.
		- Sustained wind over 30 knots.
	- **Zulu (Z) → *iZing***
		- Icing conditions.

### SIGMET (WS)
SIGMETs (WSs) are issued for hazardous weather (other than convective activity), such as include severe icing, severe or extreme turbulence, clear air turbulence (CAT), duststorms and sandstorms lowering visibility to less than 3 miles, and volcanic ash.
- Issues every **4** hours.

### Convective SIGMET (WST)
Convective SIGMETs (WSTs) are issued for hazardous *convective* weather which is significant to the safety of all aircraft, including tornadoes, lines of thunderstorms, thunderstorms over a wide area, embedded thunderstorms, hail greater than or equal to 3/4 inch in diameter, and/or wind gusts to 50 knots or greater. 
- Issues every **2** hours.