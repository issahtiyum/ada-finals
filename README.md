# Group 4: Counting Important Cross Period Pairs

Haris Issah: 41942028
Gabriel Akurang: 35882028
Ewurakoa Amoah: 74492028
Ebow Esselfie: 88872028


```
Customer Data -> Random Forest -> Churn Probability -> Explanation -> LLM -> Retention Strategy
```

## Setup

```bash
pip install -r requirements.txt

```

## What you need in place

| File | Purpose |
|---|---|
| `final_project-sandbox` | Jupyter notebook containing brute-force implementation, modified merge sort implementation,tests and experiment |




To do: install libraries in requirements.txt

## Description
The code seeks to export two algorithmic approaches to counting important cross pairs. The condition was to count pairs satisfying the condition

**Given integers** \(a_1, \ldots, a_n\), count pairs satisfying \(i < j\) and \(a_i > 2a_j\).
brute
merge
experimentation

- **Dashboard** — overall churn stats and highest-risk customers
- **Customer Analysis** — pick an existing customer, or enter one manually, to see their churn risk and what's driving it
- **AI Retention Strategy** — generates recommended retention actions for the analyzed customer
- **About** — explains the model, threshold, and known limitations

## Project structure

```
app.py
models/
  randomforest_fair.pkl
  randomforest.pkl
  scaler.pkl
data/
  E Commerce Dataset.xlsx
  Test Data.xlsx
src/
  preprocessing.py   # feature engineering + encoding
  prediction.py       # model loading + prediction (0.39 threshold)
  explanation.py      # why a customer is flagged as at-risk
  llm.py               # retention strategy generation via Groq/Llama

requirements.txt
final_project.ipynb #Analysis the data and training models
driver.ipynb  #conduct test in the terminal before app build
requirements.txt

```
