# Simple Linear Regression

While correlation only tells us *how strongly* two variables are related, **Simple Linear Regression** goes a step further. It allows us to *predict* the value of a dependent variable ($Y$) based on the value of an independent variable ($X$).

## 📈 The Regression Line Equation

In statistics, we model this relationship using the equation of a straight line:

$$Y = \beta_0 + \beta_1X + \epsilon$$

Where:
- $Y$ = Dependent / Target variable (The thing we want to predict).
- $X$ = Independent / Predictor variable (The feature we use to predict).
- $\beta_0$ = Y-intercept (The value of $Y$ when $X = 0$).
- $\beta_1$ = Slope coefficient (How much $Y$ changes for a 1-unit change in $X$).
- $\epsilon$ = Residual error (The difference between actual values and predicted values).



## 🎯 Ordinary Least Squares (OLS) Method

How do we find the perfect line? We use the **OLS method**, which minimizes the sum of the squared differences (residuals) between the actual data points and the predicted regression line.

$$\text{Minimize: } \sum (y_i - \hat{y}_i)^2$$

## 📊 How to Evaluate the Model? (R-Squared)

To check how good our regression line is, we look at **$R^2$ (Coefficient of Determination)**. It tells us the percentage of variance in the dependent variable that can be explained by the independent variable.
- $R^2 = 0.85$ means 85% of the variation in our target is captured by our model!

---

### 🚀 Data Science Action Plan for Git:
- **File Name:** `correlation_regression/simple_linear_regression.md`
- **Commit Message:** `docs: add simple linear regression OLS formulas and evaluation notes`
