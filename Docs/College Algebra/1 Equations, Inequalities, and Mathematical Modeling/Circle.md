# Circle Equation
```
:Menu("CIRCLE","RADIUS- 2 POINTS",A,"RADIUS- CENTER+POINT",B,"CENTER- 2 POINTS",C,"EQUATION- 2 POINTS",D,"EQUATION- CENTER+POINT",E,"EQUATION- CENTER+RADIUS",F,"IS POINT VALID?",G)
:Lbl A
:Input "X1? ",X
:Input "Y1? ",Y
:Input "X2? ",F
:Input "Y2? ",L
:ClrHome
:√((X-F)²+(Y-L)²)→R
:Disp "THE DIA IS ",R
:Disp "THE RADIUS IS ",(R/2)
:Stop
:Lbl B
:Input "X1? ",X
:Input "Y1? ",Y
:Input "X2? ",F
:Input "Y2? ",L
:√((X-F)²+(Y-L)²)→R
:Disp "THE DIA IS ",(R*2)
:Disp "THE RADIUS IS ",R
:Stop
:Lbl C
:Input "X1? ",X
:Input "Y1? ",Y
:Input "X2? ",F
:Input "Y2? ",L
:ClrHome
:(X+F)/2→H
:(Y+L)/2→K
:Disp "CENTER (X,Y): "
:Disp H,K
:Stop
:Lbl D
:Input "X1? ",X
:Input "Y1? ",Y
:Input "X2? ",F
:Input "Y2? ",L
:ClrHome
:(√((X-F)²+(Y-L)²)/2)→R
:(X+F)/2→H
:(Y+L)/2→K
:Disp "(X - H)² + (Y - K)² = R²"
:Disp "H: ",H
:Disp "K: ",K
:Disp "R: ",R
:Stop
:Lbl E
:Input "X1? ",X
:Input "Y1? ",Y
:Input "H? ",H
:Input "K? ",K
:ClrHome
:√((X-H)²+(Y-K)²)→R
:Disp "(X - H)² + (Y - K)² = R²"
:Disp "H: ",H
:Disp "K: ",K
:Disp "R: ",R
:Stop
:Lbl F
:Input "RADIUS? ",R
:Input "H? ",H
:Input "K? ",K
:ClrHome
:Disp "(X - H)² + (Y - K)² = R²"
:Disp "H: ",H
:Disp "K: ",K
:Disp "R: ",R
:Stop
:Lbl G
:Input "X? ",X
:Input "Y? ",Y
:Input "RADIUS? ",R
:Input "H? ",H
:Input "K? ",K
:ClrHome
:√((X-H)²+(Y-K)²)→A
:If A = R:Then
:Disp "YES"
:Else:
:Disp "NO"
:Stop
```

#### Program Desc

A menu will open that looks like this:
```
CIRCLE
1:RADIUS- 2 POINTS
2:RADIUS- CENTER+POINT
3:CENTER- 2 POINTS
4:EQUATION- 2 POINTS
5:EQUATION- CENTER+POINT
6:EQUATION- CENTER+RADIUS
7:IS POINT VALID?
```
After the user picks an option, the program will skip to the code assigned to that option. Next, the program will ask for the needed variables specific to what the user wants to solve for. After that, it will clear the screen, do the necessary calculations, and then output the answer to the user.

#### Equation - Solving for . . .

<b>Radius: </b>This uses the [Distance Formula](https://en.wikipedia.org/wiki/Distance#Geometry) between two points on the circle. For the 2 points option, it is two points on the diameter and to find the radius, the distance is divided by 2 (because that will be the diameter, not the radius which is half of the diameter). When the user uses the center and a point, the program will just show the distance from the formula because that will just be the radius (distance from center to circumference).

<b>Center: </b>This uses the [Midpoint Formula](https://en.wikipedia.org/wiki/Midpoint) to find the center of the circle from the endpoints of a diameter (because the diameter is the center of the circle).

<b>Equation: </b>This uses a combination of the previous two programs to find (h,k), the center, and r², the radius. It will then show the user the form that it belongs in, [The Standard Form of a Circle](https://en.wikipedia.org/wiki/Circle#Equations).

<b>Point Validity: </b>This program will check to make sure a point is a solution to an equation of a circle. It will plug it into an equation, with the needed variables inputted by the user.