# 📊 Social Media vs Productivity – Machine Learning Project

This project explores how social media usage patterns influence actual productivity levels using data analysis, preprocessing, and classification with multiple ML models, including neural networks, decision trees, and SVM.

---

## 🧠 Project Summary for CV

Developed a machine learning pipeline to analyze and classify productivity levels based on social media usage patterns, including model building, evaluation, and deep learning interpretation.

---

## 📂 Project Structure

- `social_media_vs_productivity.csv` — Dataset  
- `model_training.ipynb` — Main Jupyter Notebook with all steps  
- `README.md` — Project documentation  

---

## 📌 Key Features

- Data cleaning, outlier handling, and feature scaling  
- Productivity score categorization using quantile binning  
- Feature selection with SelectKBest (ANOVA F-score)  
- Multiclass classification using:  
  - Neural Networks (Keras + SciKeras)  
  - Decision Trees  
  - SVM (Support Vector Machines)  
- Performance evaluation with:  
  - Accuracy, Confusion Matrix, Classification Report  
  - ROC/AUC for multiclass  
- Model interpretability:  
  - Forward and backward pass visualization  
  - Weight and activation analysis  
- PCA for 2D projection and decision boundary visualization  

---

## 🛠️ Requirements

install manually:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow scikeras mlxtend
```

---

## 📈 Models Compared

| Model           | Training Accuracy | Testing Accuracy |
|----------------|-------------------|------------------|
| Neural Network | ✅ High           | ✅ High          |
| Decision Tree  | ✅ Moderate       | ✅ Good          |
| SVM            | ✅ Good           | ✅ Good          |

---

## 🔬 Techniques Used

- **Feature Engineering**: Scaling, Encoding, SelectKBest  
- **Model Training**: TensorFlow/Keras, DecisionTreeClassifier, SVC  
- **Visualization**: PCA, ROC/AUC curves, Decision Boundaries  
- **Evaluation Metrics**: Accuracy, Confusion Matrix, Classification Report  

---

## 📊 Visual Insights

- Boxplots before/after outlier removal  
- Joint plots between perceived productivity and job satisfaction  
- Correlation heatmaps  
- ROC curves for each model and class  

---

## 💾 Dataset

Custom dataset: `social_media_vs_productivity.csv`  
Attributes include:  
- Social media usage time  
- Perceived vs. actual productivity  
- Sleep hours, stress levels, screen time before sleep, etc.  

---

## 📌 Useful for:

- Behavioral data classification  
- Educational demos in ML pipelines  
- Deep learning model interpretability  

---

## 👤 Author

**Racha Zayni**  

---


