# Hypothesis Testing in Inferential Statistics

Hypothesis testing is a fundamental aspect of inferential statistics, allowing us to make decisions or inferences about a population based on sample data. Below is a summary of key concepts, steps, and terminologies used in hypothesis testing.

![image](https://github.com/user-attachments/assets/139bcf7f-d4f8-4fc3-91c2-8d029a1cae2e)


## 1. Key Concepts

### Null Hypothesis (H₀)
- The default assumption or statement to be tested.
- Usually states that there is no effect, no difference, or no relationship in the population.
- **Example:** "There is no difference in the mean scores of two groups."

### Alternative Hypothesis (H₁ or Ha)
- The statement that contradicts the null hypothesis.
- Represents the outcome the researcher expects or wants to test.
- **Example:** "There is a difference in the mean scores of two groups."

### Significance Level (α)
- The threshold probability for rejecting the null hypothesis.
- Commonly set at 0.05, meaning there's a 5% risk of rejecting the null hypothesis when it is actually true.

### p-Value
- The probability of obtaining test results at least as extreme as the results actually observed, under the assumption that the null hypothesis is true.
- If the p-value is less than the significance level (α), we reject the null hypothesis.

### Type I Error (α error)
- The error of rejecting a true null hypothesis.
- The probability of making this error is equal to the significance level (α).

### Type II Error (β error)
- The error of failing to reject a false null hypothesis.
- The probability of making this error is denoted by β.

### Power of the Test
- The probability of correctly rejecting a false null hypothesis.
- Power = 1 - β.

## 2. Steps in Hypothesis Testing

### State the Hypotheses
- Formulate the null hypothesis (H₀) and the alternative hypothesis (H₁).

### Choose the Significance Level (α)
- Decide on the significance level, typically 0.05.

### Select the Appropriate Test
- Depending on the data type and distribution, choose a statistical test (e.g., t-test, chi-square test, ANOVA).

### Calculate the Test Statistic
- Compute the test statistic using the sample data.

### Determine the p-Value or Critical Value
- Find the p-value or compare the test statistic to the critical value to make a decision.

### Make a Decision
- If p-value ≤ α, reject H₀ (suggesting evidence in favor of H₁).
- If p-value > α, fail to reject H₀ (not enough evidence to support H₁).

### Interpret the Results
- Draw conclusions based on the decision and context of the research question.

## 3. Common Tests in Hypothesis Testing

### Z-Test
- Used when the sample size is large (n > 30) and the population variance is known.

### t-Test
- Used when the sample size is small (n ≤ 30) and the population variance is unknown.
- **Types:**
  - **One-sample t-test:** Compares the sample mean to a known value.
  - **Independent two-sample t-test:** Compares means of two independent groups.
  - **Paired t-test:** Compares means of two related groups.

### Chi-Square Test
- Used for categorical data to assess how likely it is that an observed distribution is due to chance.

### ANOVA (Analysis of Variance)
- Used to compare the means of three or more groups.
