# Logistic Growth

```
:Input "MAX GROWTH RATE ",R
:Input "CARRYING CAPACITY ",K
:Input "POPULATION SIZE ",N
:(R*((K-N)/K)*N)→A
:Disp "THE POPULATION GROWTH IS ",A
```

#### Program Desc

The program will ask for the needed variables and then calculate and display the answer

#### Equation

Logistic growth is the desired growth pattern of a population. It will grow at its max rate for the longest time without going over the carrying capacity. The equation is a bit more complex, but still makes sense:

                   (K - N)
    dN/dT = Rmax * ------- * N
                      K
    
Where dN/dT is a fancy way of saying growth over time, Rmax is max growth rate, K is carrying capacity, and N is population size. [Wikipedia](https://en.wikipedia.org/wiki/Population_growth)