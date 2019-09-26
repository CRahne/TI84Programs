# Automatic Foiler
```
:Disp "FORM: (AX+B)(CX+D)"
:Prompt A
:Prompt B
:Prompt C
:Prompt D
:(A*C)→E
:((B*C)+(D*A))→F
:(B*D)→G
:ClrHome
:Disp "FORM: AX²+BX+C"
:Disp "A=",E
:Disp "B=",F
:Disp "C=",G
```

#### Program Desc

It will prompt the user to fill the format of (AX+B)(CX+D) and then display in the format of AX²+BX+C.

#### Equation

The algorithm behind this is simple:

```
              PURE ALG                                    ARITH
           (AX+B) * (CX+D)            |                  11 * 12
         AX(CX+D) + B(CX+D)           |              (10+1) * (10+2)
 (AX*CX) + (AX*D) + (B*CX) + (B*D)    |    (10*10) + (10*2) + (1*10) + (1*2)
 (A*C)X² + (A*D)X + (B*C)X + (B*D)    |        (100) + (20) + (10) + (2)
(A*C)X² + [(A*D) + (B*C)]X + (B*D)    |                    132

ALGORITHM:

(A*C) = A
[(B*C) + (D*A)] = B
(B*D) = C

AND:

AX²+BX+C
```

This proof above shows how this algorithm works. This makes it easy for algebra classes with dealing with quadratics. [Wikipedia](https://en.wikipedia.org/wiki/FOIL_method)