# Midpoint

```
:Disp "MDPT"
:Input "X1? ",X
:Input "Y1? ",Y
:Input "X2? ",F
:Input "Y2? ",S
:ClrHome
:(X+F)/2→Q 
:(Y+S)/2→Z
:Disp Q
:Disp Z
```

#### Program Desc

It will ask for the two points on the cartesian plane, and then will clear screen. After doing the calculations, and then will display the answers.

#### Equation

The midpoint is the middle of two points, where there is a straight connecting them. The equation takes the average of the two x values, and then it will also take the average two y values. This will return the midpoint. Here is a diagram of what I mean:

```
X (1,4)
 \
  \
   M
    \
     \
      X (5,2)


X Number line: 
<-----|-----X-----|-----|-----|-----X-----|-----|----->
      0     1     2     3     4     5     6     7
<-----|-----X-----|-----M-----|-----X-----|-----|----->

1 + 5 = 6
6 / 2 = 3
Midpoint X = 3

Y Number line:
<-----|-----|-----Y-----|-----Y-----|-----|-----|----->
      0     1     2     3     4     5     6     7
<-----|-----|-----Y-----M-----Y-----|-----|-----|----->

2 + 4 = 6
6 / 2 = 3
Midpoint Y = 3

This denotes the equation(s):

[ X1 + X2       Y1 + Y2 ]
[ -------   ,   ------- ]
[    2             2    ]
```

There is the basics of midopint. [Wikipedia](https://en.wikipedia.org/wiki/Midpoint)
