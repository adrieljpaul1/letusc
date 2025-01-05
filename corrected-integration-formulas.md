# Corrected Integration Formulas

## 1. Standard Forms with Parameters
1. ∫ (ax + b)ⁿ dx = (ax + b)ⁿ⁺¹/[a(n+1)] + C
   - Conditions: n ≠ -1, a ≠ 0

2. ∫ 1/(ax + b) dx = (1/a)ln|ax + b| + C
   - Conditions: a ≠ 0

3. ∫ 1/(ax² + bx + c) dx:
   - For b² - 4ac > 0:
     = (2/√(b² - 4ac))ln|(2ax + b - √(b² - 4ac))/(2ax + b + √(b² - 4ac))| + C
   - For b² - 4ac < 0:
     = (2/√(4ac - b²))arctan((2ax + b)/√(4ac - b²)) + C
   - Conditions: a ≠ 0

4. ∫ 1/√(ax² + bx + c) dx:
   - For b² - 4ac < 0:
     = (1/√a)ln|2a√(ax² + bx + c) + 2ax + b| + C
   - For b² - 4ac > 0:
     = ln|√(ax² + bx + c) + √a(x + r₁)| - ln|√(ax² + bx + c) + √a(x + r₂)| + C
     where r₁, r₂ are roots of ax² + bx + c = 0
   - Conditions: ax² + bx + c > 0, a > 0

## 2. Exponential and Logarithmic Forms
1. ∫ xᵃ(ln x)ⁿ dx = xᵃ⁺¹(ln x)ⁿ/(a+1) - (n/(a+1))∫ xᵃ(ln x)ⁿ⁻¹ dx
   - Conditions: x > 0, a ≠ -1, n ∈ ℕ

2. ∫ eᵃˣ(sin bx) dx = eᵃˣ(a sin bx - b cos bx)/(a² + b²) + C
   - Conditions: a, b ∈ ℝ, b ≠ 0

3. ∫ eᵃˣ(cos bx) dx = eᵃˣ(a cos bx + b sin bx)/(a² + b²) + C
   - Conditions: a, b ∈ ℝ, b ≠ 0

4. ∫ xᵃeᵇˣ dx = (xᵃeᵇˣ/b) - (a/b)∫ xᵃ⁻¹eᵇˣ dx
   - Conditions: b ≠ 0, a ∈ ℝ

5. ∫ ln(ax) dx = x ln(ax) - x + C
   - Conditions: ax > 0, a ≠ 0

6. ∫ xln(ax) dx = (x²/2)(ln(ax) - 1/2) + C
   - Conditions: ax > 0, a ≠ 0

## 3. Trigonometric Products and Powers
1. ∫ sinⁿx cosᵐx dx:
   - For n odd (n = 2k+1): Use u = cos x
   - For m odd (m = 2k+1): Use u = sin x
   - For both even: Use reduction formulas

2. ∫ sin(mx)sin(nx) dx = -cos((m+n)x)/(2(m+n)) - cos((m-n)x)/(2(m-n)) + C
   - Conditions: m ± n ≠ 0

3. ∫ cos(mx)cos(nx) dx = sin((m+n)x)/(2(m+n)) + sin((m-n)x)/(2(m-n)) + C
   - Conditions: m ± n ≠ 0

4. ∫ sin(mx)cos(nx) dx = -sin((m+n)x)/(2(m+n)) + sin((m-n)x)/(2(m-n)) + C
   - Conditions: m ± n ≠ 0

## 4. Inverse Trigonometric Forms
1. ∫ sin⁻¹(x) dx = x sin⁻¹(x) + √(1-x²) + C
   - Domain: |x| ≤ 1

2. ∫ cos⁻¹(x) dx = x cos⁻¹(x) - √(1-x²) + C
   - Domain: |x| ≤ 1

3. ∫ tan⁻¹(x) dx = x tan⁻¹(x) - (1/2)ln(1+x²) + C
   - Domain: x ∈ ℝ

4. ∫ x sin⁻¹(x) dx = (1/2)[(x² - 1)sin⁻¹(x) + x√(1-x²)] + C
   - Domain: |x| ≤ 1

5. ∫ x cos⁻¹(x) dx = (1/2)[(x² - 1)cos⁻¹(x) + x√(1-x²)] + C
   - Domain: |x| ≤ 1

## 5. Rational Functions
1. ∫ 1/(x(ax + b)) dx = (1/b)ln|x/(ax + b)| + C
   - Conditions: x ≠ 0, ax + b ≠ 0, b ≠ 0

2. ∫ 1/(x²(ax + b)) dx = -1/(bx) + (a/b²)ln|x/(ax + b)| + C
   - Conditions: x ≠ 0, ax + b ≠ 0, b ≠ 0

3. ∫ x/(ax² + b) dx = (1/2a)ln|ax² + b| + C
   - Conditions: a ≠ 0, ax² + b > 0

4. ∫ 1/(x²√(ax² + b)) dx = -√(ax² + b)/(bx) + C
   - Conditions: x ≠ 0, ax² + b > 0, b ≠ 0

5. ∫ x/√(ax² + b) dx = √(ax² + b)/a + C
   - Conditions: ax² + b > 0, a ≠ 0

## 6. Definite Integral Special Values
1. ∫₀ᵖⁱ sin(nx) dx = 0
   - Conditions: n ∈ ℤ

2. ∫₀ᵖⁱ cos(nx) dx = 0
   - Conditions: n ∈ ℤ\{0}

3. ∫₀ᵖⁱ/² sin(nx)cos(mx) dx = 0
   - Conditions: m, n ∈ ℤ⁺

4. ∫₀¹ xⁿ ln(x) dx = -1/(n+1)²
   - Conditions: n > -1

5. ∫₀∞ e⁻ᵃˣ dx = 1/a
   - Conditions: a > 0

6. ∫₀∞ xⁿe⁻ᵃˣ dx = n!/aⁿ⁺¹
   - Conditions: a > 0, n ∈ ℕ₀