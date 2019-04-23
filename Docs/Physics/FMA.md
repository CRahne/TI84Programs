# Force = Mass * Acceleration
```
:ClrHome
:Menu("FMA","FORCE (F)",A,"MASS (M)",B,"ACCELERATION (A)",C)
:Lbl A
:Disp "SOLVING FOR FORCE"
:Input "MASS IN KG ",M
:Input "ACC IN M/S/S",A
:(M*A)→F
:Disp "FORCE IS "
:Disp F
:Stop
:Lbl B
:Disp "SOLVING FOR MASS"
:Input "FORCE IN NEWTONS ",F
:Input "ACC IN M/S/S ",A
:(F/A)→M
:Disp "THE MASS IN KG IS "
:Disp M
:Stop
:Lbl C
:Disp "SOLVING FOR ACC"
:Input "FORCE IN NEWTONS ",F
:Input "MASS IN KG ",M
:(F/M)→A
:Disp "THE ACCELERATION IN M/S/S"
:Disp A
:Stop
```

#### Program Desc

It will open a menu which will prompt the user to pick an option of what they want to solve for. It will then prompt for the appropiate varibles, solve, and pick the answer.

#### Equation

Force for a moving object that is accelerating. Thiw would be newton's second law of motion. If you are looking for momentum, that would be [Here](PMV.md)

    F = m * a

    where F = force in newtons, m = mass in kilograms, and a = acceleration in m/s/s

[Wikipedia](https://en.wikipedia.org/wiki/Newton%27s_laws_of_motion#Newton's_second_law)