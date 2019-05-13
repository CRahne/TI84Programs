# Median Finder
```
:Disp "FIND THE NTH SPOT FOR THE MEDIAN"
:Input "SAMPLE SIZE ",N
:remainder(N,2)→R
:If R=1
:Then
:((N/2)+0.5)→M
:Disp "THE NTH SPOT OF THE MEDIAN IS ",M
:Else
:(N/2)→A
:Disp "THE LOWER MEDIAN IS ",A
:Disp "THE HIGHER MEDIAN IS",(A+1)
```

#### Program Desc

This program will input the sample size. The remainder will then be found between the sample size and 2. This will tell the program if it is even or not. The program will then find the nth spot of the median.

#### Equation

The median is the middle of the data. Here is a basic run-down of the logic behind the program:

```
                        { if remainder = 1: median = n/2   }
f(n) = remainder(n/2) → {                                  }
                        { else : median= n/2, (n/2) + 1    }

Where
n = sample size
median = nth spot of the median
```

[Wikipedia](https://en.wikipedia.org/wiki/Median)