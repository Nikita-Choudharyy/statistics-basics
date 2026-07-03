# Correlation (Descriptive & Inferential Analytics)
As a data science student,I learned that before building any predictive model, we must understand how different variables interact with each other. **Correlation** is a statistical technique that measures the strength and direction of a linear relationship between two quantitative variables.

## 📌 Key Concepts & Types
- **Positive Correlation:** As variable $X$ increases, variables $Y$ also increases (e.g.,Study hours and Exam scores).
- **Negative Correlation:** As variable $X$ increases, variables $Y$ decreases (e.g., Car and Travel time).
- **Zero Correlation:** No linear relationship exists between the variables (e.g., Shoe size and Intelligence).

## 📊 Pearson Correlation Coefficient ($r$)

The most common way to measure correlation is using Pearson's $r$. The value of $r$ always ranges strictly between **$-1$ and $+1$**:

- $r = +1 \rightarrow$ Perfect positive linear relationship.
- $r = -1 \rightarrow$ Perfect negative linear relationship.
- $r = 0 \rightarrow$ Absolute zero linear relationship.

### The Mathematical Formula:
$$r = \frac{\sum (x - \bar{x})(y - \bar{y})}{\sqrt{\sum (x - \bar{x})^2 \sum (y - \bar{y})^2}}$$

## ⚠️ The Golden Rule: Correlation $\neq$ Causation
Just because two variable move together does not mean one *causes* the other to happen. For example, ice cream sales and sunburns are highly correlated, but ice cream doesn't cause sunburns-the hot summer weather (a confunding variable) causes both!

