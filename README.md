# 🤖 AI/ML Task 2 – California Housing Regression

## 📌 Project Overview

This project is part of an **Artificial Intelligence & Machine Learning – Task 2** focused on **Feature Engineering, Model Optimization, and Performance Comparison**.

The project uses the **California Housing Dataset** to prepare data, engineer features, train different regression models, evaluate their performance, and compare the results.

## 🎯 Objectives

* Perform data analysis and preprocessing
* Apply feature engineering techniques
* Perform feature scaling
* Split the dataset into training and testing data
* Build regression machine learning models
* Optimize model parameters
* Evaluate models using RMSE and R²
* Compare model performance
* Visualize actual and predicted values

## 📊 Dataset

The project uses the **California Housing Dataset** available through Scikit-learn.

The dataset contains information related to California housing districts and their median house values.

## 🛠️ Technologies Used

* **Python**
* **Google Colab**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Scikit-learn**

## 🤖 Machine Learning Models

The following regression models are implemented:

1. **Linear Regression**
2. **Ridge Regression**
3. **Decision Tree Regressor**

## 🔄 Project Workflow

```text
Dataset Loading
      ↓
Data Exploration
      ↓
Data Preprocessing
      ↓
Feature Engineering
      ↓
Feature Scaling
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Hyperparameter Optimization
      ↓
Model Evaluation
      ↓
Performance Comparison
      ↓
Data Visualization
```

## 🔧 Feature Engineering

Additional features are created from the existing dataset features to improve the representation of the data.

Examples include:

* Rooms per Household
* Bedrooms per Room
* Population per Household

## ⚖️ Feature Scaling

**StandardScaler** from Scikit-learn is used to scale the numerical features before training the applicable regression models.

## 📈 Model Evaluation

The models are evaluated using:

### RMSE

**Root Mean Squared Error (RMSE)** measures the difference between actual and predicted values.

Lower RMSE indicates smaller prediction errors.

### R² Score

**R² Score** measures how well the model explains the variation in the target values.

## 📊 Visualization

The project includes **Actual vs Predicted** plots to visualize model predictions and understand model behavior.

## 📁 Project Structure

```text
California-Housing-Task-2/
│
├── AI_ML_Task_2_California_Housing.ipynb
├── README.md
└── model_comparison.csv
```

## ▶️ How to Run

### Using Google Colab

1. Open the `.ipynb` file.
2. Click **Open in Colab** or upload the notebook to Google Colab.
3. Run the cells from top to bottom.
4. Check the model evaluation results and graphs.

### Using Jupyter Notebook

Install the required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn
```

Then open the notebook and run the cells.

## 📌 Results

The trained models are compared using **RMSE and R² Score**.

The comparison helps understand the prediction performance of the different regression approaches.

## 📚 Learning Outcomes

Through this project, I practiced:

* Data preprocessing
* Feature engineering
* Feature scaling
* Regression algorithms
* Hyperparameter tuning
* Model evaluation
* Data visualization
* Python and Scikit-learn

## 👨‍💻 Author

**Shaik Mahammad Aakhil**

B.Tech – Artificial Intelligence & Machine Learning

QIS College of Engineering and Technology

## 🔗 Project

**GitHub:**
https://github.com/mahammadaakhil-cmd/California-Housing-Task-2

---

⭐ If you find this project useful, feel free to explore the repository.
