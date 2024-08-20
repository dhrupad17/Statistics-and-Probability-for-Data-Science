# Z-Test vs t-Test

| **Feature**                  | **Z-Test**                                               | **t-Test**                                               |
|------------------------------|----------------------------------------------------------|----------------------------------------------------------|
| **Population Variance**      | Known                                                    | Unknown                                                  |
| **Sample Size**              | Large (typically \( n > 30 \))                           | Small (typically \( n <= 30 \))                        |
| **Test Statistic**           | Z-score                                                  | t-score                                                  |
| **Distribution**             | Normal Distribution                                      | t-Distribution                                           |
| **Formula**                  | ![image](https://github.com/user-attachments/assets/60754c7d-1f72-498c-bca0-035516e2ec31) |  ![image](https://github.com/user-attachments/assets/84d69201-3fe1-48b0-994f-a55fa78a3b67)  |
| **Degrees of Freedom (df)**  | Not applicable                                           | \( df = n - 1 \) (for one-sample t-test)                 |
| **Use Case**                 | - When population variance is known.                     | - When population variance is unknown.                   |
|                              | - When sample size is large.                             | - When sample size is small.                             |
| **Example**                  | Comparing a large sample mean to a population mean with known variance. | Comparing a small sample mean to a population mean with unknown variance. |
| **Critical Values**          | Fixed for a given α (e.g., 1.96 for α = 0.05 in a two-tailed test) | Varies with sample size and degrees of freedom (refer to t-distribution table) |
| **Applicability**            | More appropriate when sample size is large and/or variance is known. | More appropriate when sample size is small and variance is unknown. |

![image](https://github.com/user-attachments/assets/b17f82a9-62db-4f13-9a9a-71656b4c06b6)
