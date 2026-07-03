# ANOVA (Analysis of Variance)

ANOVA is a statistical test used to compare the **means of three or more groups**
to determine whether at least one group mean is significantly different.

ANOVA uses the **F-statistic** internally.

---

## Why Not Multiple t-tests?

If we perform multiple t-tests:
- Type I error increases
- Results become unreliable

ANOVA solves this by testing all groups at once.

---

## When to Use ANOVA?

Use ANOVA when:
- Comparing means of 3 or more groups
- Data is approximately normally distributed
- Samples are independent
- Variances are approximately equal

---

## Types of ANOVA

### 1. One-Way ANOVA
- One independent variable
- Example: Compare exam scores across 3 different teaching methods

### 2. Two-Way ANOVA
- Two independent variables
- Example: Effect of teaching method and gender on scores

---

## Hypotheses

- **H₀:** All group means are equal  
- **H₁:** At least one group mean is different  

---

## ANOVA Concept

ANOVA compares:
- Variance **between groups**
- Variance **within groups**

F = (Variance Between Groups) / (Variance Within Groups)

If F is large → group means are significantly different.

---

## Example

Three classes have different teaching methods.

Average scores:
- Class A: 75  
- Class B: 82  
- Class C: 79  

ANOVA is used to determine whether the difference in means
is statistically significant.

Assume:
- Calculated F = 4.5  
- Critical F = 3.1  

Since 4.5 > 3.1 → **Reject H₀**

Conclusion:
At least one class mean is significantly different.

---

## Relationship Between F-Test and ANOVA

- F-test compares two variances
- ANOVA compares means of multiple groups
- ANOVA uses F-statistic internally

---

## Practice Questions with Answers

### 1. What does ANOVA test?

**Answer:**  
It tests whether the means of three or more groups are equal.

---

### 2. What happens if calculated F > critical F?

**Answer:**  
Reject the null hypothesis.

---

### 3. Why is ANOVA preferred over multiple t-tests?

**Answer:**  
To control Type I error rate.
