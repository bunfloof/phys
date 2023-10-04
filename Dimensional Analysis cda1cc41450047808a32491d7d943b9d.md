# Dimensional Analysis

date: October 2, 2023
published: No

Ideas and learning outcomes for today:

- Scientific notation quick review:
    
    $$
    10^3 = 1000, 10^3 \times 10^2 = 10^5, \frac{10^5}{10^3} = 10^{(5-3)} = 10^2 = 100
    $$
    
- Physical quantities, unless they are ratios (like $\pi$), usually have dimensions. In this class, spatial positions are most often in units of meters (m), and time is in units of seconds (s).
- There are other units for the same quantity, such as kilometers ($10^3$ m) or miles or feet or inches or…., and we often convert from one to another. You need to be able to convert units without looking up conversion factors. To do that reliably and to know whether you need to multiply or divide, set up a conversion fraction. For example, to convert 1 kilometer to miles:
    
    $$
    1km\times \frac{10^3m}{1km}\times\frac{10^2cm}{1m}\times\frac{1inch}{2.54cm}\times \frac{1 foot}{12 inches}\times\frac{1 mile}{5280 feet}
    $$
    
    (Don't worry: we won't expect you to have those conversion factors memorized for exams.) Notice you can cancel units in the numerator and denominator, so, after the first step, the distance of 1 km is now in units of meters, and after the second step it's in units of em, and so on. Use your calculator for that chain of fractions - you should get that 1 km is about 0.62 miles. (If you've driven a car with a speedometer with both units, you see that 55 mph is about 88 kph (km per hour). Does that match what we calculated here?).
    
    Also note that there isn't a unique path for the conversion - I happened to know that there are 2.54 cm in one inch so I did it that way. What matters is the technique, so you don't have to guess.
    
- When an object moves at constant velocity, v (which has units m/s), the distance, $\Delta x$, it moves in time, $\Delta t$, is
    
    $$
    \Delta x = v \Delta t
    $$
    
    Check that the units are the same on the left and right side. In vacuum (nothingness), light moves at constant velocity. We’ll practice using the above ideas to calculate some interesting quantities today using the velocity of light.
    
    ---
    
1. In empty space (aka vacuum), light travels at $c = 3 \times 10^8$ m/s. (The velocity of light is a fundamental physical constant, so we give it its own special symbol, c, instead of the general v.)
    1. Convert this velocity to miles per second, showing each of your steps.
        
        $$
        3\times 10^8 m/s \times \frac{10^2cm}{1m} \times \frac{1inch}{2.54cm}\times \frac{1 foot}{12 inches}\times\frac{1 mile}{5280 feet}=\boxed{186411.3576 m/s}
        $$
        
    2. How far, in feet, does light travel in 1 nanosecond (that’s $10^{-9}$s or one billionth of a second)?
        
        $$
        3\times 10^8 m/s \times \frac{10^2cm}{1m} \times \frac{1inch}{2.54cm}\times \frac{1 foot}{12 inches}=984251969 ft/s \\
        984251969 ft/s \times \frac{10^{-9}s}{1 ns}=\boxed{0.984251969 ft/ns}
        $$
        
    3. A lightyear is the distance light travels in one year. How many meters are there in 1 lightyear?
        
        $$
        3\times 10^8 m/s\times \frac{60s}{1min}\times\frac{60min}{1hour}\times\frac{24hours}{1day}\times\frac{365days}{1year}=\boxed{9.4608\times10^{15}m/s}
        $$
        
    4. The newspaper reported that the radio signal (which also travels at speed, c) from the New Horizons spacecraft took about 6 hours to reach the earth. How far away, in kilometers, was the spacecraft?
        
        $$
        3\times 10^8 m/s * \frac{60s}{1min}\times\frac{60min}{1hour}\times 6 hours = 6.48 \times 10^{12}m \\
        6.48 × 10^{12}m\times \frac{1km}{10^3m}=\boxed{6.48×10^9km}
        $$
        
    5. The earth is about 150 million km from the sun. How long (in minutes) does it take light emitted from the sun to reach the earth?
        
        $$
        3\times 10^8 m/s \times \frac{1 km}{10^3m}=300000 km/s\\
        
        150000000 km \times \frac{1 s}{300000 km}=500s\times\frac{1min}{60s}=\boxed{8.3333 min}
        $$