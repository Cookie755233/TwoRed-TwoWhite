## VOR Basics
VOR, by definition, means **Very High Frequency**—that's the V, very high frequency, that means it's in the VHF band range, so it's VHF equipment—**Omnidirectional**—Omni means all, and in this case, it means all around or, in navigation, 360 degrees—and **Range**.

There are three types of VORs:
1. **VOR**: Provides azimuth only using 360 magnetic radials.
2. **TACAN**: *Military* system providing azimuth and distance.
3. **VORTAC**: 
	- VOR + TACAN
	- Used by the military
	- In the Ultra high frequency (UHF) range
4. **VOR/DME**: 
	- VOR with *Distance Measuring Equipment (DME)* equipped.

![Radio NAVAID Symbols](/images/radionavaidssymbols.png "Radio NAVAID Symbols")

### How it Works
VOR works with two pulses. 
\
The first pulse is the **omnidirectional pulse**, which means omnidirectional range; this is an electronic pulse that goes out in *all* directions. 
\
The second pulse is a **sweeping beam**. That sweeping beam is at the 12 o'clock position, or on the VOR that would be **360 degrees magnetic**, because **VORs are oriented to magnetic north**. 
\
That sweeping beam is at 360 when the Omni beam pulses; that sweeping beam then continues on around, and when it is picked up by the receiver, the receiver measures the time difference between that Omni beam and the sweeping beam. The longer that time distance, the further that receiver is around that 360-degree circle.

Now when we navigate, we think of ourselves as being on a **radial**. My receiver can determine the radial between the pulsing beam and the sweeping beam. If I have a TACAN or a DME, I can also determine my distance from that station.



### Classifications
When we look at VORs in the United States, we see that they are classified into three classifications (You can find the class designation of a VOR facility in the A/FD *Airport/Facility Directory*):

- **Terminal (T)** *low power; nearest*
	- <25 NM
	- <12,000 ft
	- Airport
- **Low Altitude (L)** *medium power*
	- <40 NM
	- 1,000 ~ 18,000 ft
- **High Altitude (H)** *high power; furthest*
	- 40 NM; 14,500 ft
	- 100 NM; 14,500 ft ~ 18,000 ft
	- 130 NM; 18,000 ft ~ FL 450
	- 100 NM; FL 450 ~ FL 600

The reason for those different classifications is that they have different wattage outputs determining how far away they can be used. The Terminal VORTAC is low power, the Low Altitude VORTAC is medium power, and that High Altitude VORTAC is high power.

### Equipment
The equipment is both ground-based and airborne.

#### Ground Equipment: 
A VOR or a VORTAC or VOR/DME looks like a round building and it's got that cone-shaped transmitter up on top of it. That is what is sending out that omnidirectional pulse and that sweeping beam.

![VHF Omnidirectional Range - VOR](/images/vor.png "VHF Omnidirectional Range - VOR")

#### Airborne Equipment: 
1. **The Receiver:** This is what we use to dial in that VHF frequency and select that VOR signal.
2. **The Navigational Instrument:**
    - **OBS Selector (Omni Bearing Selector)/Course Selector:** This is a knob in the lower left that you turn. It allows you to dial in which of those 360-degree radials you would like the instrument to tune into.
    - **CDI (Course Deviation Indicator):** *"the needle"*. CDI Indicates whether you are on your selected course.
    - **To/From Flag:** Indicates whether your selected course will take you to *(TO)* or from *(FM)* the station.
    - **Dot Spacing:** Each dot equals **2** degrees of deviation.

![VOR Airborne Equipment](/images/vorairborne.png "VOR Airborne Equipment")

### Horizontal Situation Indicator (HSI)
The HSI combines a *heading indicator* and *VOR indicator* in a single display, providing you with an easy-to-interpret navigation picture.

![Horizontal Situation Indicator](/images/hsi.png "Horizontal Situation Indicator")

### Distance Measuring Equipment (DME)
- DME shows the distance from the aircraft to the VOR station.
- The distance measured is **slant** *(direct line-of-sight)*, aircraft to station, range, not ground distance.
- When flying directly over the station, DME reads your altitude above it in **nautical** miles (NM).
- The DME only reaches zero when the aircraft is on the ground.
- Can receive reliable signal up to 199 n.m. from the station.



---

## VOR Limitations
- **Line of sight:** VHF signals require **direct line of sight** and can be blocked by terrain.
- **Unusable sectors:** Areas with unreliable signals due to terrain, interference, or service volume limits.
- **Cone of confusion:** Signal becomes unreliable directly **over** the station.
- **Zone of ambiguity:** Occurs **90 degrees** on either side of the course where TO/FROM is unreliable.
	- Depending on the type of your aircraft, you might see the "neutral flag" or the TO/FROM arrows disappear. That's when you know you're in the zone of ambiguity.

## VOR Checking
### VOT (VOR Test Facilities)
A VOT verifies proper operation of a VOR receiver. VOT enables you to make precise VOR accuracy checks *regardless* of your position in relation to the facility.
\
**VOT check procedure**
1. Tune the published frequency.
2. Rotate the OBS to 0 or 180 (0 = FROM, 180 = TO).
3. Confirm the needle is centered.
*Error tolerance: No VFR limit specified, IFR is ± 4° on the ground and ± 6° in flight.*

### Triangulation (Cross Checking)
Determine your location *FROM* two stations and draw lines of positions (LOP) on those radials. Your position is where the two LOPs intersect.



---

## Remarks
- **UHF vs VHF?**
	- VHF (136-174 MHz) is superior for long-distance, outdoor, and open-field communication.
	- UHF (400-470 MHz) has shorter wavelengths that penetrate buildings better, ideal for urban environments.
- **CDI vs HSI?**
	- CDI is a standalone instrument where you manually select a radial. The HSI incorporates this into a heading indicator, reducing mental gymnastics because your heading is automatically integrated with the radial information.