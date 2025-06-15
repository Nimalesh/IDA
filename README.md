# Fair MIP Tree

This repository contains an implementation of a **Fair MIP Tree** model using Python. The model leverages Mixed-Integer Programming (MIP) for building interpretable decision trees while integrating fairness constraints.

---

## Requirements

To run the notebook, install the following dependencies:

```bash
pip install ucimlrepo gurobipy fairlearn xgboost pandas numpy scikit-learn matplotlib
```

> Note: Gurobi requires a valid license. You can obtain a free academic license from [https://www.gurobi.com/](https://www.gurobi.com/).

---

## Repository Structure

- `IDA_Code.ipynb`: Main notebook implementing the Fair MIP Tree model.
- Uses UCI datasets via `ucimlrepo`
- Data preprocessing using `pandas`, `numpy`, and `scikit-learn`
- Model optimization using `gurobipy`
- Fairness evaluation using `fairlearn`
- Optional integration with `xgboost` for performance benchmarking

---

## Running the Notebook

1. ]download the notebook.
2. Ensure all dependencies are installed.
3. Open the notebook with Jupyter or another notebook interface.
4. Execute each cell step-by-step to:
   - Load and preprocess data
   - Define fairness constraints
   - Train and solve the MIP model
   - Evaluate model performance and fairness metrics


## Overleaf link

https://www.overleaf.com/9955283188xypyfhndppvx#93d191

