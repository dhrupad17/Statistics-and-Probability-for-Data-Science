# Why Sample Variance is Divided by \( n-1 \) but Population Variance is Divided by \( N \)

## Population Variance

- **Population Mean** is known and used directly in the formula.
- Since the variance is calculated for the entire population, there's no need to adjust for any potential bias.
- **Dividing by \( N \)** gives the exact average squared deviation from the mean.

## Sample Variance

- **Sample Mean** is an estimate of the population mean.
- **Dividing by \( n-1 \)**, known as Bessel's correction, corrects for the bias in the estimation of the population variance from a sample.
- The reason for this correction is that using the sample mean underestimates the true variability in the population. By dividing by \( n-1 \) instead of \( n \), we compensate for this underestimation, providing an unbiased estimate of the population variance.

