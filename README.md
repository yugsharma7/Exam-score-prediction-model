# Exam-score-prediction-model
Exam score prediction

# 📚 Exam Score Prediction using Machine Learning

Predicting students' exam scores using Machine Learning by analyzing study habits, attendance, previous academic performance, and other relevant factors. This project demonstrates the complete ML workflow, from data preprocessing to model evaluation and comparison.

---

## 📌 Project Overview

Educational institutions can use predictive analytics to identify students who may need additional academic support. In this project, multiple regression algorithms are trained to predict students' exam scores based on various input features.

The project covers data cleaning, feature engineering, model training, evaluation, and comparison to determine the best-performing algorithm.

---

## 🚀 Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Handling categorical and numerical features
- Feature scaling using StandardScaler
- One-Hot Encoding for categorical variables
- Train-test split
- Multiple regression models
- Hyperparameter tuning for Decision Tree
- Model performance comparison

---

## 🗂 Dataset

The dataset contains student-related information such as:

- Student ID
- Study Hours
- Attendance
- Previous Scores
- Sleep Hours
- Extra Activities
- Internet Access
- Other academic and lifestyle factors

**Target Variable**

- Exam Score

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```
Exam-Score-Prediction/
│
├── Exam_Score_Prediction.ipynb
├── Exam_Score_Prediction.csv
├── README.md
├── requirements.txt
└── images/
    ├── correlation_heatmap.png
    ├── feature_distribution.png
    └── model_comparison.png
```

---

## 🤖 Machine Learning Models

The following regression models were implemented:

- Linear Regression
- K-Nearest Neighbors (KNN) Regressor
- Decision Tree Regressor
- Random Forest Regressor

Hyperparameter tuning was performed using **RandomizedSearchCV** for the Decision Tree model.

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Removing unnecessary columns
- Converting data types
- Handling categorical features
- One-Hot Encoding
- Standard Scaling
- Train-Test Split (80:20)

---

## 📊 Model Evaluation

Models were evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- R² Score

These metrics help compare the prediction accuracy of different regression models.

---

## 🔄 Workflow

1. Load dataset
2. Explore and clean data
3. Perform Exploratory Data Analysis
4. Preprocess features
5. Split data into training and testing sets
6. Train multiple regression models
7. Tune Decision Tree parameters
8. Evaluate model performance
9. Compare results
10. Predict exam scores

---

## 📈 Future Improvements

- Add XGBoost Regressor
- Perform advanced feature engineering
- Use cross-validation
- Build an interactive Streamlit web application
- Deploy the trained model
- Add SHAP for model explainability

---

## 💡 Skills Demonstrated

- Machine Learning
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Regression Models
- Model Evaluation
- Hyperparameter Tuning
- Python Programming
- Scikit-learn

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Exam-Score-Prediction.git
```

Navigate to the project folder:

```bash
cd Exam-Score-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📷 Results

The project compares the performance of multiple regression models to identify the most accurate predictor for student exam scores. Performance is evaluated using standard regression metrics such as MAE, RMSE, MAPE, and R² Score.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Yug Sharma**

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile

If you found this project helpful, please consider giving it a ⭐ on GitHub!
