# 🧪 Lab-02 — 3 bit Universal Shift Register with 4 Operation

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

## 🧩 Circuit Diagram
Insert your Proteus schematic image here:

![Circuit Diagram](proteus/images/schematic.png)

*Explain your circuit briefly: how the inputs and outputs are connected, which ICs are used, etc.*

---

## 🔍 Simulation / Test Results
Provide screenshots or tables showing observed output.

### Test Table
| Test No | Inputs | Expected Output | Observed Output | Status |
|:--------:|:-------|:----------------|:----------------|:--------|
| 1 | A=0, B=0 | Y=0 | Y=0 | ✅ |
| 2 | A=0, B=1 | Y=1 | Y=1 | ✅ |

---

## 📊 Observations
Mention your key observations:
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
