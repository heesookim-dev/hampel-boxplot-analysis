# Outlier Detection Research

This project explores outlier detection methods based on the paper *A Method for Finding Outliers*.

Outlier detection is important because extreme values can significantly distort statistical measures such as mean and variance, especially in small-sample datasets.

I implemented the Hampel method and Boxplot method in Java, then analyzed the paper’s proposed modification of replacing MAD with a mean estimated from Boxplot. Based on this analysis, I experimented with an alternative variable intended to preserve robustness while improving sensitivity in small-sample settings.

## Project Goals
- Implement classical outlier detection methods
- Reproduce the paper’s proposed hybrid approach
- Evaluate limitations of replacing MAD with mean
- Propose and test an alternative variable

## Methods
- Hampel method
- Boxplot method
- Paper-proposed hybrid approach
- My proposed variation

## Tech Stack
- Java
- Simulated datasets
- Statistical comparison

## Reference
Chen, T., & Sun, C. (2025). *A Method for Finding Outliers*.  
International Conference on Intelligent Computing and Data Analysis (ICDA).
