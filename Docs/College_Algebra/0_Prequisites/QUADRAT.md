# Quadrant Finder

```
:Disp "QUADRATIC"
:Prompt A
:Prompt B
:Prompt C
:ClrHome
:(­B+√(B²-4AC))/(2A)→R
:(­B-√(B²-4AC))/(2A)→P
:Disp "THE ROOTS ARE: "
:Disp R,P
```

#### Porgram Desc

This program will prompt for variables A, B, and C. It will then do the quadratic formula calculation, and finally will output what the roots are.

#### Equation

The quadratic formula is a derivative of ax² + bx + c = 0, which will return x when y = 0 in a parabola. Here is the proof:
```
             ax² + bx + c = 0
               ax² + bx = -c
           x² + (b/a)x = -(c/a)
x² + (b/a)x + (b²/4a²) = -(c/a) + (b²/4a²)
    [x + (b/2a)]² = (b² - 4ac) / 4a²
 √([x + (b/2a)]²) = +- √((b² - 4ac) / 4a²)
    x + (b/2a) = +- √((b² - 4ac) / 2a
      x = [-b +- √((b² - 4ac)] / 2a
                  or
              -b +- √((b² - 4ac))
          x = --------------------
                     2a
```

[Wikipedia](https://en.wikipedia.org/wiki/Quadratic_equation)