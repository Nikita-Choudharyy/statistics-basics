# Binomial Distribution

The **Binomial Distribution** is a **discrete probability distribution** that models the number of successes in a fixed number of independent trials.

---

## When is Binomial Distribution Used?

Binomial distribution is applicable when:
1. The number of trials (n) is fixed  
2. Each trial has only two outcomes (success or failure)  
3. Probability of success (p) is constant  
4. Trials are independent  

---

## Key Terms

- n → number of trials  
- x → number of successes  
- p → probability of success  
- q → probability of failure (q = 1 − p)

---

## Probability Mass Function (PMF)

The probability of getting **x successes** in **n trials** is:

P(X = x) = ⁿCₓ · pˣ · qⁿ⁻ˣ

---

## Example 1: Coin Toss

A fair coin is tossed **5 times**.  
Find the probability of getting **exactly 3 heads**.

Given:
- n = 5  
- x = 3  
- p = 0.5  
- q = 0.5  

### Solution:
P(X = 3) = ⁵C₃ × (0.5)³ × (0.5)²  
P(X = 3) = 10 × 0.125 × 0.25  
P(X = 3) = **0.3125**

---

## Mean and Variance of Binomial Distribution

- Mean = n × p  
- Variance = n × p × q  
- Standard Deviation = √(n × p × q)

---

### Example:
If n = 10 and p = 0.3:

- Mean = 10 × 0.3 = **3**  
- Variance = 10 × 0.3 × 0.7 = **2.1**  
- Standard Deviation = √2.1 ≈ **1.45**

---

## Applications of Binomial Distribution

- Quality control (defective vs non-defective)  
- Exam pass/fail analysis  
- Marketing response analysis  
- Machine learning classification problems  

---

## Practice Questions with Answers

### 1. A die is rolled 4 times. What is the probability of getting exactly 2 sixes?

Given:
- n = 4  
- x = 2  
- p = 1/6  
- q = 5/6  

**Answer:**  
P(X = 2) = ⁴C₂ × (1/6)² × (5/6)²  
= 6 × (1/36) × (25/36)  
= **150 / 1296**

---

### 2. What is the mean of a binomial distribution with n = 8 and p = 0.25?

**Answer:**  
Mean = n × p = 8 × 0.25 = **2**

---

### 3. Is binomial distribution discrete or continuous?

**Answer:**  
Discrete distribution
