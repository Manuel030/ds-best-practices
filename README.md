# ds-best-practices

Template for Data Science projects. It covers the steps between dataset creation and model training of the MLOps lifecycle.
The focus is on facilitating best practices and patterns for preparing training, evaluation, and testing datasets, tuning
hyperparameters and training machine learning models while being agnostic to cloud computing services. It does *not*
focus on operationalizing production grade machine learning services.

A typical project structure looks like this:

```bash
├───datasets
│   ├───training
│   └───validation
├───models
├───notebooks
│   └───.ipynb_checkpoints
├───tests
└───utils
```

Things I want to add:
- Experiment logging
- Different templates for `pyTorch` and `sk-learn`
