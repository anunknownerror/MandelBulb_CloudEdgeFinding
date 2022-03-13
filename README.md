# MandelBulb_CloudEdgeFinding
MandelBulb as from the Coding Train but with more edge points

I've refactored the original code a bit so checking if a point is in the Mandelbulb is a booelean function.
This is then used to check for each point that are in the bulb to check how many neighbours it has that are also in the bulb.
If this number is too high we don't add it the list. In this way you can keep track of points that are on the edge of the bulb and get a more detailed picture.

It's slow, because it is not optimized, but also not too stupid that it will crash your pc.
