# Distance Between 2 Real Points on the Cartesian Plane
```
:Disp "DISTANCE FORMULA"
:Input "X1: ",W
:Input "Y1: ",X
:Input "X2: ",Y
:Input "Y2: ",Z
:ClrHome
:√((W-Y)²+(X-Z)²)→D
:Disp "THE DISTANCE IS",D
```

#### Program Desc

Will ask for the two points (denoted as X1+Y1 and X2+Y2). It will then do the calculation after clearing the screen, and then will show what the distance is.

#### Equation

The mathematical concept is not complicated. The equation,

```
d = √((X1-X2)²+(Y1-Y2)²)
```

is just another way of writing the pythagorean thereom (c² = a² + b²). Well in this case:
```
Let,
 y

 8                  S - Point 1
 |                 /
 6                /
 |               /
 4              /
 |             /
 2  Point 2 - T
 |
 0 -- 2 -- 4 -- 6 -- 8   x

Therefore:
a = change in y, or yS - yT
b = change in x, or xS - xT
 y

 8              S
 |             /|
 6            / |
 |         c /  | a
 4          /   |
 |         /----|
 2        T  b
 |
 0 -- 2 -- 4 -- 6 -- 8   x

 And adding it into the pythagorean therom we get:
 
 c² = (y1 - y2)² + (x1 - x2)²

 Add by taking the square root of both sides we arrive at

 d =  √( (y1 - y2)² + (x1 - x2)² )
```

[Brilliant](https://brilliant.org/wiki/distance-formula/#distance-between-two-points)