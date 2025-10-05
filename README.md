# AMS-595_Project2

## **Project Overview**  
This project analyzes the **the Mandelbrot set** using numerical and polynomial methods in **MATLAB**.  
The approach combines **iterative computation**, **bisection search**, **polynomial fitting**, and **numerical integration** to identify and approximate the fractal’s smooth upper edge.  

The project is divided into four sequential tasks:  
1. **Task 1 – Fractal Function:** Determines whether a complex point lies inside or outside the Mandelbrot set using the iterative relation `z(n+1) = z(n)^2 + c`.  
2. **Task 2 – Boundary Detection via Bisection:** Finds the boundary points where the Mandelbrot set transitions from bounded to escaped values.  
3. **Task 3 – Polynomial Fitting:** Fits a 15th-order polynomial to smooth the computed boundary and evaluates fit accuracy using RMSE.  
4. **Task 4 – Arc Length Computation:** Uses numerical integration to compute the total arc length of the fitted curve.  

---

## **Requirements**  
- **MATLAB R2020a or newer**  
- Project file included in this repository:  
  - `Sachdeva_Prerna_Project02.m` → runs **Tasks 1–4** sequentially  

---

## **How to Run**  

### **All Tasks (1–4)**  
1. Open **MATLAB** and set your working directory to the folder containing the script.  
2. Run:  
   ```matlab
   Sachdeva_Prerna_Project02
   ```  
3. The program will:  
   - Display numerical outputs for each task in the **Command Window**.  
   - Plot the **upper Mandelbrot boundary** and the **polynomial fit**.  
   - Print the **polynomial coefficients**, **RMSE**, and the **computed arc length**.  

---

## **Notes**  
- `Re(c)` and `Im(c)` represent the **real** and **imaginary** parts of the complex number `c`.  
- The notation `1.0e+05 *` in MATLAB output means that **all listed coefficients are multiplied by 10⁵**, which is MATLAB’s standard **scientific-notation format**.  
