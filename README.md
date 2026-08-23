# 🤖 Machine Learning with Python

A practical **Machine Learning repository** containing algorithms, Jupyter Notebooks, datasets, trained models, and real-world projects implemented using **Python**.

This repository is created to build a strong understanding of Machine Learning through practical implementation rather than only theoretical concepts.

---

## 📌 About the Project

**Machine Learning (ML)** is a branch of Artificial Intelligence that enables computers to learn patterns from data and make predictions or decisions without being explicitly programmed for every task.

This repository contains practical Machine Learning projects covering:

* 📊 Data Preprocessing
* 🔍 Exploratory Data Analysis
* 🎯 Supervised Learning
* 📈 Regression
* 🏷️ Classification
* 🧠 Model Training
* 📏 Model Evaluation
* ❤️ Healthcare Prediction
* 🚗 Price Prediction
* 🏥 Insurance Prediction
* 🚢 Titanic Survival Prediction
* 🌐 Machine Learning Application using Streamlit

---

# 📚 Projects

## 1. 🏥 Insurance Prediction

**Notebook:** `Project_1(Insurance).ipynb`

This project demonstrates Machine Learning techniques using an insurance dataset.

### Key concepts:

* Data loading
* Data preprocessing
* Exploratory Data Analysis
* Feature selection
* Model training
* Prediction
* Model evaluation

### Dataset

```text
insurance.xls
```

---

## 2. ❤️ Heart Disease Prediction

**Notebook:** `Project_2(HeartDisease).ipynb`

This project focuses on predicting the possibility of heart disease using Machine Learning.

### Key concepts:

* Data preprocessing
* Feature selection
* Classification
* K-Nearest Neighbors (KNN)
* Feature scaling
* Model training
* Model prediction
* Model evaluation

### Project Files

```text
heart.xls
heart_columns.pkl
heart_scaler.pkl
knn_heart_model.pkl
```

A trained model and preprocessing files are included for the prediction application.

---

## 3. 🚗 Car Price Prediction

**Notebook:** `Project_3(car_price_prediction).ipynb`

This project demonstrates how Machine Learning can be used to predict the price of a car based on available features.

### Key concepts:

* Data preprocessing
* Feature analysis
* Regression
* Model training
* Prediction
* Model evaluation

### Example

```text
Car Features
     ↓
Data Preprocessing
     ↓
Feature Selection
     ↓
ML Model
     ↓
Predicted Car Price
```

---

## 4. 🚢 Titanic Survival Prediction

**Notebook:** `Supervised_learning(Titanic_models).ipynb`

This project demonstrates **Supervised Machine Learning** using the famous Titanic dataset.

The goal is to predict whether a passenger survived based on passenger-related features.

### Key concepts:

* Supervised Learning
* Classification
* Data preprocessing
* Feature engineering
* Model training
* Model evaluation
* Prediction

---

# 🧠 Machine Learning Concepts

## 1. Supervised Learning

In supervised learning, the model learns from data where the target/output is already known.

Examples:

* Classification
* Regression

### Example

```text
Input Data → Machine Learning Model → Known Target
```

---

## 2. Classification

Classification is used when the output belongs to a category.

Examples:

* Heart Disease → Yes / No
* Titanic → Survived / Not Survived
* Email → Spam / Not Spam

Common algorithms:

* Logistic Regression
* KNN
* Decision Tree
* Random Forest
* SVM
* Naive Bayes

---

## 3. Regression

Regression is used when the output is a continuous numerical value.

Examples:

* Car price prediction
* House price prediction
* Salary prediction
* Sales prediction

Common algorithms:

* Linear Regression
* Multiple Linear Regression
* Polynomial Regression
* Ridge Regression
* Lasso Regression

---

# 🔄 Machine Learning Workflow

The projects in this repository follow a general Machine Learning workflow:

```text
Dataset
   ↓
Data Collection
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Prediction
```

---

# 📊 Data Preprocessing

Data preprocessing is an important step before training a Machine Learning model.

Common preprocessing techniques include:

* Handling missing values
* Removing duplicates
* Encoding categorical variables
* Feature scaling
* Detecting outliers
* Feature selection
* Train-test splitting

---

# 📏 Model Evaluation

Machine Learning models need to be evaluated to determine their performance.

### Classification Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### Regression Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

# 🛠️ Technologies Used

