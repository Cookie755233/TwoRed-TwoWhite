## Types of Navigation
### Pilotage
Pilotage is when we reference landmarks *(checkpoints)* to help us navigate to and from specific locations. A pilot would navigate by visual connection to those points; that is pilotage. *(In simple English, visual flight)*.
- Checkpoints are visual cues with distinct shape/feature, visible from the air, to help pilots recognize and correct for routing.
### DE(A)D Reckoning
By taking **time**, **speed**, a known **direction** (or heading), and the **distance** to a certain point, and we're using those four things to *deduce* where we are.
### Electronic Navigation *(Radio/Satellite Navigation)*
- Very High Frequency Omnidirectional Range (VOR)
- Horizontal Situation Indicator (HSI)
- Radio Magnetic Indicator (RMI)
- Distance Measurement Equipment (DME)
- Automatic Direction Finder (ADF)
- Area Navigation (RNAV)
- Global Positioning System (GPS)

## Courses 
A Course is an intended flight path/line drawn on chart. However, in real scenarios, this would hardly be possible subjected to wind and weather conditions. Therefore it is important to understand the differences and relation between heading and directions we're flying to.
\
The core of air navigation is the process of correcting a **True Course** (the path on a map) for 3 distinct factors:
1. **Magnetic Variation:** The difference between the Geographic North Pole and the Magnetic North Pole.
2. **Wind:** The lateral drift caused by crosswinds, requiring a **Wind Correction Angle (WCA)**.
3. **Compass Deviation:** Local magnetic interference within the aircraft itself (engine, electronics).

The progression follows this logical flow:
```text
TRUE COURSE (TC)
         |
  [ +/- VARIATION ]  <-- (Correct for variation)
         |
         v
 MAGNETIC COURSE (MC)
         |
  [ +/- WIND ]       <-- (Correct for wind)
         |
         v
 MAGNETIC HEADING (MH)
         |
  [ +/- DEVIATION ]  <-- (Look into magnetic compass and correct for deviation)
         |
         v
 COMPASS HEADING (CH)