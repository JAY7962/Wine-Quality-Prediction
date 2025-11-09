# 🍷 Wine Quality Prediction using Machine Learning

## 📘 Project Overview
This project aims to **predict the quality of wine** based on various **physicochemical properties** such as acidity, sugar content, and alcohol concentration.  
By leveraging machine learning algorithms, the project helps in **automating wine quality assessment**, thereby improving **quality control** and **production efficiency** in the wine industry.

---

## 📊 Dataset Description

The dataset contains several physicochemical features (inputs) and a quality score (output).  
Below is the list of features and their descriptions:

| Feature | Description |
|----------|--------------|
| fixed acidity | Amount of nonvolatile acids |
| volatile acidity | Amount of acetic acid in wine |
| citric acid | Weak organic acid present in wine |
| residual sugar | Amount of sugar remaining after fermentation |
| chlorides | Amount of salt in the wine |
| free sulfur dioxide | Free form of SO₂ for preservation |
| total sulfur dioxide | Total concentration of SO₂ |
| density | Density of the wine |
| pH | Level of acidity or basicity |
| sulphates | Wine additive that contributes to SO₂ gas |
| alcohol | Percentage of alcohol content |
| quality | Quality score assigned by wine tasters (0–10) |

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Checked for **missing values** and **duplicates**
- **Scaled numerical features** for better uniformity
- **Split** the dataset into training and testing sets

### 2. Exploratory Data Analysis (EDA)
- Analyzed relationships between physicochemical features and wine quality  
- Visualized the **distribution of each feature** and **correlation heatmap**

📈 *Example Visualizations:*  
- Feature distribution plots  
- Correlation heatmap  
- Pair plots of key variables  

### 3. Model Building
Built and compared three machine learning classifiers:

- **Logistic Regression**
- **XGBoost**
- **Support Vector Machine (SVM)**

### 4. Model Evaluation
Models were evaluated using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

Additionally, **Confusion Matrices** were generated to visualize classification performance.

---

## 🧾 Results and Discussion

| Model | Accuracy | Precision (avg) | Recall (avg) | F1-Score (avg) |
|--------|-----------|----------------|---------------|----------------|
| Logistic Regression | 0.74 | 0.72 | 0.69 | 0.70 |
| XGBoost | **0.82** | **0.81** | **0.80** | **0.81** |
| SVM | 0.75 | 0.73 | 0.70 | 0.70 |

✅ **XGBoost** achieved the best performance across all metrics, making it the most suitable model for wine quality prediction.

---

## 🧩 Technologies Used

| Category | Tools / Libraries |
|-----------|-------------------|
| Programming Language | Python 3.8+ |
| Data Handling | pandas, numpy |
| Data Visualization | matplotlib, seaborn |
| Machine Learning | scikit-learn, xgboost |
| Environment | Jupyter Notebook |



