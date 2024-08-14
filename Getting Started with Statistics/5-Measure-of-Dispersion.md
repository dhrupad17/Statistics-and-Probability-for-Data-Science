# Measures of Dispersion

<p align="center">
  <img src="https://media.geeksforgeeks.org/wp-content/uploads/20230810105933/measure-of-depression.png" alt="Measures of Dispersion"/>
</p>


**Measures of Dispersion** quantify the spread or variability within a dataset. They provide insights into how much the data points differ from the central tendency measures (like the mean or median).

## 1. Variance

- **Definition:** The average of the squared differences between each data point and the mean.
- **Formulas:**
- **Population Variance (σ²):**
  ```
  σ² = (Σ (xᵢ - μ)²) / N
  ```
- **Sample Variance (s²):**
  ```
  s² = (Σ (xᵢ - x̄)²) / (n - 1)
  ```
where:
- `xᵢ` = each data point
- `μ` = population mean
- `x̄` = sample mean
- `N` = size of the population
- `n` = size of the sample
- **Example:** For sample data [4, 8, 6, 5], 
- Mean (x̄) = (4 + 8 + 6 + 5)/4 = 5.75
- s² = [(4-5.75)² + (8-5.75)² + (6-5.75)² + (5-5.75)²] / (4-1) = 2.9167

## 2. Standard Deviation

- **Definition:** The square root of the variance, representing the average distance of each data point from the mean.
- **Formulas:**
- **Population Standard Deviation (σ):**
  ```
  σ = sqrt(σ²)
  ```
- **Sample Standard Deviation (s):**
  ```
  s = sqrt(s²)
  ```
- **Example:** Continuing from the variance example above, 
- s = sqrt(2.9167) ≈ 1.708
