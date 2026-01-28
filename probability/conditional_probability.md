# Conditional Probability

Conditional probability measures the **probability of an event occurring given that another event has already occurred**.

It helps us update probabilities based on **new information**.

---

## What is Conditional Probability?

The conditional probability of event A given event B is written as:

P(A | B)

It means:  
**Probability of A, when B has already happened**

---

## Formula

P(A | B) = P(A ∩ B) / P(B)  
(where P(B) ≠ 0)

---

## Understanding the Formula

- P(A ∩ B) → Probability that both A and B occur  
- P(B) → Probability that B occurs  

Conditional probability focuses only on outcomes where **B has occurred**.

---

## Example 1: Coin Toss

Two coins are tossed.

Sample space:  
{HH, HT, TH, TT}

Let:  
A = getting at least one head  
B = first coin is head  

- P(B) = 2 / 4  
- Outcomes where B occurs = {HH, HT}

- Outcomes where both A and B occur = {HH, HT}

P(A | B) = 2 / 2 = **1**

---

## Example 2: Playing Cards

A card is drawn from a deck of 52 cards.

Let:  
A = card is a King  
B = card is a face card  

- Face cards = 12  
- Kings among face cards = 4  

P(A | B) = 4 / 12 = **1 / 3**

---

## Difference Between P(A) and P(A | B)

|   Term   |                 Meaning                |
|----------|----------------------------------------|
| P(A)     | Probability of A without any condition |
| P(A | B) | Probability of A given B has occurred  |

---

## When to Use Conditional Probability?

- When information about another event is available  
- In probability trees and Bayes’ theorem  
- In real-life decision-making problems  

---

## Practice Questions with Answers

### 1. If P(A ∩ B) = 0.2 and P(B) = 0.5, find P(A | B).

**Answer:**  
P(A | B) = 0.2 / 0.5 = **0.4**

---

### 2. A die is rolled. Given that the number is even, what is the probability that it is divisible by 4?

Even numbers = {2, 4, 6}  
Divisible by 4 = {4}

**Answer:**  
P = 1 / 3

---

### 3. Is conditional probability symmetric?  
(i.e., Is P(A | B) = P(B | A)?)

**Answer:**  
No, conditional probability is **not symmetric**.
