# 🧭 A Deep Dive into the Travelling Salesman Problem: From Branch and Bound to Heuristics

## 📘 Overview
This project explores and compares four algorithmic approaches to solving the **Travelling Salesman Problem (TSP)** — one of the most well-known NP-hard problems in computer science.  
The study evaluates the performance, efficiency, and scalability of:
- 🔹 **Branch and Bound (B&B)**
- 🐜 **Ant Colony Optimization (ACO)**
- 🧬 **Evolutionary Algorithm (EA)**
- ❄️ **Simulated Annealing (SA)**

The project involves both theoretical and experimental analysis using Python implementations, alongside insights from recent research (2020–2025). The findings contribute toward developing hybrid optimization strategies for real-world routing applications such as logistics, robotics, and emergency response systems.

This project was developed as part of the **Algorithm Design and Analysis (TDA6323)** course.

---

## 👥 Collaborators
| No | Student ID | Name 
|----|------|-------------
| 1 | 1221301131 | MUHAMMAD ARIFF RIDZLAN BIN MOHD FAUDZI
| 2 | 1211103754 | NOOR ALIA ALISA BINTI KAMAL
| 3 | 1211101082 | LOW WEI JIE
| 4 | 1221301143 | MUHAMMAD NABIL IRFAN BIN ROSLI

---

## 🎯 Objectives
1. ⚙️ Analyze and compare classical and heuristic algorithms for solving TSP.  
2. ⏱️ Evaluate algorithm performance based on accuracy, speed, and scalability.  
3. 🔍 Identify each algorithm’s strengths, weaknesses, and ideal use cases.  
4. 🤖 Propose a hybrid framework integrating multiple algorithms for enhanced performance.

---

## 🧩 Algorithms Studied
### 🔹 1. Branch and Bound (B&B)
- Provides **exact optimal solutions**.
- Efficient for small to medium datasets.
- Slows exponentially with large problem sizes.

### 🐜 2. Ant Colony Optimization (ACO)
- Inspired by **foraging behavior of ants**.
- Excels in **exploration and adaptability**.
- Sensitive to parameter tuning (pheromone, evaporation rate).

### 🧬 3. Evolutionary Algorithm (EA)
- Based on **genetic and evolutionary principles** (selection, crossover, mutation).
- Strong global search capability.
- Can be hybridized with machine learning or reinforcement learning.

### ❄️ 4. Simulated Annealing (SA)
- Inspired by **thermal annealing in metallurgy**.
- Efficient in avoiding local minima.
- Simple yet powerful for large-scale optimization.

---

## 📊 Results Summary
| Algorithm | Accuracy | Speed | Scalability | Strengths | Weaknesses |
|------------|-----------|--------|--------------|------------|-------------|
| 🔹 B&B | ⭐⭐⭐⭐⭐ | ⭐⭐☆☆☆ | ⭐☆☆☆☆ | Exact optimal solution | Exponential runtime |
| 🐜 ACO | ⭐⭐⭐⭐☆ | ⭐⭐⭐☆☆ | ⭐⭐⭐⭐☆ | Adaptive and robust | Parameter sensitive |
| 🧬 EA | ⭐⭐⭐⭐☆ | ⭐⭐⭐⭐☆ | ⭐⭐⭐⭐☆ | Strong convergence | May stagnate |
| ❄️ SA | ⭐⭐⭐☆☆ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐☆☆ | Fast convergence | May yield suboptimal results |

---

## 🧠 Key Findings
- ✅ **B&B** works best for small-scale, exact TSP instances.  
- 🐜 **ACO** balances exploration and exploitation effectively.  
- 🧬 **EA** adapts well when combined with hybrid or learning-based approaches.  
- ❄️ **SA** provides fast, near-optimal results with minimal tuning.  
- 💡 Proposed **CADTO** framework combines ACO, EA, and SA for real-time applications.
