# Analyzing and Predicting Traffic Crash Severity  
**High-Risk Factors and Enhancing Road Safety**  

## 📌 Project Overview  
Traffic accidents pose a major threat to public safety, causing severe injuries, fatalities, and financial losses. This project focuses on analyzing traffic crash data using **Apache Spark (PySpark)** to identify key factors influencing crash severity. We apply **machine learning models** to predict crash outcomes and compare distributed vs. non-distributed approaches for efficiency and accuracy.  

## 🚀 Features  
- **Distributed Data Processing** with PySpark for large-scale datasets  
- **Machine Learning Models** to predict crash severity  
- **Data Cleaning & Preprocessing** (Handling missing values, outliers, and feature scaling)  
- **Model Evaluation** (Accuracy, Precision, Recall, F1 Score)  
- **DAG Visualizations** for tracking Spark job execution  

## 📊 Dataset Description  
The dataset includes detailed information about crashes, such as:  
- **Crash Details**: Date, Type, Trafficway, Road Defects  
- **Weather & Road Conditions**: Lighting, Surface Conditions  
- **Vehicle & Injury Info**: Number of Vehicles, Fatal & Incapacitating Injuries  

## 🔧 Technologies Used  
- **PySpark** for distributed data processing  
- **Machine Learning Models**: Random Forest, XGBoost, Logistic Regression, Decision Tree, SVM, Naïve Bayes  
- **Data Visualization**: Matplotlib, Seaborn, Pandas  
- **Apache Spark DAG Execution**  

## 📈 Model Performance Comparison  
| Model            | Accuracy | F1 Score | Training Time (PySpark) |
|-----------------|----------|----------|-------------------------|
| **XGBoost**     | 89.06%   | 0.8532   | 129.02s                 |
| **Decision Tree** | 89.05%  | 0.8557   | 15.87s                  |
| **Random Forest** | 88.68%  | 0.8318   | 46.43s                  |
| **Logistic Regression** | 88.67% | 0.8318 | 27.60s                 |
| **SVM**         | 88.12%   | 0.8256   | 24.11s                  |
| **Naïve Bayes** | 87.62%   | 0.8248   | 9.82s                   |

**Key Finding**: **XGBoost performed the best**, but **PySpark significantly reduced training times** across all models.  

## 🏗️ Installation & Setup  
### **Prerequisites**  
- Python 3.x  
- Apache Spark & PySpark  
- Jupyter Notebook (Optional)  

### **Installation Steps**  
1. Clone this repository:  
   ```sh
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
