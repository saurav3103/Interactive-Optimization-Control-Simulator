# Optimization & Control Theory Simulator

This project is an **interactive Python simulator** designed to help students intuitively understand key concepts from **optimization theory, Lyapunov stability, and control systems**. It allows users to experiment with system parameters and visually observe convergence, instability, and failure modes in real time.

---

## 🚀 What This Simulator Does

The simulator models optimization as a **dynamical system** and visualizes how different controllers drive the system toward (or away from) an optimum.

You can:
- Visualize **gradient descent as a control law**
- Observe **Lyapunov (energy) decay**
- Study **eigenvalues, conditioning, and rotation effects**
- Compare **continuous vs discrete-time dynamics**
- Explore **nonlinear polynomial objectives**
- See **failure modes** instead of silent crashes

---

## 🧠 Mathematical Model

### Objective Functions

**Quadratic**
\[
V(x) = x^T Q x
\]

**Polynomial (Nonlinear)**
- \(x_1^4\), \(x_2^4\) curvature
- \(x_1^2 x_2^2\) coupling
- Quadratic terms

---

## 🎛️ User-Controlled Parameters

- Number of states (system dimension)
- Eigenvalues and condition number
- Rotation of the quadratic form
- Step size / learning rate
- Initial conditions
- Nonlinear curvature and coupling terms
- Failure presets (ill-conditioning, instability, saddle points)

---


## 🛠️ Tech Stack

- Python
- NumPy
- Matplotlib
- ipywidgets (interactive Jupyter UI)

---

## 🎯 Who Is This For?

- MSc students in **Systems & Control**
- Optimization and machine learning learners
- Anyone who wants intuition **beyond equations**

Especially useful for students preparing for programs like **TU Delft – Systems & Control**.

---

## 📌 How to Run

1. Open the notebook in Jupyter
2. Run the single code cell
3. Use sliders and toggles to explore system behavior interactively

---

## 📈 Learning Outcomes

- Understand stability using Lyapunov functions  
- See how eigenvalues affect convergence  
- Learn why step size matters  
- Visualize when and why optimization fails  

---

## 📎 Notes

This simulator is intended for **educational and exploratory purposes** and prioritizes conceptual understanding over numerical performance.

---

Feel free to fork, modify, and build on top of it!
