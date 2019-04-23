# Momentum
```
:ClrHome
:Menu("FGMG","FORCE OF GRAVITY (FG)",A,"MASS (M)",B,"ACCELERATION OF GRAVITY (A)",C)
:Lbl A
:Disp "SOLVING FOR FORCE OF GRAVITY"
:Input "MASS IN KG ",M
:Input "GRAVITY ACC IN M/S/S",A
:(M*A)→F
:Disp "FORCE OF GRAVITY IS "
:Disp F
:Stop
:Lbl B
:Disp "SOLVING FOR MASS"
:Input "FORCE OF GRAVITY IN NEWTONS ",F
:Input "GRAVITY ACC IN M/S/S ",A
:(F/A)→M
:Disp "THE MASS IN KG IS "
:Disp M
:Stop
:Lbl C
:Disp "SOLVING FOR GRAVITY ACC"
:Input "GRAVITY FORCE IN NEWTONS ",F
:Input "MASS IN KG ",M
:(F/M)→A
:Disp "GRAVITY ACC IN M/S/S IS "
:Disp A
:Stop
```

#### Program Desc

It will open a menu which will prompt the user to pick an option of what they want to solve for. It will then prompt for the appropiate varibles, solve, and pick the answer.

#### Equation

Will find the momentum of a moving object. Remember that momentum is with a constant velocity. Not an acceleration, like in [FMA](FMA.md).

[Wikipedia](https://en.wikipedia.org/wiki/Momentum)