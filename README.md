# Study of Successive Over-Relaxation (SOR) Method

## 📌 Project Overview

This project is a mathematical study of the **Successive Over-Relaxation (SOR) method**, an iterative numerical technique used to solve systems of linear equations.

The project focuses on the **convergence properties, convergence rate, applications, advantages, disadvantages, and types of the SOR method**. It also studies how the relaxation factor **ω (omega)** influences the convergence of the iterative process.

The study compares SOR with classical and iterative methods such as **Matrix Inversion, Gauss Elimination, Gauss-Jordan, Jacobi, and Gauss-Seidel methods**.

## 🎯 Objectives

- Study the Successive Over-Relaxation (SOR) method.
- Understand the mathematical formulation of SOR.
- Study convergence and convergence rate.
- Understand the importance of the relaxation factor ω.
- Compare SOR with other methods for solving linear systems.
- Study applications of SOR in scientific and engineering problems.
- Analyze the advantages and limitations of the method.
- Examine different variations of the SOR method.

## 🧮 Mathematical Background

A system of linear equations can be represented in matrix form as:

**Ax = b**

The SOR method improves the Gauss-Seidel iteration by introducing a relaxation factor **ω**.

The project presents the SOR iteration in the form:

**x⁽ᵏ⁺¹⁾ = x⁽ᵏ⁾ + ω(x⁽ᵏ⁺¹⁾ − x⁽ᵏ⁾)₍GS₎**

where:

- **x⁽ᵏ⁾** = current approximation
- **x⁽ᵏ⁺¹⁾** = next approximation
- **ω** = relaxation factor
- **GS** = Gauss-Seidel correction

When **ω = 1**, the method reduces to the Gauss-Seidel method. The project discusses the commonly considered range **0 < ω < 2** and the importance of selecting a suitable value for faster convergence.

## 🔬 Convergence Study

The project studies the conditions that affect convergence, including:

- Diagonal dominance or symmetry
- Symmetric positive-definite matrices
- Matrix properties
- Initial guess
- Spectral radius
- Choice of relaxation factor

For suitable systems, an appropriate relaxation factor can significantly improve the convergence rate.

## 🌡️ Application: Heat Equation

One of the applications studied in the project is a **two-dimensional heat equation problem**.

A **0.9 × 0.9 m plate** with boundary temperatures of **273 Kelvin** is considered. The finite difference method is used to formulate the resulting system of equations, and SOR is applied to obtain an approximate solution.

The report uses MATLAB for the computational example and discusses the resulting solution and errors.

## 📊 Example Comparison

For one example system:

```text
2x + y = 1
x + 7y = 5
```

The exact solution reported in the project is approximately:

```text
x = 0.153846153846154
y = 0.692307692307692
```

The project reports the following iteration counts:

| Method | Number of Iterations |
|---|---:|
| Jacobi | 15 |
| Gauss-Seidel | 8 |
| SOR | 6 |

This example demonstrates the faster convergence obtained by SOR for the selected problem and relaxation parameter.

## ⚙️ Computational Tool

The project uses:

- **MATLAB**
- Numerical linear algebra
- Iterative methods
- Finite Difference Method (FDM)

The report notes that the SOR implementation for the heat-equation example took approximately **0.084 seconds**, while MATLAB's built-in functions produced the exact solution in approximately **0.020 seconds** for the particular example studied.

## 📚 Applications of SOR

The project discusses applications of SOR in areas including:

- Finite Element Analysis (FEA)
- Computational Fluid Dynamics (CFD)
- Electromagnetic field simulation
- Structural analysis
- Heat transfer
- Quantum mechanics
- Image processing
- Optimization
- Financial modeling
- Boundary value problems
- Laplace's equation
- Poisson's equation

## ✅ Advantages

According to the project, important advantages of SOR include:

- Faster convergence than basic Gauss-Seidel in suitable cases
- Efficiency for large and sparse systems
- Control over convergence through the relaxation factor
- Flexibility for different matrix structures
- Relatively simple implementation
- Lower memory requirements than some direct approaches
- Usefulness in numerical solutions of partial differential equations

## ⚠️ Disadvantages

The project also identifies several limitations:

- Performance depends strongly on the choice of relaxation factor.
- An unsuitable relaxation factor can result in slow convergence or divergence.
- Convergence can depend on the initial guess.
- SOR is not equally effective for every matrix.
- Determining an optimal relaxation factor can be difficult for large systems.
- Implementation requires careful management of the relaxation parameter.
- Performance depends on matrix properties such as spectral radius.

## 🔄 Types of SOR Discussed

The project discusses the following variations:

1. Standard SOR (Classical SOR)
2. Symmetric SOR (SSOR)
3. Line SOR (LSOR)
4. Incomplete SOR (ISOR)
5. Parallel SOR
6. Gauss-Seidel with Over-Relaxation (GSOR)

## 📖 Project Structure

The project report is organized into three main chapters:

### Chapter 1 – Introduction to SOR

- Introduction
- Convergence and convergence rate
- Applications of SOR
- Importance of SOR

### Chapter 2 – Linear Systems of Equations

- Methods of solution
- Matrix inversion
- Gauss elimination
- Gauss-Jordan method
- Cholesky's triangularisation
- Crout's method
- Jacobi iteration
- Gauss-Seidel iteration
- Comparison of SOR with other methods

### Chapter 3 – Successive Over-Relaxation Method

- Definition and derivation
- Convergence of SOR
- Advantages
- Disadvantages
- Types of SOR
- Conclusion

## 📄 Project Report

The complete project report is available in this repository:

**[View the SOR Project Report – SOR_2024.pdf](SOR_2024.pdf)**

## 🎓 Academic Information

**Project Title:** Study of Successive Over-Relaxation (SOR) Method

**Author:** Anusha

**Degree:** Master of Science in Mathematics

**Department:** Department of Mathematics

**Institution:** Dr. G. Shankar Government Women's First Grade College and PG Study Centre, Ajjarkad, Udupi

**University:** Mangalore University

**Supervisor:** Dr. Ravisha M.

**Academic Year:** 2023–24

## 🏁 Conclusion

The project concludes that the Successive Over-Relaxation method is an effective iterative technique for solving linear systems, particularly large and sparse systems. Its main advantage is the ability to accelerate convergence through a suitable relaxation parameter.

The study also shows, through examples, that SOR can require fewer iterations than Jacobi and Gauss-Seidel methods when an appropriate relaxation factor is selected. At the same time, the project highlights that choosing the relaxation parameter is important because an unsuitable value can lead to poor convergence.

## 👩‍💻 Author

**Anusha**

Master of Science in Mathematics

