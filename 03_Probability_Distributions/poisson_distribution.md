# Poisson Distribution

The **Poisson Distribution** is a **discrete probability distribution** used to model
the number of times an event occurs in a **fixed interval of time or space**.

---

## When is Poisson Distribution Used?

Poisson distribution is applicable when:
1. Events occur independently  
2. Average rate (λ) is constant  
3. Two events cannot occur at the same exact instant  
4. Number of trials is not fixed (unlike binomial distribution)

---

## Key Parameter

- λ (lambda) → average number of occurrences in a given interval

---

## Probability Mass Function (PMF)

The probability of observing **x events** is:

P(X = x) = (e^(-λ) · λ^x) / x!

---

## Example 1: Call Center

A call center receives an average of **4 calls per hour**.

Find the probability that exactly **2 calls** are received in an hour.

Given:
- λ = 4  
- x = 2  

### Solution:
P(X = 2) = (e^(-4) · 4²) / 2!  
P(X = 2) = (e^(-4) · 16) / 2  
P(X = 2) = **8e^(-4)**

---

## Mean and Variance

For Poisson distribution:

- Mean = λ  
- Variance = λ  
- Standard Deviation = √λ

---

## Difference Between Binomial and Poisson Distribution

|     Feature      |     Binomial    |       Poisson         |
|------------------|-----------------|-----------------------|
| Number of trials | Fixed           | Not fixed             |
| Probability      | Constant        | Based on rate (λ)     |
| Outcomes         | Success/Failure | Number of occurrences |
| Mean             | n·p             | λ                     |

---

## Applications of Poisson Distribution

- Number of accidents per day  
- Calls received in a call center  
- Defects per unit in manufacturing  
- Arrivals at a service center  

---

## Practice Questions with Answers

### 1. If λ = 3, find P(X = 1).

**Answer:**  
P(X = 1) = (e^(-3) · 3¹) / 1! = **3e^(-3)**

---

### 2. What is the mean of a Poisson distribution with λ = 5?

**Answer:**  
Mean = **5**

---

### 3. Is Poisson distribution discrete or continuous?

**Answer:**  
Discrete distribution
