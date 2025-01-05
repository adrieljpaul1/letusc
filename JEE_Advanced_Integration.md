# JEE Advanced Integration Techniques and Problems

## Partial Fractions
Used when the integrand is a rational function (polynomial in numerator and denominator).  

### Cases to Practice:  
1. **Proper Rational Functions**:  
   - ∫ 1/((x-1)(x+2)) dx  
   - ∫ (x+1)/(x²+x-6) dx

2. **Improper Rational Functions**:  
   (Use polynomial division to convert into proper form before decomposing)  
   - ∫ (x²+3x+2)/(x²-4x+3) dx

3. **Distinct Linear Factors in Denominator**:  
   - ∫ 1/((x+1)(x+2)) dx

4. **Repeated Linear Factors in Denominator**:  
   - ∫ 1/(x-1)² dx

5. **Irreducible Quadratic Factors in Denominator**:  
   - ∫ 1/(x²+4x+5) dx

6. **Combination of Linear and Quadratic Factors**:  
   - ∫ x²/((x²+1)(x+1)) dx

---

## Substitution Method
Substitution is useful for reducing complex integrals into simpler forms.  

### Standard Substitutions:
1. x = a sin θ for √(a² - x²)  
   - ∫ dx/√(a² - x²)  

2. x = a tan θ for √(a² + x²)  
   - ∫ dx/(a² + x²)  

3. x = a sec θ for √(x² - a²)  
   - ∫ dx/√(x² - a²)  

4. t = tan(x/2): Rationalizing trigonometric functions  
   - ∫ sin x/(1+cos x) dx

### Other Useful Substitutions:  
1. u = x^n: To reduce powers  
   - ∫ x² √(x³ + 1) dx

2. u = e^x or u = ln x: To simplify exponential/logarithmic terms  
   - ∫ ln x/x dx

3. u = sin x, cos x, e^x, ln x: Based on the problem context  
   - ∫ e^(sin x) cos x dx

---

## Integration by Parts
Used for products of functions, logarithmic terms, or when substitution doesn't simplify the integral.  

### Formula:  
∫ u v' dx = u v - ∫ v u' dx  

### Key Problems:  
1. ∫ x e^x dx: Polynomial × Exponential  
2. ∫ x² ln x dx: Polynomial × Logarithm  
3. ∫ e^x sin x dx: Exponential × Trigonometric  
4. ∫ x^n e^(-x) dx: Polynomial × Exponential  
5. ∫ ln x dx: Logarithmic (use u = ln x, v' = 1)  
6. ∫ arctan x dx: Inverse Trigonometric  
7. ∫ x^n sin(ax) dx: Polynomial × Trigonometric  
8. ∫ x^n e^(ax) dx: Polynomial × Exponential  

---

## Mixed Problems  
Many problems combine these techniques. Examples:  
1. ∫ x²/((x+1)(x²+1)) dx: Partial fractions + substitution  
2. ∫ x ln(x+1) dx: Integration by parts + substitution  
3. ∫ ln x/(x²+1) dx: Substitution + logarithms  
4. ∫ sin x/(1+cos²x) dx: Trigonometric substitution  

---

## Tricky/Advanced Integrals for JEE  
1. ∫ e^x sin x dx  
2. ∫ ln(x+1)/(x²+1) dx  
3. ∫ x³/(x²+1)² dx  
4. ∫ x² ln(1+x²) dx  
5. ∫ arctan x/(1+x²) dx  
6. ∫ dx/√(x⁴ + x²)  

