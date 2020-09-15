# Population Growth (Individuals)

```
:Input "BIRTHS ",B
:Input "IMMIGRANTS ",I
:Input "DEAHTS ",D
:Input "EMIGRANTS ",E
:((B+I)-(D+E))→A
:Disp "THE POPULATION GROWTH IS ",A
```

#### Program Desc

The program will ask for the varibles, calculate the answer, and then display it

#### Equation

The equation is for finding the change in individuals in a population over time:

    change = (births + immigrants) - (deaths + emigrants)

[Wikipedia](https://en.wikipedia.org/wiki/Population_growth)