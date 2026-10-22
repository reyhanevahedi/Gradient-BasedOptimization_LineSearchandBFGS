# Gradient-BasedOptimization_LineSearchandBFGS

Unconstraint Optimization - gradient based, line search & BFGS
gradient-based optimization methods with adaptive step-size selection, employed on benchmark nonlinear problems, implemented using Wolfe-condition line search and inverse-Hessian updates for efficiency of nonlinear unconstrained optimizers. 
Project Overview:
This project implements and evaluates gradient-based optimization algorithms, including Gradient Descent with Line Search and BFGS, for solving nonlinear unconstrained optimization problems. A line search algorithm based on the Wolfe conditions was developed to select suitable step sizes, incorporating a zoom procedure to identify acceptable steps. The implementations were tested on the Rosen-brock and Powell functions to investigate convergence behavior and optimization performance.
The project analyzes objective-function values, gradient norms, and convergence patterns across iterations, comparing the methods with basic gradient descent and examining their computational efficiency. The BFGS implementation iteratively updates an approximation of the inverse Hessian matrix, enabling faster convergence without explicitly computing the full Hessian. The results highlight the benefits of line search and quasi-Newton methods for improving convergence and reducing computational effort in nonlinear optimization.

