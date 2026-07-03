# Statistics Practice: Solved Numerical Problems

This practice sheet contains step-by-step numerical calculations for core statistical concepts, acting as a handy reference for interviews and data processing pipelines.

---

## 🧮 PROBLEM 1: Z-Score and Outlier Detection
**Scenario:** A data science team is analyzing user session times on an app. The average session time ($\mu$) is **25 minutes** with a standard deviation ($\sigma$) of **5 minutes**. A specific user spent **40 minutes** on the app. Find the Z-score for this user and determine if this is an outlier.

### Given Data:
- Value ($X$) = 40
- Mean ($\mu$) = 25
- Standard Deviation ($\sigma$) = 5

### Mathematical Formula:
$$Z = \frac{X - \mu}{\sigma}$$

### Step-by-Step Calculation:
1. Subtract the mean from the value: $40 - 25 = 15$
2. Divide by the standard deviation: $\frac{15}{5} = 3.0$

### Final Answer & Conclusion:
The **Z-score is $+3.0$**. Since a Z-score of $\ge 3.0$ or $\le -3.0$ is standardly classified as an outlier in data preprocessing, this user's session is an **extreme outlier** (unusual engagement behavior).

---

## 📊 PROBLEM 2: 95% Confidence Interval Calculation
**Scenario:** We pulled a random sample of $n = 100$ data analyst resumes and found their mean entry-level salary ($\bar{x}$) to be **\$70,000**. The population standard deviation ($\sigma$) is known to be **\$5,000**. Calculate the 95% Confidence Interval for the true population mean salary.

### Given Data:
- Sample Size ($n$) = 100
- Sample Mean ($\bar{x}$) = \$70,000
- Population Std Dev ($\sigma$) = \$5,000
- Confidence Level = 95% $\rightarrow$ Critical Z-score ($z_{\alpha/2}$) = **1.96**

### Mathematical Formula:
$$\text{CI} = \bar{x} \pm z_{\alpha/2} \left( \frac{\sigma}{\sqrt{n}} \right)$$

### Step-by-Step Calculation:
1. Calculate the Standard Error (SE):
   $$\text{SE} = \frac{\sigma}{\sqrt{n}} = \frac{5000}{\sqrt{100}} = \frac{5000}{10} = 500$$
2. Calculate the Margin of Error (ME):
   $$\text{ME} = 1.96 \times 500 = 980$$
3. Compute Upper and Lower Limits:
   - Lower Limit = $70,000 - 980 = 69,020$
   - Upper Limit = $70,000 + 980 = 70,980$

### Final Answer & Conclusion:
The **95% Confidence Interval is (\$69,020, \$70,980)**. We are 95% confident that the true average entry-level salary for data analysts falls between \$69,020 and \$70,980.

---

## 📈 PROBLEM 3: Pearson's Correlation Coefficient ($r$)
**Scenario:** Find the correlation coefficient between hours studied ($X$) and test scores ($Y$) for 3 students.

### Given Data Table:
| Student | Hours Studied ($X$) | Test Score ($Y$) |
| :--- | :--- | :--- |
| 1 | 2 | 50 |
| 2 | 4 | 70 |
| 3 | 6 | 90 |

### Step-by-Step Calculation:
1. **Find Mean of $X$ and $Y$:**
   - $\bar{x} = \frac{2 + 4 + 6}{3} = 4$
   - $\bar{y} = \frac{50 + 70 + 90}{3} = 70$

2. **Calculate Deviations & Deviations Squared:**
   - For $X$: $(2-4)=-2$, $(4-4)=0$, $(6-4)=2 \rightarrow \sum(x-\bar{x})^2 = (-2)^2 + 0^2 + 2^2 = \mathbf{8}$
   - For $Y$: $(50-70)=-20$, $(70-70)=0$, $(90-70)=20 \rightarrow \sum(y-\bar{y})^2 = (-20)^2 + 0^2 + 20^2 = \mathbf{800}$

3. **Calculate Product of Deviations $\sum(x-\bar{x})(y-\bar{y})$:**
   - Student 1: $(-2) \times (-20) = 40$
   - Student 2: $0 \times 0 = 0$
   - Student 3: $2 \times 20 = 40$
   - Sum of Products = $40 + 0 + 40 = \mathbf{80}$

4. **Apply Pearson's Formula:**
   $$r = \frac{80}{\sqrt{8 \times 800}} = \frac{80}{\sqrt{6400}} = \frac{80}{80} = 1.0$$

### Final Answer & Conclusion:
The **Correlation Coefficient ($r$) is $+1.0$**. This indicates a **perfect positive linear relationship**—every extra hour of study leads to a perfectly predictable increase in test scores.