| Technology          | Purpose                         |
| ------------------- | ------------------------------- |
| 🐍 Python           | Programming language            |
| 📓 Jupyter Notebook | Development and experimentation |
| 🧮 NumPy            | Numerical computing             |
| 🐼 Pandas           | Data manipulation               |
| 📊 Matplotlib       | Data visualization              |
| 🎨 Seaborn          | Statistical visualization       |
| 🤖 Scikit-learn     | Machine Learning algorithms     |
| 🌐 Streamlit        | ML application development      |
| 💾 Joblib/Pickle    | Model and preprocessing storage |

---

# 📂 Repository Structure

The current repository contains the following major files:

```text
Machine-Learning/
│
├── Project_1(Insurance).ipynb
├── Project_2(HeartDisease).ipynb
├── Project_3(car_price_prediction).ipynb
├── Supervised_learning(Titanic_models).ipynb
│
├── app.py
│
├── heart.xls
├── insurance.xls
│
├── heart_columns.pkl
├── heart_scaler.pkl
├── knn_heart_model.pkl
│
├── .gitattributes
└── README.md
```

The structure above reflects the files currently visible in the repository.

---

# 🌐 Heart Disease Prediction App

The repository also contains an `app.py` file that can be used as the application component for the Heart Disease Machine Learning project.

The trained model and preprocessing files include:

```text
knn_heart_model.pkl
heart_scaler.pkl
heart_columns.pkl
```

This allows the trained Machine Learning model to be integrated into an application.

---

# ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Monu-kumar-kushwaha/Machine-Learning.git
```

### 2. Navigate to the Project

```bash
cd Machine-Learning
```

### 3. Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter streamlit joblib
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open any `.ipynb` file and run the cells.

---

# 🌐 Run the Streamlit Application

If you want to run the application included in the repository:

```bash
streamlit run app.py
```

The application will open in your web browser.

---

# 🎯 Learning Objectives

After working with this repository, you will understand:

* What Machine Learning is
* Difference between supervised and unsupervised learning
* Classification and regression
* Data preprocessing
* Feature selection
* Feature scaling
* Model training
* Model evaluation
* Prediction
* Real-world ML applications
* Deployment of ML models using Streamlit

---

# 🌍 Real-World Applications

Machine Learning is widely used in:

* 🏥 Healthcare
* 💰 Finance
* 🚗 Automobile Industry
* 🛒 E-Commerce
* 🏦 Banking
* 🎬 Recommendation Systems
* 📧 Spam Detection
* 🔐 Fraud Detection
* 📈 Business Analytics
* 🤖 Artificial Intelligence

### Example

A healthcare organization can use Machine Learning to analyze patient data and predict the risk of a particular disease.

```text
Patient Data
     ↓
Data Preprocessing
     ↓
Trained ML Model
     ↓
Prediction
     ↓
Risk Assessment
```

---

# 📈 Skills Demonstrated

This repository demonstrates practical skills in:

* Python Programming
* Data Analysis
* Data Visualization
* Machine Learning
* Statistical Analysis
* Classification
* Regression
* Feature Engineering
* Model Evaluation
* Model Deployment

---

# 🔮 Future Improvements

Future additions to this repository may include:

* [ ] Linear Regression
* [ ] Logistic Regression
* [ ] Decision Tree
* [ ] Random Forest
* [ ] Support Vector Machine
* [ ] KNN
* [ ] Naive Bayes
* [ ] K-Means Clustering
* [ ] PCA
* [ ] Ensemble Learning
* [ ] Hyperparameter Tuning
* [ ] Cross-Validation
* [ ] More real-world datasets
* [ ] More ML projects
* [ ] Streamlit deployment
* [ ] Model comparison

---

# 📌 Important Machine Learning Topics

```text
Machine Learning
│
├── Data Preprocessing
│
├── Supervised Learning
│   ├── Regression
│   └── Classification
│
├── Unsupervised Learning
│   ├── Clustering
│   └── Dimensionality Reduction
│
├── Feature Engineering
│
├── Model Training
│
├── Model Evaluation
│
└── Model Deployment
```

---

# ⭐ Why This Repository?

This repository is focused on **learning Machine Learning through practical projects**.

Instead of studying algorithms only theoretically, the projects demonstrate how Machine Learning techniques can be applied to real datasets such as:

* Insurance
* Heart Disease
* Car Prices
* Titanic Passenger Data

This makes the repository useful for **students, beginners, Data Science learners, and aspiring Machine Learning Engineers**.

---

# 👨‍💻 Author

**Monu Kumar Kushwaha**

GitHub:
https://github.com/Monu-kumar-kushwaha

---

# ⭐ Support

If you find this repository useful, please consider giving it a ⭐ on GitHub.

Your support is appreciated and helps encourage more Machine Learning projects.

---

## 📄 License

This repository is created primarily for **educational and learning purposes**.
