# Lab Template — Digital System Design Lab

Use this Markdown file as a template for documenting each lab. Copy it into your lab folder as `README.md` and update the placeholders accordingly.

---

## 🧪 Lab NN — [Lab Title]

**Course:** Digital System Design Lab  
**Performed on:** YYYY-MM-DD  
**Submitted by:** [Your Name(s)]  
**Instructor:** [Instructor Name]

---

## 🎯 Objectives
List the main goals of this lab:
- Understand the working of …
- Design and simulate …
- Measure and analyze …

---

## 📘 Theory
Briefly explain the theoretical background of the experiment. Include:
- Logic equations
- Truth tables
- Timing diagrams or state tables (if applicable)

Example:
```
Y = A'B + AB'
```
| A | B | Y |
|:-:|:-:|:-:|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

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

## 🧠 Procedure
Describe the steps you followed during the experiment:
1. Create a new project in Proteus.
2. Place the required ICs and components.
3. Connect input switches and output LEDs.
4. Simulate and observe the logic behavior.

---

## 🔍 Simulation / Test Results
Provide screenshots or tables showing observed output.

### Waveform / Simulation Output
![Simulation](sims/waveform1.png)

### Test Table
| Test No | Inputs | Expected Output | Observed Output | Status |
|:--------:|:-------|:----------------|:----------------|:--------|
| 1 | A=0, B=0 | Y=0 | Y=0 | ✅ |
| 2 | A=0, B=1 | Y=1 | Y=1 | ✅ |

---

## 📊 Observations
Mention your key observations:
- Propagation delay observed: xx ns
- Power supply: 5V DC
- Gate response: stable with minor glitches

---

## ✅ Conclusion
Summarize your findings:
> In this lab, we successfully designed and simulated [circuit name]. The output matched theoretical results and verified the logic equation.

---

## ⚠️ Problems Faced & Solutions
| Problem | Solution |
|----------|-----------|
| Simulation not running | Checked wiring and power sources |
| Wrong output | Replaced incorrect IC with 74LS86 |

---

## 📚 References
- M. Morris Mano — *Digital Design*
- Proteus Design Suite Documentation ([labcenter.com](https://www.labcenter.com))
- 74LS00 Series Datasheets (TI, Nexperia)

---

## 🔗 Related Files
- **Proteus Project:** `proteus/schematic.psz`
- **Simulation Output:** `sims/waveform1.png`
- **Code (if any):** `code/` folder

---

## 🧾 Version Info
- Commit: `commit-hash`
- Last Updated: `YYYY-MM-DD`

> *Keep your documentation clean and visual — add as many images or timing diagrams as possible.*

