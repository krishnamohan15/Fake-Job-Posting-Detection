# 🔍 Fake Job Posting Detection System

## Machine Learning Based Fraudulent Job Posting Detection

A Natural Language Processing (NLP) and Machine Learning based system designed to identify potentially fraudulent job postings.

The system analyzes information such as job title, company profile, job description, requirements, benefits and other textual information to classify a job posting as **Legitimate** or **Potentially Fraudulent**.

---

## 📌 Project Overview

Online job platforms contain a large number of legitimate employment opportunities, but fraudulent job postings can also appear and potentially mislead job seekers.

This project uses Natural Language Processing and Machine Learning techniques to automatically analyze job-posting text and identify patterns associated with fraudulent postings.

The project includes:

- Exploratory Data Analysis
- Data cleaning
- Duplicate detection and removal
- Text preprocessing
- TF-IDF feature extraction
- Multiple Machine Learning models
- Model comparison
- Cross-validation
- Hyperparameter tuning
- Model evaluation
- Feature interpretation
- Prediction system
- Interactive Gradio web interface

---

## 🎯 Objectives

The main objectives of this project are:

1. Analyze a dataset containing legitimate and fraudulent job postings.
2. Understand the characteristics of fraudulent job advertisements.
3. Clean and preprocess textual job-posting information.
4. Convert textual data into numerical features using TF-IDF.
5. Train multiple Machine Learning classification models.
6. Compare model performance using different evaluation metrics.
7. Improve model performance using feature engineering and hyperparameter tuning.
8. Build a system capable of analyzing previously unseen job postings.
9. Develop an interactive interface for users to test job postings.
10. Demonstrate how NLP and Machine Learning can assist in identifying potentially fraudulent job advertisements.

---

# 📊 Dataset

The project uses a dataset containing job posting information and a target variable indicating whether a posting is fraudulent.

### Dataset Information

| Property | Value |
|---|---:|
| Original Records | 17,880 |
| Duplicate Records | 235 |
| Records After Duplicate Removal | 17,645 |
| Fraudulent Postings | 866 |
| Legitimate Postings | 17,014 |
| Target Variable | `fraudulent` |

The target variable is binary:

```text
0 → Legitimate
1 → Fraudulent
