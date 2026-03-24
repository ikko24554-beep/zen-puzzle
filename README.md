# zen-puzzle
# ZenCPU Puzzle  
A minimal, interactive prototype of the **Zen‑Universe computation model**.  
This project implements:

- Zen Integer Arithmetic (Ƶ)
- Zen Gates (ADD / MUL / MAX / MIN / XOR)
- Zen Flow (value decay)
- Zen Circuit (wire routing)
- Zen Entropy (information heatmap)
- Interactive grid-based Zen CPU

All in a single HTML file.

---

## 🧠 What is ZenCPU?

**ZenCPU** is a cellular, integer‑based computational model inspired by the idea:

> “The universe does not compute with floating points.  
>  It computes with integers.”

Each cell holds a **Zen integer (0 to 2³²−1)**.  
Values flow, combine, decay, and generate entropy.  
Wires allow arbitrary routing between cells, forming circuits.

This prototype is a playground for exploring:

- integer‑only computation  
- emergent patterns  
- information flow  
- entropy dynamics  
- circuit behavior  
- early



This creates natural gradients and prevents runaway growth.

---

## 🔌 Zen Circuit (Wires)

Wires are directional connections:





A cell may receive multiple inputs.  
If more than two exist, Zen‑Universe rules apply:

- Use the **maximum** and **minimum** values  
- Discard the rest  

This produces stable, interpretable behavior.

---

## 🧪 Zen Entropy

Entropy is computed per cell:

