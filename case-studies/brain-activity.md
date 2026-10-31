# Harmful brain activity classification

**University of Sheffield team project · HMS Kaggle competition**

[Team repository](https://github.com/supinfl/UoS_HBAC/tree/baseline) · [Back to profile](../README.md)

## The question

How can deep learning classify patterns of harmful brain activity from EEG-related inputs?

This team project explored spectrogram representations, EfficientNet models and two-stage training for the HMS competition. Representation choices and training procedures are central to the investigation.

## What is available

The linked baseline branch contains training and inference notebooks, local Python training and inference scripts, data-splitting code and experiment records.

Useful entry points include:

- [Two-stage training notebook](https://github.com/supinfl/UoS_HBAC/blob/baseline/2stageTrainning.ipynb)
- [Local training implementation](https://github.com/supinfl/UoS_HBAC/blob/baseline/local_train.py)
- [Local inference implementation](https://github.com/supinfl/UoS_HBAC/blob/baseline/local_inference.py)
- [Data splitting](https://github.com/supinfl/UoS_HBAC/blob/baseline/data_split.py)

## How to read this project

Start with the notebooks to understand the experiment flow, then compare the training and inference scripts. Read experiment records alongside their corresponding configuration and validation method.

This is a collaborative academic project. The linked code represents the team's work; this page does not assign individual contributions.

## Limits and next questions

A useful next review would examine patient-level separation, label uncertainty, class balance and performance on an independent dataset. Competition performance alone does not establish clinical readiness.
