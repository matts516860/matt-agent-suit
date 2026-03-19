# Tableau Calculations

(See original project for full details)

Use SCRIPT_REAL to call TabPy endpoints such as:
- predict_total_goals
- predict_goals_bayesian
- predict_goals_prophet

Example:

```tableau
SCRIPT_REAL(
"return tabpy.query('predict_total_goals', years=_arg1, rounds=_arg2)['response']",
ATTR([Year]), ATTR([Round])
)
```
