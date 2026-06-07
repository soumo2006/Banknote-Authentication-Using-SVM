
💵 Banknote Authentication Using Support Vector Machine (SVM)

📌 Project Overview

This project uses Machine Learning to classify banknotes as Genuine or Forged based on statistical features extracted from banknote images.

A Support Vector Machine (SVM) classifier was trained on the Banknote Authentication Dataset and achieved excellent performance in detecting fake banknotes.

---

🎯 Objective

To build a machine learning model capable of identifying whether a banknote is genuine or forged using numerical features.

---

📊 Dataset Information

The dataset contains the following features:

- Variance
- Skewness
- Curtosis
- Entropy

Target Variable

- 0 → Forged Banknote
- 1 → Genuine Banknote

---

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

📈 Exploratory Data Analysis

The following analyses were performed:

- Dataset inspection
- Class distribution analysis
- Scatter plot visualization
- Correlation analysis

---

🤖 Machine Learning Model

Algorithm Used

Support Vector Machine (SVM)

Kernels Tested

- Linear Kernel
- Polynomial Kernel
- RBF Kernel

The RBF Kernel achieved the best performance and was selected as the final model.

---

⚙️ Workflow

1. Data Loading
2. Exploratory Data Analysis
3. Train-Test Split
4. Feature Scaling using StandardScaler
5. SVM Model Training
6. Prediction
7. Performance Evaluation
8. User Input Prediction System

---

📊 Evaluation Metrics

The model was evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix

Results

Metric| Score
Accuracy| 100%
Precision| 100%
Recall| 100%
F1 Score| 100%

---

🔍 Sample Prediction

The user can enter:

- Variance
- Skewness
- Curtosis
- Entropy

The model predicts:

✅ Genuine Banknote

or

❌ Forged Banknote

---

📷 Visualizations

- Scatter Plot
- Confusion Matrix

(Add screenshots inside the images folder and attach them here.)

---

🚀 Future Improvements

- Deploy using Streamlit
- Build a web application
- Compare with Logistic Regression, KNN, and Random Forest
- Real-time banknote verification system

---

👨‍💻 Author

Soumotirtha Das

B.Tech in Information Technology

RCC Institute of Information Technology
