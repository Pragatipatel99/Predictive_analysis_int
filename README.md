# 💻 Laptop Price Prediction and Classification using Machine Learning

This project focuses on analyzing laptop specifications and predicting laptop prices using various machine learning techniques. It also classifies laptops into different price categories and performs market segmentation to understand pricing patterns.

The project is implemented using Python and popular data science libraries, following a complete end-to-end machine learning workflow.

---

## 📌 Project Objectives

- To clean and preprocess real-world laptop data  
- To perform exploratory data analysis (EDA) and visualize key patterns  
- To predict laptop prices using regression models  
- To classify laptops into Low, Medium, and High price categories  
- To compare the performance of multiple machine learning algorithms  

---

## 📂 Dataset Information

- **Dataset Name:** Laptop Dataset  
- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/sushmita36/laptops-dataset  

### Key Features Used
- Company  
- TypeName  
- RAM (GB)  
- Weight (kg)  
- Price  

---

## 🛠️ Technologies & Libraries Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🔍 Project Workflow

1. **Data Loading**
   - Load dataset and remove unnecessary columns  

2. **Data Preprocessing**
   - Clean RAM, Weight, and Price columns  
   - Handle missing values  
   - Encode categorical variables  

3. **Exploratory Data Analysis (EDA)**
   - Price distribution analysis  
   - RAM vs Price visualization  
   - Correlation heatmap  

4. **Model Building**
   - Linear Regression (Price Prediction)  
   - K-Means Clustering (Market Segmentation)  
   - Decision Tree Classifier  
   - K-Nearest Neighbors (KNN)  
   - Naive Bayes Classifier  

5. **Model Evaluation**
   - R² Score for regression  
   - Accuracy and confusion matrix for classification  
   - Final model comparison  

---

## 📊 Machine Learning Models Used

| Model | Purpose |
|------|--------|
| Linear Regression | Predict laptop prices |
| K-Means Clustering | Segment laptops into price groups |
| Decision Tree | Price category classification |
| KNN | Distance-based classification |
| Naive Bayes | Probabilistic classification |

---

## ✅ Results Summary

- Linear Regression achieved a moderate R² score (~0.54)  
- KNN provided the highest classification accuracy (~74%)  
- RAM and Weight were found to be the most influential features  
- K-Means successfully grouped laptops into meaningful segments  

---

## 📁 Output Files

- `final_predictions.csv` – Stores actual vs predicted price categories  

---

## 🚀 How to Run the Project

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
