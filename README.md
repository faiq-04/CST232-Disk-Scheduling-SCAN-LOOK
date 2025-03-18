
# 📄 Disk Scheduling Algorithms - SCAN vs LOOK

## 📚 Description
This project implements and compares two classic **Disk Scheduling Algorithms** — **SCAN (Elevator Algorithm)** and **LOOK Algorithm** — in Python. It is part of the **CST232 Operating Systems Assignment 2**.

The goal is to analyze and compare the **performance (seek time)** of both algorithms with different disk request sequences and directions, including graphical visualization of disk head movements.

---

## 💻 Technologies Used
- **Python**
- **Jupyter Notebook**
- **Matplotlib (for visualization)**
- OS Concepts: Disk Scheduling, Seek Time Optimization

---

## 🚀 Files Included
- `LOOK 1.ipynb`: Python implementation and visualization of the LOOK algorithm.
- `SCAN 1.ipynb`: Python implementation and visualization of the SCAN algorithm.
- `Group04_CST232W_A2.pdf`: Assignment report with detailed analysis, performance comparison, strengths, and weaknesses of both algorithms.
- `CST232-Assignment 2.pdf`: Assignment instructions (if added).
- `.ipynb_checkpoints/`: Auto-generated notebook checkpoints (can ignore).

---

## 📈 Performance Comparison Highlights (From Report)
| Algorithm | Direction | Seek Time |
|----------|----------|----------|
| **SCAN** | Right    | 314 ms   |
| **SCAN** | Left     | 268 ms   |
| **LOOK** | Right    | 292 ms   |
| **LOOK** | Left     | 260 ms   |

**Observation:** LOOK performs better in both directions due to skipping unnecessary end disk movements.

---

## 🔄 How to Run
1. Clone this repository:
```bash
git clone https://github.com/faiq-04/CST232-Disk-Scheduling-SCAN-LOOK.git
```
2. Open the `.ipynb` files in **Jupyter Notebook** or **VS Code with Python extension**.
3. Run the cells to execute the simulation and see the visualizations.

---

## 📌 Author
- Faiq Ahmed Shaikh
- Laiba Faraz
---

## 📑 Note
This repository is for **academic purposes only** and showcases Python simulation of disk scheduling algorithms as part of an Operating Systems course.

---
