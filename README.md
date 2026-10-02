# 📊 Data Science Techniques Applied to Customer Review Analysis for Delivery Agents

A **Data Science and Machine Learning project** that analyzes customer reviews and delivery-related data to understand **customer satisfaction, delivery performance, order accuracy, and delivery-agent performance**.

The project applies data preprocessing, exploratory data analysis, statistical analysis, data visualization, regression, and classification techniques to extract meaningful insights from the dataset.

---

## 📌 Project Overview

Customer reviews and delivery information contain valuable insights about the quality of delivery services.

This project analyzes the available data to understand factors that may influence customer satisfaction and delivery performance.

The analysis covers:

* Customer ratings
* Delivery time
* Delivery-agent performance
* Order accuracy
* Customer service
* Order type
* Price range
* Discounts
* Product availability
* Customer feedback

The complete implementation is available in the **`Fast Delivery Agent Reviews(IDS).ipynb`** notebook.

---

## 🎯 Objectives

* Analyze customer review and delivery data.
* Understand customer satisfaction patterns.
* Analyze delivery-agent performance.
* Study the relationship between delivery time and ratings.
* Analyze order accuracy and customer ratings.
* Apply statistical techniques to the dataset.
* Build Machine Learning models for prediction.
* Evaluate the performance of the models.
* Generate meaningful business insights.

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning & Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Statistical Analysis
   ↓
Feature Preparation
   ↓
Machine Learning
   ↓
Model Evaluation
   ↓
Insights & Conclusions
```

---

## 🧹 Data Preprocessing

The project performs several data preparation steps before analysis and model building.

### Main preprocessing techniques

* Checking dataset structure
* Handling missing values
* Checking data types
* Data cleaning
* Feature selection
* Label encoding
* Preparing data for Machine Learning

### Label Encoding

`LabelEncoder` from Scikit-learn is used to convert categorical values into numerical values so that they can be used by Machine Learning models.

---

## 📊 Exploratory Data Analysis

Exploratory Data Analysis is performed to understand patterns and relationships within the dataset.

The project analyzes:

### ⭐ Customer Ratings

Customer ratings are analyzed to understand overall customer satisfaction.

### 🚚 Delivery Time

Delivery time is analyzed to understand its relationship with customer ratings and service quality.

### 👤 Delivery-Agent Performance

Delivery-agent-related data is analyzed to identify differences in customer feedback and performance.

### ✅ Order Accuracy

Order accuracy is examined to understand its relationship with customer satisfaction.

### 💬 Customer Feedback

Customer feedback is analyzed to identify patterns in customer experiences.

### 💰 Price & Discounts

Price ranges and discounts are explored to understand their relationship with customer behavior and ratings.

---

## 📈 Data Visualization

The project uses different visualization techniques to identify patterns and communicate findings clearly.

### Visualization Libraries

* **Matplotlib**
* **Seaborn**

Examples of analysis include:

* Rating distributions
* Delivery-time distributions
* Correlation analysis
* Comparison charts
* Classification visualizations
* Regression-related plots

---

## 📐 Statistical Analysis

The project uses **SciPy** for statistical analysis.

```python
from scipy import stats
```

Statistical techniques are used to investigate relationships and patterns in the dataset.

---

# 🤖 Machine Learning

The project also applies Machine Learning techniques to the delivery and customer-review data.

## 1. Train-Test Split

The dataset is divided into training and testing sets using:

```python
from sklearn.model_selection import train_test_split
```

This allows the models to be trained on one portion of the data and evaluated on unseen data.

---

## 2. Linear Regression

**Linear Regression** is used for regression-based prediction tasks.

```python
from sklearn.linear_model import LinearRegression
```

The model is evaluated using metrics such as:

* Mean Squared Error
* Mean Absolute Error
* R² Score

---

## 3. Logistic Regression

**Logistic Regression** is used for classification tasks.

```python
from sklearn.linear_model import LogisticRegression
```

The classification model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

## 📏 Model Evaluation

The project uses Scikit-learn evaluation metrics to measure Machine Learning model performance.

### Regression Metrics

* **Mean Squared Error (MSE)**
* **Mean Absolute Error (MAE)**
* **R² Score**

### Classification Metrics

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **Confusion Matrix**
* **Classification Report**

These metrics help determine how well the trained models perform on the test data.

---

## 🛠️ Technology Stack

### Programming Language

* **Python**

### Data Analysis

* **Pandas**
* **NumPy**

### Data Visualization

* **Matplotlib**
* **Seaborn**

### Machine Learning

* **Scikit-learn**

### Statistical Analysis

* **SciPy**

### Development Environment

* **Jupyter Notebook**
* **Google Colab**

---

## 📚 Libraries Used

```text
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
SciPy
```

### Purpose of Each Library

| Library          | Purpose                                           |
| ---------------- | ------------------------------------------------- |
| **Pandas**       | Data loading, cleaning, manipulation and analysis |
| **NumPy**        | Numerical operations                              |
| **Matplotlib**   | Data visualization                                |
| **Seaborn**      | Statistical visualization                         |
| **Scikit-learn** | Machine Learning, preprocessing and evaluation    |
| **SciPy**        | Statistical analysis                              |

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/prakruthidevanga/Data-Science-Techniques-Applied-to-Customer-Review-Analysis-for-Delivery-Agents.git
```

### 2. Navigate to the Project

```bash
cd Data-Science-Techniques-Applied-to-Customer-Review-Analysis-for-Delivery-Agents
```

### 3. Open the Notebook

Open:

```text
Fast Delivery Agent Reviews(IDS).ipynb
```

You can run the notebook using:

* **Google Colab**
* **Jupyter Notebook**
* **JupyterLab**

### 4. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

### 5. Run the Notebook

Execute the cells sequentially to reproduce the data analysis, visualizations, Machine Learning models, and evaluation results.

---

## 💡 Key Questions Addressed

The project explores questions such as:

* How satisfied are customers with the delivery service?
* How does delivery time affect customer ratings?
* How does order accuracy relate to customer satisfaction?
* What patterns can be observed in delivery-agent performance?
* Which factors are associated with customer ratings?
* Can Machine Learning models be used to predict outcomes from the available data?

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Python for Data Science
* Data preprocessing
* Data cleaning
* Exploratory Data Analysis
* Statistical analysis
* Data visualization
* Feature preprocessing
* Label encoding
* Train-test splitting
* Linear Regression
* Logistic Regression
* Model evaluation
* Business-oriented data analysis
* Extracting insights from customer and delivery data

---

## 🔮 Future Enhancements

Possible future improvements include:

* NLP-based sentiment analysis of customer reviews
* Advanced Machine Learning models
* Customer satisfaction prediction
* Delivery-agent performance prediction
* Interactive Power BI dashboard
* Real-time review analysis
* Automated business reports
* Deep Learning-based text analysis
* Deployment as a web application

---

## 👩‍💻 Author

**Prakruthi BR**

BCA – Artificial Intelligence & Machine Learning


**Project Repository:**
https://github.com/prakruthidevanga/Data-Science-Techniques-Applied-to-Customer-Review-Analysis-for-Delivery-Agents
