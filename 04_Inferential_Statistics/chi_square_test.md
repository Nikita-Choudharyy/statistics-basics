# Chi-Square Test

The **Chi-Square (χ²) Test** is a statistical test used to determine whether
there is a **significant association between categorical variables**.

It compares **observed frequencies** with **expected frequencies**.

---

## When to Use Chi-Square Test?

Use the Chi-Square test when:
- Data is **categorical**
- Observations are independent
- Expected frequency in each cell is sufficiently large (generally ≥ 5)

---

## Types of Chi-Square Tests

### 1. Chi-Square Test of Independence
- Checks whether two categorical variables are related

### 2. Chi-Square Goodness of Fit Test
- Checks whether observed data fits a known distribution

---

## Chi-Square Formula

χ² = Σ [(O − E)² / E]

Where:
- O = Observed frequency  
- E = Expected frequency  

---

## Degrees of Freedom (df)

df = (rows − 1) × (columns − 1)

---

## Example: Test of Independence

A survey records **gender and preference for online courses**.

| Gender | Prefer Online | Prefer Offline | Total |
|--------|---------------|----------------|-------|
| Male   | 30            | 20             | 50    |
| Female | 20            | 30             | 50    |
| Total  | 50            | 50             | 100   |

---

### Step 1: Hypotheses

H₀: Gender and course preference are independent  
H₁: Gender and course preference are dependent  

---

### Step 2: Expected Frequencies

E = (Row total × Column total) / Grand total

For Male & Online:
E = (50 × 50) / 100 = 25

(Similarly calculate for other cells)

---

### Step 3: Calculate χ² value

χ² = Σ [(O − E)² / E]

(After calculation, assume χ² = 4)

---

### Step 4: Decision

- df = (2−1)(2−1) = 1  
- Critical χ² at α = 0.05, df = 1 = **3.84**

Since χ² (4) > 3.84 → **Reject H₀**

---

## Conclusion

There is a **significant association** between gender and course preference.

---

## Practice Questions with Answers

### 1. What type of data is required for a Chi-Square test?

**Answer:**  
Categorical data

---

### 2. What does the Chi-Square test compare?

**Answer:**  
Observed and expected frequencies

---

### 3. How is degree of freedom calculated?

**Answer:**  
(rows − 1) × (columns − 1)
