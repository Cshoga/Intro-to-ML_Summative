# Student Academic Outcome Prediction Using Machine Learning and Deep Learning

## Project Overview

This project investigates the use of Machine Learning (ML) and Deep Learning (DL) techniques to predict student academic outcomes. The goal is to identify whether a student is likely to Graduate, Drop Out, or Remain Enrolled based on demographic, academic, and socioeconomic factors.

The project was completed as part of a comparative study between traditional machine learning methods and neural network-based deep learning approaches. Multiple experiments were conducted to evaluate model performance and understand the strengths and limitations of each approach.

---

## Problem Statement

Student dropout remains a major challenge in higher education institutions. Early identification of students who may be at risk can help universities provide timely support and interventions.

This project aims to answer the following question:

**Can machine learning and deep learning models accurately predict student academic outcomes using historical student data?**

---

## Dataset

The dataset used in this project is the **Predict Students' Dropout and Academic Success Dataset**, obtained from an open-source repository.

Target Classes:

* Graduate
* Enrolled
* Dropout

Dataset Characteristics:

* 4,424 student records
* 36 input features
* Multi-class classification problem

Features include:

* Academic performance indicators
* Enrollment information
* Demographic information
* Financial information

---

## Project Structure

```text
├── Student_academic_prediction_notebook_celine_shoga.ipynb
├── data.csv
├── README.md
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* TensorFlow / Keras
* Google Colab

---

## Machine Learning Models

The following traditional machine learning models were implemented:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Support Vector Machine (SVM)

---

## Deep Learning Models

The following neural network architectures were implemented:

### Sequential API Models

* Neural Network with one hidden layer
* Neural Network with two hidden layers
* Neural Network with dropout regularization

### Functional API Models

* Functional Neural Network Architecture
* Functional Neural Network with additional dense layers

Model summaries are included in the notebook to show the architecture and number of trainable parameters.

---

## Experiments Conducted

A total of 12 experiments were performed.

Examples include:

* Comparing different machine learning algorithms
* Varying neural network depth
* Testing dropout regularization
* Comparing Sequential and Functional APIs
* Evaluating learning rate and architecture changes

Performance metrics used:

* Accuracy
* Precision
* Recall
* F1 Score

---

## Visualizations

The notebook includes:

* Class distribution plots
* Correlation analysis
* Learning curves
* Confusion matrices
* ROC Curves
* Model comparison charts

These visualizations help explain model performance and identify areas where models struggle.

---

## How to Run the Project

### Option 1: Google Colab

1. Open the notebook in Google Colab.
2. Upload the dataset file (`data.csv`) or connect to GitHub.
3. Run all cells from top to bottom.

### Option 2: Local Environment

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
```

Run the notebook using:

```bash
jupyter notebook
```

Open:

```text
Student_academic_prediction_notebook_celine_shoga.ipynb
```

and execute all cells.

---

## Results Summary

The experiments demonstrate that both traditional machine learning and deep learning approaches can effectively predict student outcomes.

Key observations:

* Ensemble methods such as Random Forest generally achieved strong performance.
* Deep learning models required more training time but captured complex relationships in the data.
* Model performance varied depending on architecture and hyperparameter choices.
* Proper preprocessing and feature scaling significantly improved results.

---

## Limitations

* The dataset represents a specific educational context and may not generalize to all institutions.
* Class imbalance may affect prediction performance.
* Additional features such as attendance and engagement data could improve results.

---

## Author

**Celine Shoga**

Bachelor of Software Engineering

African Leadership University (ALU)

Machine Learning Specialization

---

## Report Documentation


---

## Video Presentation

Presentation Video:


