# Digital System Design Lab Task-05 
**Design a 4 Bit Arithmetic Logical Unit that can Perform on :-**
```bash
===============================================================
| S2  S1  S0 | Cin |  X   Y  | Functions                      |
===============================================================
| 0    0   0 |  1  |  A   0  | Increment A → A+1              |
| 0    0   0 |  0  |  A   0  | Transfer A → A                 |
| 0    0   1 |  0  |  A   B  | Addition → A+B                 |
| 0    1   0 |  1  |  A   B  | Addition with Carry → A+B+1    |
| 0    1   1 |  1  |  A   B' | Subtraction → A+B'+1           |
| 1    0   0 |  x  | A+B  0  | A OR B                         |
| 1    0   1 |  x  |  A   B  | A XOR B                        |
===============================================================
```
Functions : 
```bash
x = A + S2⋅S1'⋅S0⋅B
y = S1'⋅S0⋅B+S1⋅S0'⋅B'
z = S2'⋅Cin
```

*Class Task-05*