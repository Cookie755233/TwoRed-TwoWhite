## Types of Aviation Weather Information
The FAA has identified three distinct types of weather information available to pilots and operators: **Observations** (raw sensor/human data), **Analyses** (interpreted current conditions), and **Forecasts** (predicted future weather).

- **Observation**
	- Aviation Routine Weather Report (METARS) 
	- *Radar Summary Chart*
	- Pilot Reports (PIREPs) 
	- In-Flight Weather Advisories (AIRMETs & SIGMETs)
- **Analyses**
	- *Surface Analysis Chart*
- **Forecasts**
	- Terminal Aerodrome Forecast (TAF) 
	- Meteorological Impact Statements (MIS) 
	- *Prognostic Charts (Prog Charts)*
	- *Convective Outlook*
	- Wind and Temperature Aloft (FB) 

We will be talking about some of the *graphic* reports in this section. Printed reports are further introduced in [Weather Services (Printed Reports)](weather-services-printed-reports).

> [!CAUTION]
> - *The following classification is based on Aviation Weather Handbook 2024 (FAA-H-8083-28A). Some of the data (e.g. FLs) may vary, it is advised to perform careful validation.*
> - *For detailed SIGWX guidelines, please refer to Guidelines for interpreting World Area Forecast Centre T+24 Significant Weather forecasts V.2.01*
> - *Complete Graphic Forecasts Help can be found at [https://aviationweather.gov/gfa/help/](https://aviationweather.gov/gfa/help/)*

---

## Surface Analysis Chart
- Shows weather conditions as of the valid time shown on the chart.
- Includes locations of high and low pressure systems and associated fronts.
- Issued every 3 hours, eight times daily (0000Z, 0300Z, 0600Z, 0900Z, 1200Z, 1500Z, 1800Z, 2100Z).
- Provides surface weather observations for a large number of reporting points *(station model)*.

![Example of a Surface Chart with Surface Observations](/images/surfacechart.png "Example of a Surface Chart with Surface Observations")

![Station Model Informations](/images/stationpointsample.png "Station Model Informations")

![Weather Symbols](/images/weathersymbols.png "Weather Symbols")

![Pressure Trend Symbols](/images/pressuretrends.png "Pressure Trend Symbols")

---

## Significant Weather (SIGWX) & Prognostic (Prog) Chart 
Significant weather charts are issued by World Area Forecast Centers displaying **cloud, turbulence, jet stream, tropical cyclone, and volcano** forecast information.

### Low-Level Significant Weather Prog Charts (LLSWPC) 
- Covers the conterminous United States (CONUS) and the coastal waters, depicting a “snapshot” of weather expected at the specified valid time.
- Provides information from the surface to FL240 (400 mbs: *pressure level of 400 millibars*).
- **Issuance:**
	- 4 times per day (0000, 0600, 1200, 1800).
	- WAFC SIGWX forecasts are 24-hour forecasts. That means they represent the expected weather 24 hours after the time of observation/analysis.
	- Per ICAO Doc 8896, WAFC SIGWX forecasts are 'usable' for a period of time extending from 3 hours before to 3 hours after the stated 'fixed' validity time.

![SIGWX Issuance](/images/sigwxissuance.png "SIGWX Issuance")

- Altitudes from the surface to 17,999' are referenced using MSL altitudes.
- Altitudes from 18,000' to FL240 are referenced using pressure altitude.
- **Provided in two forecasts in 4 panels:**
	- **Top:** Surface to FL240 (400MB); 12/24 hour.
	- **Bottom:** Surface; 12/24 hour.
- **Contents:**
	- Flying Categories: IFR, MVFR *(Marginal Visual Flight Rules)*, **VFR NOT DEPICTED**.
	- Turbulence.
	- Freezing Levels.

![Sample of a LLSWPC](/images/llswpc.png "Sample of a LLSWPC")

![Common Legends](/images/llswpclegends.png "Common Legends")

### Mid-Level Significant Weather (SIGWX) Charts
- Provides a forecast of significant en route weather phenomena over a range of FLs from 10,000 ft MSL to FL450.
- **Issuance:** 4 times daily.
- **Content:** Non-Convective Clouds with Moderate or Severe Icing and/or Moderate or Severe Turbulence.

![Mid Level SIGWX](/images/midlevelsigwx.png "Mid Level SIGWX")

### High-Level Significant Weather Prog Charts (HLSWPC)
- HLSWPC is a day 1 forecast of significant weather in the CONUS from FL250 to FL630.
- Provided for the en route portion of international flights.
- **Issuance:** 4 times daily.
- **Contents:**
	- Thunderstorms and Cumulonimbus Clouds (CB).
	- Moderate or Severe Turbulence.
	- Moderate or Severe Icing.
	- Jet Streams.
	- Tropopause Heights.
	- Tropical Cyclones.
	- Volcanic Eruption Sites.

![Sample of a HLSWPC](/images/hlswpc.png "Sample of a HLSWPC")

### Short-Range Surface Prognostic (Prog) Charts
- Combines WPC forecasts of fronts, isobars, and high/low pressure systems with the NWS’ National Digital Forecast Database (NDFD) digital forecasts.
- *Short-range surface prognostic (prog) charts focus on predicting pressure systems, fronts, and precipitation at the surface, while Low-Level Significant Weather (SIGWX) charts forecast specific aviation hazards.*
- **Contents:**
	- Precipitation.
	- Pressure.
	- Fronts.
	- Squall Lines.

![Sample of a Short Range Prog Chart](/images/shortrangeprog.png "Sample of a Short Range Prog Chart")

---

## Convective Outlook Chart (AC)
> [!CAUTION]
> - *The following risk is referred to NOAA's newest display changes, which may vary from your textbook.*
> - [Conditional Intensity Information](https://www.spc.noaa.gov/exper/conditional-intensity-information/)
> - [Changes to SPC Day 1, 2, and 3 Convective Outlook Probabilities](https://www.weather.gov/news/262402-spc)

- A Convective Outlook (AC) delineates areas *forecast* to have **thunderstorms**.
- Contains 2 panels: Day 1 (24-hour) on the left; Day 2 (48-hour) on the right.
- Issued as required.
- **Levels of Risks:** - **TSTM** (light green) non-severe.
	- **1-MRGL** (dark green).
	- **2-SLGT** (yellow).
	- **3-ENH** (orange).
	- **4-MDT** (red).
	- **5-HIGH** (magenta).

![Severe Thunderstorm Risk Categories](/images/thunderstormriskcategories.png "Severe Thunderstorm Risk Categories")

![New Changes in Convective Outlook Charts](/images/convectiveoutlooknew.png "New Changes in Convective Outlook Charts")