# Healthcare AI & Machine Learning Project

This repository presents selected work from my university capstone project involving machine learning and large language models for emergency department triage prediction.

The project focused on predicting triage acuity using information available early in a patient's emergency department visit, including chief complaints, vital signs and basic demographic information.

## My Contribution

My main contributions included:

- Data cleaning and preprocessing using Python and Pandas
- Developing a complaint-only Logistic Regression baseline
- Reproducing and evaluating multiple machine learning models
- Training and tuning an XGBoost model
- Evaluating model performance using accuracy, F1 score, confusion matrices, under-triage and over-triage
- Designing and testing an LLM-based triage prediction workflow
- Comparing traditional machine learning models with LLM predictions
- Collaborating with team members using Git and GitHub

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

## Machine Learning Results

A complaint-only Logistic Regression model was used as the baseline.

- Baseline accuracy: **68.54%**

After adding additional clinical features and tuning the model, the tuned XGBoost model achieved:

- Accuracy: **72.12%**
- Macro F1: **0.5271**
- Weighted F1: **0.7197**
- Under-triage rate: **20.5%**
- Over-triage rate: **29.8%**

## LLM Evaluation

Large language models were also tested using a zero-shot prompting approach.

For triage prediction:

- GPT accuracy: **43.54%**
- GPT under-triage rate: **11.22%**
- GPT over-triage rate: **57.66%**

The results showed that the LLM behaved more conservatively than the machine learning model, producing lower under-triage but substantially higher over-triage.

## Visual Results

### GPT vs Tuned XGBoost

![GPT vs Tuned XGBoost](images/GPT%20vs%20Tuned%20XGBoost.png)

Additional confusion matrices and evaluation figures are available in the `images` folder.

## Repository Structure

```text
images/
    Model comparison figures and confusion matrices

notebooks/
    Jupyter notebooks for machine learning reproduction and LLM experiments
