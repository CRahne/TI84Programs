# Finding Nth Number in a Arithmetic Sequence

```
:Disp "FIND NTH NUMBER"
:Input "N ",N
:Input "FIRST NUMBER ",A
:Input "COMMEN DIFFERENCE ",D
:Disp ((D*(N-1))+A)
```

#### Program Description

Asks for the needed variables - First Number, N, and the common difference. Then it will show the wanted number.


#### Equation

The equation is:
```
aN = a1 + (n-1)d

aN is the Nth Number
a1 is the first number in the sequence
n is the desired slot
d is the difference
```

What does this look similar too? If you guessed ```y = mx + b```, or slope intercept form, you would be correct. Think about it, ```a1``` is the y-intercept, ````d```` is the slope, ```n``` is the x variable, and ```aN``` is the y variable. All we change in this equation is that it is n-1 because then we don't add an extra common difference for the initial value's place. [Wikipedia](https://en.wikipedia.org/wiki/Arithmetic_progression)