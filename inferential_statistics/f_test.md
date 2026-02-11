# F-Test

The **F-Test** is a statistical test used to **compare the variances of two populations**.
It helps determine whether the variability of two samples is significantly different.

The F-test is also the foundation for **ANOVA**.

---

## When to Use F-Test?

Use an F-test when:
- You want to compare **variances** of two samples
- Data is approximately normally distributed
- Samples are independent

---

## F-Test Formula

F = s₁² / s₂²

Where:
- s₁² = variance of sample 1  
- s₂² = variance of sample 2  

👉 The **larger variance is always placed in the numerator**,  
so F ≥ 1.

---

## Hypotheses

- **Null Hypothesis (H₀):**  
  Variances of the two populations are equal  

- **Alternative Hypothesis (H₁):**  
  Variances of the two populations are not equal  

---

## Degrees of Freedom

- df₁ = n₁ − 1  
- df₂ = n₂ − 1  

Where n₁ and n₂ are sample sizes.

---

## Example (Step-by-Step)

Two machines produce rods.

Sample data:
- Sample 1 variance = 16  
- Sample 2 variance = 9  

### Step 1: Calculate F value

F = 16 / 9  
F ≈ **1.78**

---

### Step 2: Decision Rule

- Compare calculated F with **critical F value** from F-table
- If F > F-critical → Reject H₀  
- Otherwise → Fail to reject H₀  

(Assume critical F = 3.18)

---

### Step 3: Conclusion

Since 1.78 < 3.18 → **Fail to reject H₀**

There is **no significant difference** between variances.

---

## Relationship Between F-Test and ANOVA

- F-test compares **two variances**
- ANOVA compares **means of more than two groups**
- ANOVA internally uses the **F-statistic**

---

## Practice Questions with Answers

### 1. What does the F-test compare?

**Answer:**  
Variances of two populations.

---

### 2. Why is the larger variance placed in the numerator?

**Answer:**  
To ensure the F value is always ≥ 1.

---

### 3. What distribution does the F-test follow?

**Answer:**  
F-distribution.
