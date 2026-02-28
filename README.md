# Social Media & Academic Performance Analysis

## Overview
Statistical analysis of how daily social media usage affects academic 
performance and mental health among undergraduate students across the 
USA, France, and Spain (n=81).

## Key Findings
- Students reporting academic impact averaged 6.1 hrs/day of social 
  media vs 3.8 hrs for unaffected students (p < 0.001)
- Each additional hour of usage associated with a 0.52 point drop 
  in mental health score
- Social media usage explains 66% of variance in mental health scores (R² = 0.66)
- USA students averaged 7.1 hrs/day — highest among the three countries

## Methods
- Filtered undergraduate students from top 3 countries by sample size
- Welch two-sample t-test comparing usage hours by academic impact
- Simple linear regression predicting mental health score from usage hours
- Descriptive statistics grouped by country

## Tech Stack
R · dplyr · ggplot2 · knitr

## Files
| File | Description |
|------|-------------|
| `MATH408_Project_Euro_Kim.Rmd` | Full R analysis and code |
| `Students_Social_Media_Addiction.csv` | Raw dataset from Kaggle |
| `MATH408_Project_Euro_Kim.pdf` | Written report with results |

## Data Source
Kaggle — [Students' Social Media Addiction](https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships)
