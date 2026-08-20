#  Human Activity Recognition using Smartphone Sensor Data

**Research Internship Project** — NIT Jalandhar (June – July 2025)
Conducted under the mentorship of **Dr. Samayveer Singh**, Assistant Professor, NIT Jalandhar

---

##  Overview

This project builds and evaluates multiple machine learning and deep learning models to classify human physical activities — walking, walking upstairs, walking downstairs, sitting, standing, and laying — using the **UCI HAR (Human Activity Recognition) dataset** collected from smartphone accelerometer and gyroscope sensors.

The goal was to compare classical ML approaches against a neural network model, apply dimensionality reduction, and identify the most effective technique for accurate, real-world activity recognition.

---

## 🔹 What Was Done

- Extracted and preprocessed the UCI HAR dataset (561 features, 10,299 samples across 6 activity classes)
- Performed exploratory data analysis using NumPy, Pandas, Matplotlib, and Seaborn
- Applied **Linear Discriminant Analysis (LDA)** for dimensionality reduction
- Built and trained multiple classification models:
  - Logistic Regression
  - Decision Tree
  - K-Nearest Neighbors
  - Support Vector Machine (SVM)
  - Random Forest
  - Bagging Classifier (with GridSearchCV tuning)
  - Dense Neural Network (Keras/TensorFlow)
  - Voting Ensemble models
- Visualized class separability using **t-SNE**
- Validated results using **5-fold cross-validation**
- Compared all models using accuracy, precision, recall, F1-score, and confusion matrices

---

##  Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Data Handling & EDA | NumPy, Pandas, Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Deep Learning | TensorFlow, Keras |
| Techniques | LDA, t-SNE, GridSearchCV, Cross-Validation, Ensemble Learning (Voting, Bagging) |

---

## 📊 Results

| Model | Accuracy |
|---|---|
| **Ensemble (Logistic Regression + KNN)** | **96.64%** ✅ Best |
| Logistic Regression | 96.50% |
| Neural Network (Dense/MLP) | ~96.7% (weighted F1) |
| K-Nearest Neighbors | 96.44% |
| Support Vector Machine | 96.30% |
| Random Forest | 96.23% |
| Bagging (tuned via GridSearchCV) | 96.13% |
| Decision Tree | 95.52% |

**5-fold cross-validation** (Logistic Regression base) achieved a mean accuracy of **98.49% (± 0.87%)**, confirming the robustness of the model beyond a single train/test split.

---

## Conclusion

This project successfully developed a Human Activity Recognition system using smartphone sensor data and machine learning. The **Voting Ensemble of Logistic Regression and KNN** achieved the highest test accuracy at **96.64%**, narrowly outperforming standalone Logistic Regression (96.50%). This demonstrates that combining lightweight, well-regularized models can match or exceed more complex approaches when paired with strong feature engineering (LDA-based dimensionality reduction).

---

##  Key Learnings

- Hands-on experience applying classical ML and deep learning to real-world sensor datasets
- Practical exposure to dimensionality reduction (LDA), ensemble methods (Voting, Bagging), and hyperparameter tuning (GridSearchCV)
- Improved skills in model selection, evaluation, and performance optimization
- Research exposure and mentorship under **Dr. Samayveer Singh** at NIT Jalandhar

---

##  Repository Contents

🔹 Key Learnings

Practical experience in applying machine learning and deep learning techniques on real-world sensor datasets.
Improved skills in model selection, evaluation, and performance optimization.
Gained research exposure and mentorship experience at NIT, Jalandhar.



---

## 👤 Author

**Sargun Kaur** -
Research Intern, NIT Jalandhar (June – July 2025)
[GitHub](https://github.com/Sargunnn)
