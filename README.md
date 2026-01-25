[![Python CI](https://github.com/shreyapatil9480/project-management-analytics-demo/actions/workflows/python-ci.yml/badge.svg)](https://github.com/shreyapatil9480/project-management-analytics-demo/actions/workflows/python-ci.yml)
![Python](https://img.shields.io/badge/python-3.11-blue)
![pytest](https://img.shields.io/badge/tested%20with-pytest-0A9EDC)

# Project Management Analytics Demo

Where are resources overallocated?

**Stakeholder:** Resource Manager

## Key Insights

- Bench time under 4 hours/week signals overallocation risk.
- Billable hours above 42/week precedes overallocation flags.
- FTE above 1.2 on a single initiative raises overload probability.

## Dataset

Primary file: `data/resource_utilization.csv`  
Target variable: `overallocated`

## Getting Started

```bash
pip install -r requirements.txt
jupyter notebook notebooks/case_study.ipynb
```



## Testing

```bash
pip install -r requirements.txt
pytest tests/ --cov=src
```

## Next Steps

Tune class weights and add SHAP explainability.

---
*Analytics portfolio project — 2025-09*

<!-- build 5 -->

### Implemented

```bash
pip install -r requirements.txt
python src/train.py && python src/explain.py
```
