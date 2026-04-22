# Lab 11: Non-Parametric Statistical Testing

[Русская версия](README_ru.md)

Applied Mann-Whitney U test and Chi-squared goodness-of-fit test to analyze restaurant billing patterns. Built with Python, `scipy`, `seaborn`, and `matplotlib`.

## Key Results
- Significant difference in bill amounts between lunch and dinner (p < 0.001)
- Total bills do not follow an exponential distribution (χ² test, p ≈ 0)
- Visualizations confirm non-parametric assumptions are met

## How to Run
```bash
pip install -r requirements.txt
# Then open lab11.ipynb in Jupyter, VS Code, or Google Colab