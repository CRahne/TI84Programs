# Work
```
:ClrHome
:Menu("WFD","WORK (W)",A,"FORCE (F)",B,"DISTANCE (D)",C)
:Lbl A
:Disp "SOLVING FOR WORK"
:Input "FORCE IN NEWTONS ",N
:Input "DISTANCE IN METERS ",D
:(N*D)→W
:Disp "THE WORK IN JOULES IS "
:Disp W
:Stop
:Lbl B
:Disp "SOLVING FOR FORCE"
:Input "WORK IN JOULES ",W
:Input "DISTANCE IN METERS ",D
:(W/D)→F
:Disp "THE FORCE IN NEWTONS IS "
:Disp F
:Stop
:Lbl C
:Disp "SOLVING FOR DISTANCE"
:Input "WORK IN JOULES ",W
:Input "FORCE IN NEWTONS ",F
:(W/F)→D
:Disp "THE DISTANCE IN METERS IS "
:Disp D
:Stop
```

#### Program Desc

It will open a menu which will prompt the user to pick an option of what they want to solve for. It will then prompt for the appropiate varibles, solve, and pick the answer.

#### Equation

Work is the amount of force exerted over a distance. Force can be found with [FMA](FMA.md).

[Wikipedia](https://en.wikipedia.org/wiki/Work_(physics))