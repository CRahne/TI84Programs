# Distance Between 2 Real Numbers or Absolute Difference
```
:Disp "ABSOLUTE VALUE"
:Input "A? ",A
:If A<0:Then
:Disp "THE ABSOLUTE VALUE IS ",-A
:Else:
:Disp "THE ABSOLUTE VALUE IS ",A
```

#### Program Desc

Will input for <i>a</i>, any real number, and then calculates the absolute value by using the logic behind absolute value. This program isn't made for efficiency, rather as a visualization of the proof behind the concept.

#### Equation

The idea behind this is simple:

```
      { a, if a >= 0    }
|a| = {                 }
      { -a, if a < 0    }
```

By using some clever logic, this program is just this in TI Basic language instead of math. [Wikipedia](https://en.wikipedia.org/wiki/Absolute_value)