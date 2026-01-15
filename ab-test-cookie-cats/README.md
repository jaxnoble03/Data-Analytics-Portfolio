# A/B Test Analysis: Cookie Cats Gate Placement

## Overview
Statistical analysis of a mobile game A/B test to determine whether moving an in-game gate from level 30 to level 40 affects player retention and engagement.

## Key Findings
- **Day 7 Retention:** gate_30 significantly outperforms gate_40 (p = 0.002)
  - gate_30: 19.02% retention
  - gate_40: 18.20% retention
  - Difference: +0.82 percentage points
- **Day 1 Retention:** No significant difference (p = 0.074)
- **Game Rounds:** No significant difference

## Business Recommendation
**Keep the gate at level 30.** Moving to level 40 significantly hurts long-term retention without any offsetting benefits.

## Statistical Methods
- Two-proportion z-tests for retention metrics
- Independent samples t-test for continuous data
- 95% confidence intervals
- Significance threshold: p < 0.05

## Tools & Technologies
- Python (Pandas, NumPy, SciPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Statistical Hypothesis Testing

## Dataset
Cookie Cats mobile game data (90,189 players, available on Kaggle)
