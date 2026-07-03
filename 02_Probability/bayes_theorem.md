# Bayes' Theorem

Bayes’ Theorem is used to find the **conditional probability of an event** using prior knowledge of related events.

It helps update probabilities when **new information is available**.

---

## Statement of Bayes’ Theorem

For two events A and B, where P(B) ≠ 0:

P(A | B) = [ P(B | A) × P(A) ] / P(B)

---

## Understanding the Terms

- P(A) → Prior probability of A  
- P(B) → Prior probability of B  
- P(B | A) → Likelihood (probability of B given A)  
- P(A | B) → Posterior probability (updated probability of A)

---

## When is Bayes’ Theorem Used?

- When probabilities need to be updated with new evidence  
- In medical testing, spam detection, risk analysis  
- In machine learning classification models  

---

## Example 1: Basic Numerical Example

Given:
- P(A) = 0.4  
- P(B | A) = 0.5  
- P(B) = 0.6  

Find P(A | B).

### Solution:
P(A | B) = (0.5 × 0.4) / 0.6  
P(A | B) = 0.2 / 0.6  
P(A | B) = **0.333**

---

## Example 2: Medical Test Problem

- 2% of people have a disease  
- Test correctly identifies disease 95% of the time  
- Test gives false positive 5% of the time  

Let:
- D = person has disease  
- T = test is positive  

Given:
- P(D) = 0.02  
- P(T | D) = 0.95  
- P(T | not D) = 0.05  

### Step 1: Find P(T)

P(T) = P(T | D)P(D) + P(T | not D)P(not D)  
P(T) = (0.95 × 0.02) + (0.05 × 0.98)  
P(T) = 0.019 + 0.049  
P(T) = 0.068  

### Step 2: Apply Bayes’ Theorem

P(D | T) = (0.95 × 0.02) / 0.068  
P(D | T) ≈ **0.279**

---

## Key Insight

Even if a test is highly accurate,  
the **actual probability of having the condition may still be low**  
when the condition itself is rare.

---

## Practice Questions with Answers

### 1. If P(A)=0.3, P(B|A)=0.4, and P(B)=0.5, find P(A|B).

**Answer:**  
P(A|B) = (0.4 × 0.3) / 0.5 = **0.24**

---

### 2. Why is Bayes’ Theorem important in machine learning?

**Answer:**  
It helps update predictions using prior knowledge and observed data.

---

### 3. What is the posterior probability in Bayes’ Theorem?

**Answer:**  
The updated probability of an event after considering new evidence.
