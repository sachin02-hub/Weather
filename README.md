# 🌤️ Weather Condition Prediction Using Machine Learning
This repository contains a machine learning project that focuses on predicting weather conditions using three different algorithms:

K-Nearest Neighbors (KNN)

Logistic Regression

Decision Tree

The models are trained and evaluated on three separate synthetic weather datasets, with a full workflow from data cleaning to model comparison.

## 📁 Project Structure

### 📦 Weather-condition-prediction
```bash
├── 📊 Logistic Regression.ipynb
├── 📊 KNN.ipynb
├── 📊 Decision Tree.ipynb
├── 📄 seattle-weather.csv
├── 📄 traffic_weather.csv
├── 📄 weather3.csv
└── 📑 Weather PPT (1).pdf
```

## 🔍 Datasets
Each dataset represents synthetic weather data with continuous and categorical features. The target variable in all three datasets is the weather condition.
```bash
├── seattle-weather.csv
├── traffic_weather.csv
├── weather3.csv
```

Data Cleaning Steps:
```bash
├── Removed missing values
├── Removed duplicates
├── Detected and eliminated outliers
```
## 🧠 Algorithms Used
### ✅ K-Nearest Neighbors (KNN)

Great performance on dataset 1

Simple yet effective for classification tasks

### ✅ Logistic Regression

Suitable for binary/multiclass classification

Interpretable model with solid baseline accuracy

### ✅ Decision Tree

Intuitive and visual model

Handles non-linear relationships well

## 📊 Model Performance (Test Accuracy)
| Algorithm            | Dataset 1 | Dataset 2 | Dataset 3 |
|----------------------|-----------|-----------|-----------|
| KNN                  | 0.99      | 0.78      | 0.53      |
| Logistic Regression  | 0.92      | 0.76      | 0.44      |
| Decision Tree        | 0.98      | 0.75      | 0.46      |

## 📈 Analysis Summary
🔹 KNN outperformed other models across all three datasets.

🔹 Dataset 1 showed the highest predictive performance across all models.

🔹 This suggests dataset 1 is the most suitable for modeling weather conditions in this context.

## 🧾 Conclusion
Through our analysis, KNN was found to be the most accurate model, and Dataset 1 emerged as the most reliable dataset for this problem. The project demonstrates how classic ML algorithms can be leveraged for weather prediction when paired with proper data preprocessing.

## 📎 Presentation
For a summary of this project and visual representation of results, check out the 📄 Weather Project Presentation (PDF)

