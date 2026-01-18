# Spam Classification (TF-IDF + Logistic Regression)

This repository contains the course project for **COMP4602 - Natural Language Processing**: spam classification using a classical NLP pipeline (**TF-IDF + Logistic Regression**), comparing a reproducible **baseline** model against a **hyperparameter-optimized** model across three datasets.

## Contents
- `notebooks/`
  - `21SOFT1055_NLP_Project3_Dataset1_SMS.ipynb` (SMS Spam)
  - `21SOFT1055_NLP_Project3_Dataset2_LingSpam.ipynb` (Ling-Spam)
  - `21SOFT1055_NLP_Project3_Dataset3.ipynb` (Large Email Dataset)
- `report/Final_Report.pdf` (6 pages)
- `requirements.txt`

## Method (Summary)
Pipeline (used in all notebooks):
1. TF-IDF vectorization
2. Logistic Regression classifier

We first report a **baseline** (default parameters). Then we apply **RandomizedSearchCV** (3-fold) to tune TF-IDF and Logistic Regression hyperparameters and report the tuned results.

## Key Results (Accuracy)
- Dataset 1 (SMS): Baseline **0.968** -> Tuned **0.982**
- Dataset 2 (Ling-Spam): Baseline **0.967** -> Tuned **0.993**
- Dataset 3 (Large Email): Baseline **0.970** -> Tuned **0.990**

See the PDF report for full metrics and confusion matrices.

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open and run notebooks in `notebooks/`.

## Author
- (Add your name + student id here)
