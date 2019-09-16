# Comparison of 2 Real Numbers
```
:Disp "COMPARING 2 REAL NUMBERS"
:Input "A? ",A
:Input "B? ",B
:If (A<B):
:Then
:Disp "A < B"
:Else:
:If (A>B):
:Disp "A > B"
:Else (A=B):
:Disp "A = B"
:End
```

#### Program Desc

Program will ask for the input of two real numbers, and then compare them together. This will display the relationship

#### Explanation

All real numbers have this property called an order. With <, >,and = we denote order, thus describing a relationship between two numbers (in this case <i>a</i> and <i>b</i>). The Law of Trichotomy states that here are only three possible relationships between two real number: <i>a</i> > <i>b</i>, <i>a</i> < <i>b</i>, or <i>a</i> = <i>b</i>. This program will display the relationship derived from that law. [Wikipedia](https://en.wikipedia.org/wiki/Trichotomy_(mathematics))