# Quadrant Finder

```
:Input "POINT X? ",X
:Input "POINT Y? ",Y
:If X>0 and Y>0:Disp "QUADRANT 1"
:If X<0 and Y>0:Disp "QUADRANT 2"
:If X<0 and Y<0:Disp "QUADRANT 3"
:If X>0 and Y<0:Disp "QUADRANT 4"
:If X=0 and Y≠0:Disp "Y-AXIS"
:If Y=0 and X≠0:Disp "X-AXIS"
:If X=0 and Y=0:Disp "ORIGIN"
```

#### Porgram Desc

The program will ask for a point, and then will go through multiple if statements to determine which quardrant it is in.

#### Equation

```

                        {    X > 0 and Y > 0 means Quadrant 1
                        {
                        {    X < 0 and Y > 0 means Quadrant 2
                        {
                        {    X < 0 and Y < 0 means Quadrant 3
                        {
FOR REAL POINT (x, y) = {    X > 0 and Y < 0 means QUardrant 4
                        {
                        {    X = 0 and Y ≠ 0 means Y Axis
                        {
                        {    X ≠ 0 and Y = 0 means X Axis
                        {
                        {    X = 0 and Y = 0 means Origin
```

This will tell you what part of the graph a real point is on the cartesian plane. [Wikipedia](https://en.wikipedia.org/wiki/Cartesian_coordinate_system)