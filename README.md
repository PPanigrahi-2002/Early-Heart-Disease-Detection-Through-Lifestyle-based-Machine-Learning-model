# 🫀 Early Heart Disease Detection using Lifestyle-Based Machine Learning Models

This project leverages machine learning techniques to predict the risk of heart disease using a combination of clinical indicators, lifestyle habits, and behavioral factors. The model is built on data derived from the Framingham Heart Study, aiming to assist in early diagnosis and preventive healthcare.

## 📁 Dataset

The data used in this project comes from the publicly available [Framingham Heart Study](https://www.kaggle.com/datasets/sciencely/framingham-heart-study). It was divided into three subsets:
- `HR_survey.csv`
- `life.csv`
- `life2.csv`

These were merged into a comprehensive dataset named `final_merge.csv` consisting of 3,390 records and 27 features.

## 🧪 Models Used

Three supervised machine learning models were implemented and evaluated:
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Multi-Layer Perceptron (MLP)**

Each model was tested on both the `HR_survey` dataset and the merged dataset to observe the impact of enriched lifestyle data.

## 📊 Results

| Model | HR_survey Accuracy | final_merge Accuracy |
|-------|---------------------|----------------------|
| KNN   | 84.03%              | 86.28%               |
| SVM   | 85.86%              | **89.82%**           |
| MLP   | 85.19%              | 87.76%               |

Hyperparameter tuning further improved performance, with SVM and MLP reaching close to 90% accuracy.

## ⚙️ Key Features

- Data cleaning, merging, and transformation
- Feature encoding and scaling
- Model evaluation and accuracy comparison
- Hyperparameter tuning
- Visualization of model performance

## 🛠 Technologies Used

- Python (Scikit-learn, Pandas, NumPy)
- Jupyter Notebook / VS Code
- Matplotlib for visualization

## 📌 Conclusion

This project shows that combining lifestyle and clinical data can significantly improve the accuracy of heart disease predictions. SVM with the RBF kernel and MLP with optimized hidden layers showed the best performance.
