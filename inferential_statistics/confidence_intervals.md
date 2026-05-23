# Confidence Intervals (Inferential Statistics)

As a data science student, I learned that we can rarely calculate the exact population parameters (like the true average height of everyone in a country) because collecting data from every single person is impossible. Instead, we take a sample.

A **Confidence Interval (CI)** is a type of estimate computed from the observed sample data that gives a **range of values** where the true population parameter is likely to fall, along with a specific level of confidence!

## 📌 Key Concepts (Student Notes)

- **Point Estimate:** A single value (like the sample mean $\bar{x}$) that serves as our best guess for the population parameter.
- **Interval Estimate:** A range of values $(\text{Lower Limit}, \text{Upper Limit})$ that tells us where the true value probably lies.
- **Confidence Level ($1 - \alpha$):** The probability that the interval contains the true population parameter if we repeat the sampling process many times. The most common levels are **95%** and **99%**.
  - *What does 95% Confidence Level actually mean?* It means if we collect 100 different samples and calculate a confidence interval for each, about 95 of those intervals will contain the true population parameter. It does NOT mean there is a 95% chance that the true value lies in this specific interval.
- **Margin of Error (ME):** The maximum expected difference between the true population parameter and the sample estimate. 
  $$\text{Confidence Interval} = \text{Point Estimate} \pm \text{Margin of Error}$$



## 🚀 Real-World Data Science Use-Cases

1. **A/B Testing (App Engagement):** When testing a new feature, we don't just state that users spent 5 minutes more on average. We say, "We are 95% confident that the new feature increases average user time by between 4.2 and 5.8 minutes."
2. **Machine Learning Model Accuracy:** Predicting the error rate of a model on unseen production data within a specific confidence range rather than reporting a single number.
3. **E-commerce Pricing:** Estimating the average amount a customer is willing to spend on a new subscription bundle.

## 📊 The Math & Calculation Formula

Depending on the sample size and whether we know the population standard deviation ($\sigma$), we use two different distributions to calculate the critical values:

### 1. Z-Interval (Used when Population Variance $\sigma$ is KNOWN and $n \ge 30$)
$$\text{CI} = \bar{x} \pm z_{\alpha/2} \left( \frac{\sigma}{\sqrt{n}} \right)$$

### 2. T-Interval (Used when Population Variance $\sigma$ is UNKNOWN or $n < 30$)
$$\text{CI} = \bar{x} \pm t_{\alpha/2, df} \left( \frac{s}{\sqrt{n}} \right)$$
*(Where $s$ is sample standard deviation, and $df = n - 1$ is the degrees of freedom)*

### 💡 Common Z-Score Critical Values to Remember:
- For **90%** Confidence Level: $Z = 1.645$
- For **95%** Confidence Level: $Z = 1.96$
- For **99%** Confidence Level: $Z = 2.576$

## 📝 Quick Revision Checklist for Practice
- **Larger sample size ($n$)** $\rightarrow$ Narrower interval (More precise estimate).
- **Higher confidence level** $\rightarrow$ Wider interval (We need a bigger net to be more sure!).
