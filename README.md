# Digital System Design Lab Repository

Welcome to the **Digital System Design Lab Repository** — a complete documentation and archive for all lab tasks, circuit designs, and simulations created throughout the course.

This repository contains Proteus circuit designs, simulation results, test vector analyses, and theoretical documentation for each lab experiment performed in the **Digital System Design (DSD)** course.

---

## 🎯 Objectives
- To design, simulate, and analyze various digital circuits using **Proteus**.
- To document each lab task with detailed theory, circuit diagrams, waveforms, and conclusions.
- To maintain a structured and version-controlled record of lab experiments.

---

## 🧱 Repository Structure

```
Digital-System-Design-Lab/
├─ README.md                 
├─ .gitignore
├─ LICENSE 
├─ Lab Task/
 ├─ 01-logic-gates/
 │  ├─ README.md            
 │  ├─ proteus/             
 │  ├─ sims/                             
 ├─ 02-flipflops/
 │  ├─ README.md
 │  └─ ...
 └─ ...                
└─ Lab Test/
 ├─ Lab Test-01/
 │  ├─ README.md           
 │  ├─ proteus/            
 │  ├─ sims/              
 ├─ Lab Test-02/
 │  ├─ README.md
 │  └─ ...
 └─ ...  
```

Each lab folder is self-contained with:
- `proteus/` → Circuit design files (`.pdsprj`, `.psd`, `.png`)
- `sims/` → Simulation outputs, timing diagrams, and waveform captures
- `code/` → Supporting code or logic implementation 
- `README.md` → The detailed documentation of the lab 
---

## 🧪 How to Add a New Lab

1. Create a new folder inside `Lab Task/` using the naming format: `Lab Task-NN` (e.g., `Lab Task-02`).
2. Copy the `templates/lab_template.md` into that folder and rename it to `README.md`.
3. Add your **Proteus** project files inside `proteus/`.
4. Export schematic and simulation screenshots into `sims/` folders.
5. Fill in all required details (objectives, theory, results, etc.) in the new `README.md`.
6. Commit your work with a clear message:
   ```bash
   git add .
   git commit -m "Added Lab 03 - 4x1 Multiplexer schematic and results"
   git push origin main
   ```

---

## 🧰 Tools and Technologies Used
- **Proteus Design Suite** — Circuit simulation and schematic design


---

## 📘 Lab Topics Covered 
| Lab No | Title | Key Concept |
|:------:|:---------------------|:-----------------------------|
| 01 | Parallel Adder | Implementation using Full Adder |
| 02 | Universal Shifter | Implementation using D-FlipFlop |
| 03 | Synchronous Counter | Implementation using T-FlipFlop |
| 04 | ALU Design [Arithmatic Only] | Implementation using Full Adder |
| 05 | ALU Design [Arithmatic + Logical] | Implementation using Full Adder |


*(I will Add more as I progress through my lab sessions.)*

---

## 💡 Contribution Guidelines
If you’re contributing as a team:
1. Fork the repository.
2. Create a feature branch for your lab: `feature/DSD-Lab-01`.
3. Commit your changes with clear messages.
4. Open a Pull Request for review.

---

## 📂 Useful Resources
- **Proteus Documentation:** [Labcenter Electronics](https://www.labcenter.com/)
- **Digital Electronics Reference:** M. Morris Mano — *Digital Design*
- **Logic IC Datasheets:** [Futurlec](https://www.futurlec.com/IC74LS00Series.shtml)

---

## 👨‍💻 Authors 
- **Istiaq Alam**, Department of CSE, Notre Dame Univarsity Bangladesh


---

## 📅 Course Information
**Course:** Digital System Design Lab  
**Department:** Computer Science & Engineering (CSE)  
**Institution:** Notre Dame Univaristy Bangladesh  
**Semester:** Fall 2025

---

## 🏁 License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🌐 **Live Documentation (GitHub Pages):** [View Labs](#)
---

> “Design is not just what it looks like and feels like. Design is how it works.” – *Steve Jobs*

