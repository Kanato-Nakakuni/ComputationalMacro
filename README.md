<p align="center">
  <a href="Lecture%20notes/Lec02_TwoPeriod.ipynb"><img src="Lecture%20notes/figures/lec02-analytical-numerical.svg" alt="Numerical and analytical saving policies" width="49%"></a>
  <a href="Lecture%20notes/Lec07_InfiniteHorizon.ipynb"><img src="Lecture%20notes/figures/lec10-value-function-iteration.svg" alt="Value-function convergence over iterations" width="49%"></a>
</p>

# Computational Macroeconomics — University of Mannheim

This repository contains code and lecture materials for the *Computational Macroeconomics* course in the Master's program at the University of Mannheim (Fall 2026).

See the [syllabus](Syllabus.pdf) for course information.

## Contents

- **[Lec01_Introduction.pdf](Lecture%20notes/Lec01_Introduction.pdf)**

  Course introduction.

- **[Lec01_JuliaPrimer.ipynb](Lecture%20notes/Lec01_JuliaPrimer.ipynb)**

  Reviews essential Julia programming concepts used to solve macroeconomic models, including loops, functions, conditionals, plotting, and discretization.

- **[Lec02_TwoPeriod.ipynb](Lecture%20notes/Lec02_TwoPeriod.ipynb)**

  Solves a two-period consumption-saving model to demonstrate core solution techniques in computational macroeconomics:

  - Grid search
  - Endogenous Grid Method (EGM)
  - Projection method

- **[Lec03_MultiPeriod.ipynb](Lecture%20notes/Lec03_MultiPeriod.ipynb)**

  Introduces a multi-period lifecycle model and solves it using backward induction. Exercises explore how function-based code and efficient grid search improve performance.

- **[Lec04_GE.ipynb](Lecture%20notes/Lec04_GE.ipynb)**

  Computes stationary general equilibrium in a lifecycle model with public pensions. Counterfactual experiments examine demographic changes and pension reforms, including welfare analysis using consumption-equivalent variation.

- **[Lec05_Calibration.ipynb](Lecture%20notes/Lec05_Calibration.ipynb)**

  Introduces calibration, distinguishing externally set parameters from internally calibrated parameters. Covers target selection, loss functions, identification, and the sensitivity of counterfactual results to parameter choices.

- **[Lec06_Transition.ipynb](Lecture%20notes/Lec06_Transition.ipynb)**

  Explains how to solve transitional dynamics following an education subsidy reform in a two-period model with endogenous human capital. Discusses aggregate transition paths, cohort welfare, and extensions to multi-period models.

- **[Lec07_InfiniteHorizon.ipynb](Lecture%20notes/Lec07_InfiniteHorizon.ipynb)**

  Formulates the infinite-horizon consumption-saving problem recursively and implements value function iteration (VFI) and policy function iteration (PFI).

- **[Lec08_Aiyagari.ipynb](Lecture%20notes/Lec08_Aiyagari.ipynb)**

  Introduces the Aiyagari model with uninsurable income risk and borrowing constraints. Covers stationary equilibrium, Tauchen's method for discretizing an AR(1) income process, and invariant distributions. Exercises examine wealth taxation, redistribution, and welfare.

- **[Lec09_NumericalMethod.pdf](Lecture%20notes/Lec09_NumericalMethod.pdf)**

  Lecture slides on numerical methods.

- **[Lec09_NumericalMethod_Ex.ipynb](Lecture%20notes/Lec09_NumericalMethod_Ex.ipynb)**

  Applies root finding (bisection and Newton–Raphson), optimization (golden-section search and Newton's method), and grid search to a static consumption–leisure problem.

## Assignment and exam materials

- [Assignment](Lecture%20notes/Assignment%20and%20exam/Assignment.ipynb)
- [Exam preparation](Lecture%20notes/Assignment%20and%20exam/Exam_prep.pdf)
- [Sample exam](Lecture%20notes/Assignment%20and%20exam/Sample_exam.pdf)
