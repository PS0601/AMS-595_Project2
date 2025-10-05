# AMS-595_Project2
Mandelbrot Set Boundary Analysis
Project Overview

This project analyzes the upper boundary of the Mandelbrot set using numerical and polynomial methods in MATLAB.
The approach combines iterative computation, bisection search, polynomial fitting, and numerical integration to identify and approximate the fractal’s smooth upper edge.

The project is divided into four sequential tasks:

Task 1 – Escape-Time Function: Computes whether a complex point lies inside or outside the Mandelbrot set using the recurrence 
z(n+1) = z(n)^2 + c
Task 2 – Boundary Detection via Bisection: Finds the boundary points where the Mandelbrot set transitions from bounded to escaped values.

Task 3 – Polynomial Fitting: Fits a 15th-order polynomial to smooth the computed boundary and evaluates fit accuracy using RMSE.

Task 4 – Arc Length Computation: Uses numerical integration to compute the total arc length of the fitted curve.

Requirements

MATLAB R2020a or newer

The following project file:

Sachdeva_Prerna_Project02.m → runs Tasks 1–4 sequentially

How to Run

Open MATLAB and set the working directory to the folder containing Sachdeva_Prerna_Project02.m.

Run the script:

Sachdeva_Prerna_Project02


The program will:

Display numerical results for each task in the Command Window.

Plot the upper Mandelbrot boundary and the polynomial fit.

Print the polynomial coefficients, RMSE, and the computed arc length.

Notes

Re(c) and Im(c) represent the real and imaginary parts of the complex number c.

The notation 1.0e+05 * in MATLAB output means that all listed coefficients are multiplied by 10^5.
