# Healthcare AI & Machine Learning Project

This project explores the use of machine learning and large language models for healthcare prediction tasks using emergency department data.

The project was completed as part of a university capstone project and involved data preprocessing, model development, evaluation, and comparison between traditional machine learning models and large language models.

## My Contribution

My main contributions included:

- Data cleaning and preprocessing using Python and Pandas
- Developing a complaint-only Logistic Regression baseline
- Training and evaluating Logistic Regression, Decision Tree, Random Forest and XGBoost models
- Hyperparameter tuning for XGBoost
- Evaluating under-triage and over-triage performance
- Developing and testing LLM-based prediction workflows
- Comparing machine learning and LLM performance
- Working collaboratively using Git and GitHub

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Matplotlib
- Git / GitHub
- Large Language Models

## Task 1 – Emergency Triage Prediction

The first task involved predicting emergency department triage acuity levels using information available early in the patient journey.

Features included:

- Chief complaint
- Detailed chief complaint
- Temperature
- Heart rate
- Respiratory rate
- Oxygen saturation
- Blood pressure
- Gender
- Arrival transport

The final classification task predicted acuity levels 1–4.

### Results

The complaint-only Logistic Regression baseline achieved approximately:

- Accuracy: 68.5%

The tuned XGBoost model achieved approximately:

- Accuracy: 72.1%
- Macro F1: 0.53
- Weighted F1: 0.72
- Under-triage rate: 20.5%
- Over-triage rate: 29.8%

## Task 2 – LLM Evaluation

Large language models were also evaluated using clinical text and early vital signs.

The purpose of this experiment was not to deploy an LLM as a clinical decision-making system, but to compare its behaviour with traditional machine learning approaches.

The results showed that LLMs could behave conservatively and produce high over-triage rates, highlighting limitations in using zero-shot LLMs as standalone clinical predictors.

## Key Learning

This project gave me practical experience in:

- Building end-to-end machine learning workflows
- Working with imbalanced datasets
- Evaluating models beyond accuracy
- Understanding the importance of safety-related metrics
- Comparing traditional ML methods with LLM-based approaches
- Working with real-world healthcare-style data

## Important Note

This repository is a portfolio version of a university team project.

It contains only material that I am permitted to share publicly and focuses on my own contribution. Sensitive, private, or restricted project data is not included.
