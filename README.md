# Digital System Design Lab Repository

Welcome to the **Digital System Design Lab Repository** — a complete documentation and archive for all lab tasks, circuit designs, and simulations created throughout the course.

This repository contains Proteus circuit designs, simulation results, test vector analyses, and theoretical documentation for each lab experiment performed in the **Digital System Design (DSD)** course.

---

## 🎯 Objectives
- To design, simulate, and analyze various digital circuits using **Proteus**.
- To document each lab task with detailed theory, circuit diagrams, waveforms, and conclusions.
- To maintain a structured and version-controlled record of lab experiments using **GitHub**.

---

## 🧱 Repository Structure

```
DigiSysLab/
├─ README.md                  <- This file (repository overview)
├─ .gitignore
├─ LICENSE (optional)
├─ templates/
│  └─ lab_template.md         <- markdown template for new labs
├─ assets/                    <- shared images, icons, and diagrams
└─ labs/
   ├─ 01-logic-gates/
   │  ├─ README.md            <- lab report using the template
   │  ├─ proteus/             <- Proteus design and schematic files
   │  ├─ sims/                <- simulation waveforms or animations
   │  └─ code/                <- Verilog/Arduino/Assembly code if any
   ├─ 02-flipflops/
   │  ├─ README.md
   │  └─ ...
   └─ ...
```

Each lab folder is self-contained with:
- `proteus/` → Circuit design files (`.pdsprj`, `.psd`, `.png`)
- `sims/` → Simulation outputs, timing diagrams, and waveform captures
- `code/` → Supporting code or logic implementation (if applicable)
- `README.md` → The detailed documentation of the lab (using the provided template)

---

## 🧪 How to Add a New Lab

1. Create a new folder inside `labs/` using the naming format: `NN-lab-name` (e.g., `03-multiplexer`).
2. Copy the `templates/lab_template.md` into that folder and rename it to `README.md`.
3. Add your **Proteus** project files inside `proteus/`.
4. Export schematic and simulation screenshots into respective folders.
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
- **Git & GitHub** — Version control and online documentation
- **Markdown (.md)** — For lab documentation formatting
- **Optional:** Verilog / Assembly / Arduino IDE — For programmable circuits

---

## 📘 Lab Topics Covered (Examples)
| Lab No | Title | Key Concept |
|:------:|:---------------------|:-----------------------------|
| 01 | Basic Logic Gates | AND, OR, NOT, NAND, NOR, XOR |
| 02 | Universal Gates | Implementation using NAND/NOR |
| 03 | Combinational Circuits | Half/Full Adders, Subtractors |
| 04 | Multiplexers & Demultiplexers | Data routing circuits |
| 05 | Flip-Flops | SR, D, JK, T Flip-Flops |
| 06 | Counters & Registers | Sequential circuit design |
| 07 | FSM Design | Finite State Machines |

*(Add more as you progress through your lab sessions.)*

---

## 💡 Contribution Guidelines
If you’re contributing as a team:
1. Fork the repository.
2. Create a feature branch for your lab: `feature/lab-05`.
3. Commit your changes with clear messages.
4. Open a Pull Request for review.

---

## 📂 Useful Resources
- **Proteus Documentation:** [Labcenter Electronics](https://www.labcenter.com/)
- **Digital Electronics Reference:** M. Morris Mano — *Digital Design*
- **Logic IC Datasheets:** [Texas Instruments Logic Family](https://www.ti.com/logic-circuits/overview.html)

---

## 👨‍💻 Authors / Team Members
- **Name 1** — Student ID, Department
- **Name 2** — Student ID, Department

*(Edit this section with your team details.)*

---

## 📅 Course Information
**Course:** Digital System Design Lab  
**Department:** Computer Science & Engineering (CSE)  
**Institution:** [Your University Name]  
**Semester:** [e.g., Fall 2025]

---

## 🏁 License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🌐 Repository Links
- **Live Documentation (GitHub Pages):** [View Labs](#)
- **Main Repository:** [GitHub Repo Link](#)

---

> “Design is not just what it looks like and feels like. Design is how it works.” – *Steve Jobs*

