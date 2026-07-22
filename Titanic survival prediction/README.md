# 🚢 Titanic Survival Prediction using Machine Learning

A machine learning classification project that predicts whether a passenger survived the Titanic disaster based on demographic and travel-related information.

---

# 📌 Project Objective

The objective of this project is to build a classification model that predicts passenger survival using historical Titanic data.

This project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, visualization, and model serialization.

---

# 📂 Dataset

**Dataset:** Titanic Dataset

**Target Variable:**
- `Survived`

**Target Classes:**
- `0` → Did Not Survive
- `1` → Survived

---

# 📊 Features Used

- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

---

# 🛠 Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle
- Jupyter Notebook

---

# 🤖 Machine Learning Algorithm

- Random Forest Classifier

---

# 🔄 Project Workflow

### 1. Import Required Libraries

Load all required Python libraries.

### 2. Load Dataset

Read the Titanic dataset using Pandas.

### 3. Data Exploration

- View dataset
- Check data types
- Statistical summary
- Missing values

### 4. Data Cleaning

- Fill missing Age values using Median
- Fill missing Embarked values using Mode
- Drop Cabin column
- Remove unnecessary columns

### 5. Feature Encoding

Convert categorical columns into numerical values using LabelEncoder.

### 6. Feature Selection

Split dataset into:

- Features (X)
- Target (y)

### 7. Train-Test Split

Split the dataset into training and testing sets.

### 8. Model Training

Train the Random Forest Classifier.

### 9. Prediction

Predict survival on the testing dataset.

### 10. Model Evaluation

Evaluate using:

- Accuracy Score
- Confusion Matrix
- Classification Report

### 11. Data Visualization

- Count Plot
- Bar Plot

### 12. Save Trained Model

Save the trained model using Pickle for future predictions.

---

# 📈 Model Performance

Evaluation Metrics:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# 📁 Project Structure

```
Titanic-Survival-Prediction/
│
├── Titanic-Dataset.csv
├── Titanic.ipynb
├── Titanic_Model.pkl
├── README.md
└── requirements.txt
```

---

# ▶️ How to Run

1. Clone the repository.

2. Install dependencies.

```
pip install -r requirements.txt
```

3. Open the notebook.

```
jupyter notebook
```

4. Run all cells.

---

# 📌 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Feature Engineering
- Model Comparison
- Deployment using Streamlit or Flask

---

# 👨‍💻 Author

**ARMAN**

B.Sc. Data Science Student

Machine Learning & Data Science Enthusiast

---

# ⭐ Project Highlights

- End-to-End Machine Learning Project
- Data Cleaning
- Feature Encoding
- Random Forest Classification
- Model Evaluation
- Data Visualization
- Model Serialization (.pkl)

---

## 📄 License

This project is created for educational and learning purposes.