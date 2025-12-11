# Introduction to Artificial Intelligence – Course Projects

This repository contains all assignments, implementations, and final project materials from the course **Introduction to Artificial Intelligence** at **Ton Duc Thang University**.  
The projects cover classical AI search, optimization, logic, and machine learning fundamentals.

# Overview
This course provides foundational concepts in Artificial Intelligence, including:

- State-space search  
- Heuristic evaluation  
- Uninformed & informed search algorithms  
- Adversarial search (Minimax & Alpha-Beta)  
- Local optimization algorithms  
- Logical reasoning & CNF  
- SAT solving  
- Machine learning with Decision Trees  

The repository includes full implementations, pseudocode, and result visualizations.

---

# 1. Search Algorithms – 8-Puzzle
We model the classic 8-puzzle with:

### ✔ State Representation
- Position of tiles (1–8 + blank)
- Initial & goal states
- Actions: Up, Down, Left, Right

### ✔ Algorithms Implemented
- **Breadth-First Search (BFS)**
- **A\* Search** with:
  - Manhattan heuristic  
  - Euclidean heuristic  

### ✔ Features
- Validity checking  
- Path reconstruction  
- Random generation of 1000 initial states  
- Comparison of BFS vs A\* performance  

---

# 2. Search & Heuristics – Pacman

We model Pacman's environment including:

- Obstacles  
- Pacman's position  
- Food pellets  
- Valid actions  

### ✔ Algorithms Implemented
- **Uniform-Cost Search (UCS)**
- **A\* Search (Manhattan & Euclidean)**

### ✔ Goal
- Eat all food items  
- Visit all four corners  
- Minimize total cost  

---

# 3. Local Search Algorithms

We explored three classical local optimization strategies on a 2D evaluation landscape:

### ✔ Algorithms
- **Random Restart Hill-Climbing**
- **Simulated Annealing**
- **Local Beam Search**

### ✔ Features
- Stateful search  
- Escape from local maxima  
- Temperature schedule for simulated annealing  
- Path visualization on 3D surface  

---

# 4. N-Queens with CNFs & SAT Solver

We solve the N-Queens problem using propositional logic:

### ✔ Steps
1. Map each board cell → a propositional variable  
2. Encode constraints:
   - One queen per row  
   - One queen per column  
   - No queens on same diagonal  
3. Convert constraints to **Conjunctive Normal Form (CNF)**  
4. Solve using **Glucose3 SAT Solver**  
5. Visualize the solved N×N board  

---

# 5. Game AI – 8x8 Tic-Tac-Toe with Alpha-Beta Pruning

A competitive game implementation where the AI plays against a human.

### ✔ Game Rules
- 8×8 board  
- Win if 4 consecutive marks (row/column/diagonal)

### ✔ AI Method
- **Minimax Search**
- **Alpha-Beta Pruning**
- Custom evaluation function:
  - Offensive streak scoring  
  - Defensive blocking heuristics  
  - Positional (zone-based) weighting  

---

# 6. Machine Learning – Decision Tree

Using dataset *dt_data.csv* containing Rank + 9 scoring attributes:

### ✔ Part 1: Information Theory Metrics
We compute:
- **Entropy**
- **Average Entropy**
- **Information Gain**

### ✔ Part 2: Decision Tree Classifier
Using Scikit-learn:
- Train/test split  
- Model training (depth=7)  
- Accuracy reports  
- Confusion matrix  
- Feature importance chart  
- Decision Tree visualization  

---

# 🛠 Technologies Used
- **Python**  
- **NumPy**, **Pandas**  
- **Matplotlib**  
- **Scikit-learn**  
- **Glucose3 (SAT Solver)**  
- **Custom AI algorithms**

---

# Team Members
| Name | Student ID | Email |
|------|-----------|--------|
| **Lý Tuấn An** | 52000620 | 52000620@student.tdtu.edu.vn |
| **Lý Tiểu Long** | 52200168 | 52200168@student.tdtu.edu.vn |
| **Giản Hoàng Huy** | 52200147 | 52200147@student.tdtu.edu.vn |
| **Huỳnh Hoài Nam** | 52200151 | 52200151@student.tdtu.edu.vn |
| **Lê Hồng Quang** | 52200156 | 52200156@student.tdtu.edu.vn |

