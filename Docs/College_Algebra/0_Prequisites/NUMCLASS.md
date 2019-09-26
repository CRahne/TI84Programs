# Number Classicifcation (Janky)

```
:Input "REAL NUMBER? ",N
:If remainder(N,1)=0:Then
:Disp "NUMBER IS INTEGER"
:If remainder(N,1)=0 and N≥0:Then
:Disp "NUMBER IS WHOLE"
:If remainder(N,1)=0 and N>0:Then
:Disp "NUMBER IS NATURAL"
:Else
:Disp "NUMBER IS RATIONAL"
```

#### Program Desc

It will ask for a number, and then will say what kind of number it is. Except if it is irrational. The calculator will then flip out at you. The reason why it isn't fixed was because this was an exercise for learning if statements in TI Basic.

#### Equation

Classification isn't hard just weird.

```
            Real Numbers                          - No imaginary numbers
            /          \ 
        Irrational   Rational                     - Able to be put in a fraaction
                     /      \
              Integers      Whole Numbers         - Equal to or greater than zero 
                                 |
                          Natural Numbers         - Greater than zero
                        
```

[Wikipedia](https://en.wikipedia.org/wiki/Number)