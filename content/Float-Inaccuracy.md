# Float Inaccuracy
---

Not to be confused with [Scroll Speed Bug](Scroll-Speed-Bug) or [X position limit](X-Position-Limit).

Float Inaccuracy is a bug that's caused by their way of storing. The gap between representable numbers increases bigger the number is. 
Geometry Dash uses 32-bit floating-point numbers, making the inaccuracy more significant.

As the exponent increases, the distance between two adjacent representable floating-point numbers also increases, because the mantissa is spread out over a much larger range. 

## Effects
Float inaccuracy may cause the player to move slower/faster ([Scroll Speed Bug](Scroll-Speed-Bug)), entirely stop ([X position limit](X-Position-Limit)) on both axis and certain distances from origin. 
However, these are unrelated to the absolute positions limits by `float` data type being 2^128 (3.402823466e+38).