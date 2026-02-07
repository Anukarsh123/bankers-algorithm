# 🏦 Banker's Algorithm – Deadlock Avoidance

This repository contains an implementation of **Banker’s Algorithm**, a deadlock avoidance algorithm used in **Operating Systems** to ensure safe allocation of resources to processes.

---

## 🎯 Objective
- To check whether the system is in a **safe state**
- To determine a **safe sequence** of processes
- To understand deadlock avoidance in Operating Systems

---

## 🧠 Key Concepts
- Deadlock
- Safe State
- Resource Allocation
- Need Matrix
- Available Resources
- Operating Systems

---

## 🛠️ Technology Used
- Python 3
- Command Line Interface (CLI)

---

## 📂 Project Structure

---

## ▶️ How to Run the Program
1. Clone the repository
```bash
git clone https://github.com/Anukarsh123/bankers-algorithm.git

📥 Sample InputNumber of processes: 5
Number of resources: 3

Available resources:
3 3 2

Allocation Matrix:
0 1 0
2 0 0
3 0 2
2 1 1
0 0 2

Max Matrix:
7 5 3
3 2 2
9 0 2
2 2 2
4 3 3

📤 Output

System is in a SAFE state.
Safe sequence is:
P1 → P3 → P4 → P0 → P2
