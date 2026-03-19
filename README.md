# TabPy World Cup Hands-On Training (Tableau Conference)

This repository contains a hands-on workshop for **Tableau Conference (TC26)** focused on:

- Analytics Extensions (TabPy)
- External model integration
- Predictive + Bayesian + forecasting techniques in Tableau

## Project Structure

```text
.
├── README.md
├── requirements.txt
├── tableau-calculations.md
├── data/
│   └── world_cup_matches_sample.csv
└── src/
    ├── deploy_regression.py
    ├── deploy_bayesian.py
    └── deploy_prophet.py
```

## Quick Start

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
tabpy
python src/deploy_regression.py
```

Then connect Tableau Desktop to TabPy at `localhost:9004`.

---

## Purpose

This repo is designed for:
- Hands-on training sessions
- Workshop labs
- Conference demos

Participants will:
1. Deploy models to TabPy
2. Connect Tableau to external models
3. Visualize predictions and uncertainty
