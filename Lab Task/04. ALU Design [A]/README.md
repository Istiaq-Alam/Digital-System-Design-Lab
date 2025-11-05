# Digital System Design Lab Task-04
## Design a 4 Bit Arithmetic Logical Unit that can Perform on - 
## Truth Table : 

| S2 | S1 | S0 | Cin |  X  |  Y  | Functions                  |
|:--:|:--:|:--:|----:|:---:|:---:|:---------------------------:|
| 0 | 0 | 0 | 0 | A | 0 | Transfer A → A                 |
| 0 | 0 | 0 | 1 | A | 0 | Increment A → A+1              |
| 0 | 0 | 1 | 0 | A | B | Addition → A+B                 |
| 0 | 0 | 1 | 1 | A | B | Addition with Carry → A+B+1    |
| 0 | 1 | 0 | 0 | A | B' | Subtraction with Borrow → A-B-1|
| 0 | 1 | 0 | 1 | A | B' | Subtraction → A+B'+1           |
| 0 | 1 | 1 | 0 | A | all 1 | Decrement A → A-1              |
| 0 | 1 | 1 | 1 | A | all 1 | Transfer with Carry            |


## Function : 
```bash

```

## Circuit in Proteus : 
<img width="1229" height="860" alt="image" src="https://github.com/user-attachments/assets/92191728-abfd-4f06-9977-a720a7143aa4" />
