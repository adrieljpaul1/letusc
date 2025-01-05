
# JEE Advanced Integration Techniques and Problems

## Partial Fractions
Used when the integrand is a rational function (polynomial in numerator and denominator).  

### Cases to Practice:  
1. **Proper Rational Functions**:  
   - \( \int \frac{1}{(x-1)(x+2)} dx \)  
   - \( \int \frac{x+1}{(x^2+x-6)} dx \)

2. **Improper Rational Functions**:  
   (Use polynomial division to convert into proper form before decomposing)  
   - \( \int \frac{x^2+3x+2}{x^2-4x+3} dx \)

3. **Distinct Linear Factors in Denominator**:  
   - \( \int \frac{1}{(x+1)(x+2)} dx \)

4. **Repeated Linear Factors in Denominator**:  
   - \( \int \frac{1}{(x-1)^2} dx \)

5. **Irreducible Quadratic Factors in Denominator**:  
   - \( \int \frac{1}{x^2+4x+5} dx \)

6. **Combination of Linear and Quadratic Factors**:  
   - \( \int \frac{x^2}{(x^2+1)(x+1)} dx \)

---

## Substitution Method
Substitution is useful for reducing complex integrals into simpler forms.  

### Standard Substitutions:
1. \( x = a \sin \theta \) for \( \sqrt{a^2 - x^2} \)  
   - \( \int \frac{dx}{\sqrt{a^2 - x^2}} \)  

2. \( x = a \tan \theta \) for \( \sqrt{a^2 + x^2} \)  
   - \( \int \frac{dx}{a^2 + x^2} \)  

3. \( x = a \sec \theta \) for \( \sqrt{x^2 - a^2} \)  
   - \( \int \frac{dx}{\sqrt{x^2 - a^2}} \)  

4. \( t = \tan(x/2) \): Rationalizing trigonometric functions.  
   - \( \int \frac{\sin x}{1+\cos x} dx \)

### Other Useful Substitutions:  
1. \( u = x^n \): To reduce powers.  
   - \( \int x^2 \sqrt{x^3 + 1} dx \)

2. \( u = e^x \) or \( u = \ln x \): To simplify exponential/logarithmic terms.  
   - \( \int \frac{\ln x}{x} dx \)

3. \( u = \sin x, \cos x, e^x, \ln x \): Based on the problem context.  
   - \( \int e^{\sin x} \cos x dx \)

---

## Integration by Parts
Used for products of functions, logarithmic terms, or when substitution doesn't simplify the integral.  

### Formula:  
\[ \int u v' \,dx = u v - \int v u' \,dx \]  

### Key Problems:  
1. \( \int x e^x dx \): Polynomial × Exponential  
2. \( \int x^2 \ln x dx \): Polynomial × Logarithm  
3. \( \int e^x \sin x dx \): Exponential × Trigonometric  
4. \( \int x^n e^{-x} dx \): Polynomial × Exponential  
5. \( \int \ln x dx \): Logarithmic (use \( u = \ln x \), \( v' = 1 \))  
6. \( \int \arctan x dx \): Inverse Trigonometric  
7. \( \int x^n \sin(ax) dx \): Polynomial × Trigonometric  
8. \( \int x^n e^{ax} dx \): Polynomial × Exponential  

---

## Mixed Problems  
Many problems combine these techniques. Examples:  
1. \( \int \frac{x^2}{(x+1)(x^2+1)} dx \): Partial fractions + substitution.  
2. \( \int x \ln(x+1) dx \): Integration by parts + substitution.  
3. \( \int \frac{\ln x}{x^2+1} dx \): Substitution + logarithms.  
4. \( \int \frac{\sin x}{1+\cos^2 x} dx \): Trigonometric substitution.  

---

## Tricky/Advanced Integrals for JEE  
1. \( \int e^x \sin x dx \)  
2. \( \int \frac{\ln(x+1)}{x^2+1} dx \)  
3. \( \int \frac{x^3}{(x^2+1)^2} dx \)  
4. \( \int x^2 \ln(1+x^2) dx \)  
5. \( \int \frac{\arctan x}{1+x^2} dx \)  
6. \( \int \frac{dx}{\sqrt{x^4 + x^2}} \)  
