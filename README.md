# Numerical Analysis and Algorithmic Methods: Part 2

This repository contains the second part of the laboratory notebook sequence, focusing on the direct, programmatic execution of core numerical analysis routines. The codebase transitions foundational mathematical concepts into fully automated, interactive Python scripts developed within Google Colab.

## Core Characteristics

* **Code-Driven Architecture:** The workspace minimizes theoretical definitions to prioritize logical execution, operational script code, and algorithmic runtime structures.
* **Dynamic Dataset Inputs:** Each module features interactive console input mechanisms, allowing for real-world parameter updates and live data validation.
* **Graphical Visualizations:** All algorithmic outputs are paired with dedicated matplotlib graphics to track convergence vectors, interpolation boundaries, and structural trajectories visually.



## Repository Contents and Module Roadmap

The notebook is systematically organized into specific numerical modules:

### 1. Root Optimization & Boundary Analysis
* **Generalized Newton's Method:** Designed to locate multiple roots and maintain ideal quadratic convergence profiles by modifying standard derivative formulas.
* **Finite Difference Vectoring:** Approximating boundary slopes using Forward, Backward, and Central difference formulas to evaluate error scaling.

### 2. Data Interpolation & Curve Approximation
* **Equally Spaced Formulations:** Implementations of Newton's (Forward/Backward), Gauss (Forward/Backward), and Stirling's central difference algorithms.
* **Unequally Spaced Formulations:** Lagrange’s interpolation and Inverse Interpolation techniques to calculate dependent or independent grid targets across uneven parameters.

### 3. Statistical Trend Fitting
* **Power Regression Modeling:** Linearizing non-linear dynamics to solve expressions of the form $y = ax^b$.
* **Exponential Regression Modeling:** Fitting data to exponential configurations ($y = ae^{bx}$) using least-squares matrix systems.

### 4. Numerical Calculus & Ordinary Differential Equations
* **Definite Integration Stencils:** Higher-order area calculations utilizing the Trapezoidal Rule alongside Simpson’s 1/3 and 3/8 Rules.
* **Marching ODE Solvers:** State tracking using the Predictor-Corrector Modified Euler method and the high-fidelity 4th-Order Runge-Kutta (RK4) algorithm.

### 5. Multi-Dimensional Grid Field Simulations (PDEs)
* **Parabolic Systems:** Explicit FTCS finite-difference modeling of the 1D Heat Equation.
* **Hyperbolic Systems:** CFL-constrained boundary modeling of the 1D Wave Equation.
* **Elliptic Systems:** Gauss-Seidel iterative relaxation solutions via the 4-Point Liebmann Stencil for the 2D Laplace Equation.



## Execution Instructions

To execute the code blocks, open the notebook inside a Google Colab instance or a Jupyter environment supporting standard data science libraries:

```bash
# Core mathematical and visualization libraries required
pip install numpy matplotlib
