# Z-Score (Standard Score) Equation
```
:ClrHome
:Menu("Z-SCORE","STD DEV",A,"DATA",B,"MEAN",C,"Z",D)
:ClrHome
:Lbl A
:Input "Z ",Z
:Input "DATA ",D
:Input "MEAN ",M
:((D-M)/Z)→A
:Disp "STD DEV IS, ",A
:Stop
:Lbl B
:Input "Z ",Z
:Input "MEAN ",M
:Input "STD DEV ",S
:((Z*S)+M)→A
:Disp "DATA IS, ",A
:Stop
:Lbl C
:Input "Z ",Z
:Input "DATA ",D
:Input "STD DEV ",S
:(­(Z*S)-D)→A
:Disp "MEAN IS, ",A
:Stop
:Lbl D
:Input "MEAN ",M
:Input "DATA ",D
:Input "STD DEV ",S
:((D-M)/S)→A
:Disp "Z IS ",A
:Stop
```

#### Program Desc

It will open a menu which will prompt the user to pick an option of what they want to solve for. It will then prompt for the appropiate varibles, solve, and pick the answer.

#### Equation

The z-score is a statistical analysis of a certian value in a set of data with a normal distribution. The z-score will show the precentile of that data in relation to the mean and standard deviation. The equation is:

    z = (x - μ) / σ

    where μ = mean and σ = standard deviation

which is a complicated way of how many standard deviations fit within the distance between the data and the mean. [Wikipedia](https://en.wikipedia.org/wiki/Standard_score)