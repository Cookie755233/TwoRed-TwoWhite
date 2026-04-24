   

## Pitot Tube Errors
Now let's jump into some possible errors that might be introduced into this system. Let's start with a **blocked pitot tube**.

### Scenario 1: Pitot Tube Blocked, Drain Hole Open
*Moisture in the system drains out of that pitot tube system through that drain hole.*

With the pitot tube blocked and the drain hole open, that airspeed indicator is not going to get that ram air, and so it's not going to be able to indicate. Meanwhile, the case pressure is operating just fine. 

**TL;DR:**\
**The needle is going to drop to zero.**

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
    

