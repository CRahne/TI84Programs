# Margin of Error for Advanced Algebra
```
:Disp "MARGIN OF ERROR"
:Input "X (DATA) ",X
:Input "SAMPLE SIZE ",N
:ClrHome
:(X/N)→P
:(1.96*√((P*(1-P))/N)→E
:Disp "THE SAMPLE PROPORTION IS",P
:Disp "THE MARGIN OF ERROR IS ",E,"AND",­E
:Disp "THE CONFIDENCE INTERVAL IS"
:P+E→H
:Disp H
:P-E→X
:Disp X
:Pause 
:ClrHome
:Disp "WE ARE 95% CONFIDENT THAT"
:Disp "THE INTERVAL FROM (",H,E
:Disp ") CAPTURES THE TRUE"
:Disp "PROPORTION OF"
```

#### Program Desc

Will prompt for the specific values. It will do some calulations, and then display all answers to those calculations and what they are. It will then clear that screen, and then print out an example of how to write this data out.

#### Equation

The Margin of Error is an equation that calculates the average error in the data calculated. It is often included in large sets of data like polls and surveys. [Wikipedia](https://en.wikipedia.org/wiki/Margin_of_error)