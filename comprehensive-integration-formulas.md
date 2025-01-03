# Comprehensive Integration Formulas Guide

## 1. Standard Forms with Parameters
1. ∫ (ax + b)ⁿ dx = (ax + b)ⁿ⁺¹/[a(n+1)] + C, n ≠ -1
2. ∫ 1/(ax + b) dx = (1/a)ln|ax + b| + C
3. ∫ 1/(ax² + bx + c) dx:
   - For b² - 4ac > 0: (2/√(b² - 4ac))ln|(2ax + b - √(b² - 4ac))/(2ax + b + √(b² - 4ac))| + C
   - For b² - 4ac < 0: (2/√(4ac - b²))tan⁻¹((2ax + b)/√(4ac - b²)) + C
4. ∫ 1/√(ax² + bx + c) dx = ln|2(√(ax² + bx + c)) + 2ax + b| + C

## 2. Exponential and Logarithmic Forms
1. ∫ xᵃ(ln x)ⁿ dx = xᵃ⁺¹(ln x)ⁿ/(a+1) - (n/(a+1))∫ xᵃ(ln x)ⁿ⁻¹ dx
2. ∫ eᵃˣ(sin bx) dx = eᵃˣ(a sin bx - b cos bx)/(a² + b²) + C
3. ∫ eᵃˣ(cos bx) dx = eᵃˣ(a cos bx + b sin bx)/(a² + b²) + C
4. ∫ xᵃeᵇˣ dx = (xᵃeᵇˣ/b) - (a/b)∫ xᵃ⁻¹eᵇˣ dx
5. ∫ ln(ax) dx = x ln(ax) - x + C
6. ∫ xln(ax) dx = (x²/2)(ln(ax) - 1/2) + C

## 3. Trigonometric Products and Powers
1. ∫ sinⁿx cosᵐx dx (various cases):
   - For n odd: Let n = 2k+1, substitute u = cos x
   - For m odd: Let m = 2k+1, substitute u = sin x
   - For both even: Use double angle formulas
2. ∫ sin(mx)sin(nx) dx = -cos((m+n)x)/(2(m+n)) - cos((m-n)x)/(2(m-n)) + C
3. ∫ cos(mx)cos(nx) dx = sin((m+n)x)/(2(m+n)) + sin((m-n)x)/(2(m-n)) + C
4. ∫ sin(mx)cos(nx) dx = -sin((m+n)x)/(2(m+n)) + sin((m-n)x)/(2(m-n)) + C

## 4. Inverse Trigonometric Forms
1. ∫ sin⁻¹(x) dx = x sin⁻¹(x) + √(1-x²) + C
2. ∫ cos⁻¹(x) dx = x cos⁻¹(x) - √(1-x²) + C
3. ∫ tan⁻¹(x) dx = x tan⁻¹(x) - (1/2)ln(1+x²) + C
4. ∫ x sin⁻¹(x) dx = (1/2)[(x² - 1)sin⁻¹(x) + x√(1-x²)] + C
5. ∫ x cos⁻¹(x) dx = (1/2)[(x² - 1)cos⁻¹(x) + x√(1-x²)] + C
6. ∫ x tan⁻¹(x) dx = (x²/2)tan⁻¹(x) - (x/2) + (1/2)ln(1+x²) + C

## 5. Special Products
1. ∫ x sin(ax) dx = (sin(ax)/a²) - (x cos(ax)/a) + C
2. ∫ x cos(ax) dx = (cos(ax)/a²) + (x sin(ax)/a) + C
3. ∫ x² sin(ax) dx = (2x sin(ax)/a²) - (x² cos(ax)/a) - (2 cos(ax)/a³) + C
4. ∫ x² cos(ax) dx = (2x cos(ax)/a²) + (x² sin(ax)/a) - (2 sin(ax)/a³) + C
5. ∫ e^(ax) sin(bx) dx = e^(ax)(a sin(bx) - b cos(bx))/(a² + b²) + C
6. ∫ x^n e^(ax) dx = (x^n e^(ax)/a) - (n/a)∫ x^(n-1) e^(ax) dx

## 6. Rational Functions
1. ∫ 1/(x(ax + b)) dx = (1/b)ln|x/(ax + b)| + C
2. ∫ 1/(x²(ax + b)) dx = -1/(bx) + (a/b²)ln|x/(ax + b)| + C
3. ∫ x/(ax² + b) dx = (1/2a)ln|ax² + b| + C
4. ∫ 1/(x²√(ax² + b)) dx = -√(ax² + b)/(bx) + C
5. ∫ x/√(ax² + b) dx = √(ax² + b)/a + C

## 7. Hyperbolic Functions
1. ∫ sinh(x) dx = cosh(x) + C
2. ∫ cosh(x) dx = sinh(x) + C
3. ∫ tanh(x) dx = ln(cosh(x)) + C
4. ∫ coth(x) dx = ln|sinh(x)| + C
5. ∫ sech(x) dx = arctan(sinh(x)) + C
6. ∫ cosech(x) dx = ln|tanh(x/2)| + C
7. ∫ sinh²(x) dx = sinh(x)cosh(x) - x/2 + C
8. ∫ cosh²(x) dx = sinh(x)cosh(x) + x/2 + C

## 8. Definite Integral Special Values
1. ∫₀ᵖⁱ sin(nx) dx = 0, n ∈ Z
2. ∫₀ᵖⁱ cos(nx) dx = 0, n ∈ Z\{0}
3. ∫₀ᵖⁱ/² sin(nx)cos(mx) dx = 0, m,n ∈ Z⁺
4. ∫₀¹ xⁿ ln(x) dx = -1/(n+1)², n > -1
5. ∫₀∞ e⁻ᵃˣ dx = 1/a, a > 0
6. ∫₀∞ xⁿe⁻ᵃˣ dx = n!/aⁿ⁺¹, a > 0, n ∈ N

## 9. Application-Based Integration Formulas
1. Area: A = ∫ᵃᵇ |f(x)| dx
2. Volume of Revolution about x-axis: V = π∫ᵃᵇ [f(x)]² dx
3. Volume of Revolution about y-axis: V = 2π∫ᵃᵇ x|f(x)| dx
4. Arc Length: L = ∫ᵃᵇ √(1 + [f'(x)]²) dx
5. Surface Area of Revolution: S = 2π∫ᵃᵇ |f(x)|√(1 + [f'(x)]²) dx

## 10. Integration Techniques
1. Integration by Parts: ∫u dv = uv - ∫v du
2. Substitution Method: ∫f(g(x))g'(x)dx = ∫f(t)dt, where t = g(x)
3. Partial Fractions Method:
   - For non-repeated linear factors: A/(x-a) + B/(x-b)
   - For repeated linear factors: A/(x-a) + B/(x-a)² + C/(x-a)³
   - For quadratic factors: (Ax + B)/(ax² + bx + c)