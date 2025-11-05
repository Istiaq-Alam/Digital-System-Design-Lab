**Truth table of 4 Bit Arithmetic Logical Unit that can Perform on :-**
```bash
===============================================================
| S2  S1  S0 | Cin |  X   Y  | Functions                      |
===============================================================
| 0    0   0 |  1  |  0   B  | Increment B → B+1              |
| 0    0   1 |  0  |  0   B  | Transfer B → B                 |
| 0    1   0 |  1  |  A   B' | Subtraction → A-B              |
| 0    1   1 |  0  |  A   B' | Subtraction with Borrow → A-B-1|
| 1    0   0 |  x  |  A   B  | A XOR B                        |
| 1    0   1 |  x  |  A   B' | A XNOR B                       |
===============================================================
```

## Functions : 
```bash
x = A ⋅ (S2 + S1)
y = B ⊕ [ S1 + (S2 ⋅ S0) ]
z = S2' ⋅ Cin        
F = F3 F2 F1 F0
```

## Status Flags : 
```bash
SF = F3
CF = (F3 ⋅ F2 ⋅ F1 ⋅ F0)' 
OF = S2' ⋅ Cout
ZF = (C3 ⊕ Cout) ⋅ S2'
```
