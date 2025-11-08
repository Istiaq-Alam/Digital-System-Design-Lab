# 🧪 Lab-02 — 3 bit Universal Shift Register with 8 Operation

**Course:** Digital System Design Lab  
**Performed on:** 10-08-25  
**Submitted by:** [Istiak Alam]  
**Instructor:** [Afsana Sharmin Shanta]

---

## 🎯 Objectives
List the main goals of this lab:
- Understand the working of Shift Registers
- Design and simulate 3bit Universal Shift Registers

---

## 📘 Theory
There Are 3 types of Shifters -
1. Unidirectional Shifter
2. Bidirectional Shifter → Control to left to right 
3. Universal Shifter

---

## ⚙️ Components / Tools Required
| Component | Description | Quantity |
|------------|-------------|-----------|
| IC 7400 | NAND Gate | 1 |
| LED | Indicator | 3 |
| Proteus | Simulation Software | — |

---
## Operation Table : 
**Design of a 4 Bit Universal Shift Register that can Perform on :-**


| S2 | S1 | S0 | Operations       |
|:--:|--:|:--:|:-----------------|
| 0  |  0  | 0  | Data Hold        |
| 0  |  0  | 1  | Parallel Trasfer |
| 0  |  1  | 1  | Left Shift       |
| 0  |  1  | 1  | Transfer all 0   |
| 1  |  0  | 0  | Transfer all 1   |
| 1  |  0  | 1  | Data Hold        |
| 1  |  1  | 0  | Right Shift      |
| 1  |  1  | 1  | Data Hold        |


## 🧩 Circuit Diagram
<img width="1751" height="909" alt="image" src="https://github.com/user-attachments/assets/0f5e3e59-4754-441c-a684-a85a0d49b66e" />



---


---

## 📊 Observations
 key observations:
- Propagation delay observed: 500ms
- Power supply: 5V DC
- Gate response: stable with minor glitches
- Clock pulse frequency : 2hz

---



## 📚 References
- M. Morris Mano — *Digital Design*
- Proteus Design Suite Documentation ([labcenter.com](https://www.labcenter.com))
- 74LS00 Series Datasheets (TI, Nexperia)

---

## 🔗 Related Files
- **Proteus Project:** `Universal Shift Register.pdsprj`
- **Simulation Output:** `3bit.png`

---
