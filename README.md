# Network Intrusion Detection Using NSL-KDD

## Project Description

This project reproduces and critically evaluates a public machine-learning implementation for network intrusion detection using the NSL-KDD dataset.

The objective is to investigate whether classical machine-learning models can distinguish malicious network connections from legitimate traffic and whether the conclusions of the original source are supported by a more detailed experimental evaluation.

## Selected Source

Original GitHub repository:

https://github.com/Mamcose/NSL-KDD-Network-Intrusion-Detection

## Dataset

The project uses the NSL-KDD dataset.

Dataset repository:

https://github.com/jmnwong/NSL-KDD-Dataset

Required files:

- KDDTrain+.txt
- KDDTest+.txt

The notebook downloads these files automatically when they are not available locally.

## Models

The project evaluates:

- Logistic Regression
- Decision Tree
- Random Forest
- Dummy Classifier
- Isolation Forest

## Main Analysis

The notebook includes:

- Data loading and inspection
- Missing-value analysis
- Duplicate and constant-feature analysis
- Exploratory Data Analysis
- Class-prevalence analysis
- Outlier analysis
- Spearman correlation analysis
- Feature redundancy analysis
- Feature engineering
- Cross-validation
- Official test-set evaluation
- Threshold analysis
- Feature importance
- Error analysis by attack family
- Critical evaluation of the selected source

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- F2-score
- Matthews Correlation Coefficient
- ROC-AUC
- Confusion Matrix

## Repository Files

- `NSL_KDD_final_project.ipynb` – Complete executed notebook
- `Report.pdf` – Final written report
- `README.md` – Project documentation

## Execution Instructions

### Google Colab

1. Download or open `NSL_KDD_final_project.ipynb`.
2. Upload it to Google Colab.
3. Select **Runtime → Restart session and run all**.
4. Wait until all cells finish executing.

### Local Jupyter Notebook

Install the required packages:

```bash
pip install numpy pandas matplotlib scikit-learn
