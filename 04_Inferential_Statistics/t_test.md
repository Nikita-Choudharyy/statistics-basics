# t-Test

The **t-test** is a hypothesis test used to determine whether there is a
**significant difference between means** when the sample size is small
or the population standard deviation is unknown.

---

## When to Use t-Test?

Use a t-test when:
1. Sample size is small (n < 30)
2. Population standard deviation (σ) is unknown
3. Data is approximately normally distributed

---

## Types of t-Test

### 1. One-Sample t-Test
- Compares sample mean with a known population mean

### 2. Independent (Two-Sample) t-Test
- Compares means of two independent groups

### 3. Paired t-Test
- Compares means of the same group before and after treatment

---

## t-Test Formula (One-Sample)

t = (x̄ − μ) / (s / √n)

Where:
- x̄ = sample mean  
- μ = population mean  
- s = sample standard deviation  
- n = sample size  

---

## Steps in t-Test

1. State null and alternative hypothesis  
2. Choose significance level (α)  
3. Calculate t value  
4. Find critical t value (using t-table)  
5. Make decision  

---

## Example (One-Sample t-Test)

A sample of **10 students** has an average score of **75**.
The claimed population mean is **70**.

Given:
- x̄ = 75  
- μ = 70  
- s = 8  
- n = 10  
- α = 0.05  

### Step 1: Hypotheses
H₀: μ = 70  
H₁: μ ≠ 70  

---

### Step 2: Calculate t value

t = (75 − 70) / (8 / √10)  
t = 5 / 2.53  
t ≈ **1.98**

---

### Step 3: Decision

Critical t value at α = 0.05 (two-tailed, df = 9) ≈ **2.262**

Since |t| < 2.262 → **Fail to reject H₀**

---

## Difference Between Z-Test and t-Test

|    Feature   | Z-Test |     t-Test     |
|--------------|--------|----------------|
| Sample size  | Large  | Small          |
| σ known      | Yes    | No             |
| Distribution | Normal | t-distribution |

---

## Practice Questions with Answers

### 1. When should a t-test be preferred over a Z-test?

**Answer:**  
When sample size is small and population standard deviation is unknown.

---

### 2. Which t-test is used for before-and-after comparisons?

**Answer:**  
Paired t-test.

---

### 3. If calculated |t| > critical t value, what is the decision?

**Answer:**  
Reject the null hypothesis.
