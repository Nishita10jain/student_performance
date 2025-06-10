# Student Performance Prediction using Machine Learning
Machine learning models to predict student academic performance using demographic and behavioral data

This project aims to predict student performance (final grades) using various supervised machine learning algorithms. The dataset contains demographic, social, and academic data of secondary school students. Our model helps identify students at risk and can assist educators in providing early interventions.

📊 Project Overview

I explored and applied several classification algorithms to accurately predict the final grade (G3) of students based on attributes like parental education, study time, failures, absences, and more.

🔍 Problem Statement

Student underperformance is a growing concern, and early identification of low-performing students can help educators intervene in time. This project uses historical student data to build predictive models for academic success.

🧰 Technologies Used

- Python 3  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Jupyter Notebook

📁 Dataset

The dataset was taken from the UCI Machine Learning Repository:

- **Student Performance Data Set**
- Attributes include: study time, past failures, absences, parental background, internet access, etc.

🧪 ML Models Implemented

- Logistic Regression  
- Decision Tree Classifier  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Support Vector Machine (SVM)

We used train-test split for model evaluation and accuracy metrics to compare performance.

📈 Results

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 0.70     |
| Decision Tree       | 0.68     |
| KNN                 | 0.66     |
| Naive Bayes         | 0.64     |
| SVM                 | 0.72     |

> 📌 *Support Vector Machine (SVM)* achieved the best accuracy in the experiments.



📷 Visualizations

The notebook includes:
- Correlation heatmaps  
- Bar plots of feature importance  
- Accuracy comparison charts for different models



📝 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/nishta10jain/student-performance-ml.git
