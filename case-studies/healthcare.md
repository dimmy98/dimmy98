# Healthcare billing prediction

**MSc dissertation · University of Sheffield · 2024**

[Repository](https://github.com/dimmy98/Developing-Evaluating-ML-for-HealthCare) · [Interactive dashboard](https://dimmy98.github.io/Developing-Evaluating-ML-for-HealthCare/) · [Back to profile](../README.md)

## The question

How do a linear baseline, a decision tree and a gradient boosting model compare when predicting medical insurance charges?

The project uses a public insurance dataset and examines demographic and lifestyle features, including age, BMI and smoking status.

## The approach

The reference workflow removes duplicate rows, encodes categorical inputs and predicts log-transformed charges. Models are compared using R² and mean squared error, with attention to the difference between training and test performance.

| Model | Reported test R² | Reported test MSE |
| :--- | ---: | ---: |
| Linear regression | 0.8025 | 0.0346 |
| Tuned decision tree | 0.8524 | 0.0258 |
| Gradient boosting | 0.8641 | 0.0238 |

These are the project's published historical results. They have not been independently reproduced during this profile refresh. MSE is on the transformed target scale.

## Why it is interesting

The comparison illustrates the value of starting with a baseline and checking overfitting before treating a more complex model as an improvement. The dashboard also explores how the chosen inputs affect predictions.

## What to inspect

- **Dashboard:** the reported workflow, comparison charts and feature analysis.
- **README:** the data source, reference Python implementation and reproduction notes.

## Limits and next questions

A small train/test gap on one split does not establish generalisation. Repeated evaluation, leakage checks and subgroup error analysis would provide stronger evidence.

The public repository currently presents the dashboard and reference implementation. Original dissertation experiments, trained models and raw data are not included.
