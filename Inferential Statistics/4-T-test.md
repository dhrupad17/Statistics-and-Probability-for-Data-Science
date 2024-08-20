# t-Test in Hypothesis Testing

## What is a t-Test?

- A **t-test** is a statistical test used to compare the means of two groups or to compare a sample mean to a known value, especially when the sample size is small and the population variance is unknown.
- It is commonly used when the sample size is small (\( n \leq 30 \)).

## Types of t-Tests

### 1. One-Sample t-Test
- **Purpose:** To compare the mean of a single sample to a known population mean.
- **Hypotheses:**
  - **Null Hypothesis (H₀):** The sample mean is equal to the population mean.
  - **Alternative Hypothesis (H₁):** The sample mean is not equal to the population mean.

### 2. Independent Two-Sample t-Test
- **Purpose:** To compare the means of two independent groups.
- **Hypotheses:**
  - **Null Hypothesis (H₀):** The means of the two groups are equal.
  - **Alternative Hypothesis (H₁):** The means of the two groups are not equal.
- **Assumptions:**
  - The two groups are independent.
  - The data in both groups are normally distributed.
  - The variances of the two groups are equal (can be tested with Levene's test).

### 3. Paired t-Test
- **Purpose:** To compare the means of two related groups (e.g., before and after measurements on the same subjects).
- **Hypotheses:**
  - **Null Hypothesis (H₀):** The mean difference between the paired observations is zero.
  - **Alternative Hypothesis (H₁):** The mean difference between the paired observations is not zero.
- **Assumptions:**
  - The data are paired and related.
  - The differences between the paired data are normally distributed.

## t-Test Formula

![image](https://github.com/user-attachments/assets/3082fdfc-d59c-4190-97e0-50026452b027)


## Example 

![image](https://github.com/user-attachments/assets/c8fafde1-928f-4aa2-b311-5ce85dba5bde)
![image](https://github.com/user-attachments/assets/402d6801-07f7-41ef-9f62-564ced6eae4d)
![image](https://github.com/user-attachments/assets/09388dee-207d-4169-b6d0-cda1f3a98e3e)



## When to Use t-Test?

- Use a t-test when the sample size is small and the population variance is unknown. For large samples or known variance, a Z-test might be more appropriate.

