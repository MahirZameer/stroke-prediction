# stroke-prediction
Stroke Prediction using Classification
# 🧠 Stroke Prediction

This project uses classification algorithms to predict the likelihood of a stroke based on patient health data. It includes preprocessing, EDA, SMOTE for balancing, and multiple machine learning models.

## 📁 Project Structure

├── data/ # Raw dataset (CSV file)
├── notebooks/ # Jupyter notebooks for EDA and modeling
├── src/ # Python scripts (preprocessing, modeling, utils)
├── visualizations/ # Saved plots/images from EDA
├── presentation/ # Final slides/report
└── README.md # You're reading it

## 📊 Dataset
- Source: Kaggle
- Contains patient info like age, glucose level, BMI, etc.
- Target variable: `stroke`

## 🧪 Methods Used
- Exploratory Data Analysis (EDA)
- One-hot encoding
- SMOTE for class imbalance
- Random Forest Classifier
- Accuracy, precision, recall, f1-score

## 📈 Results
- Accuracy: 91%
- Precision on stroke class (1): **16%** (needs balancing improvement)

## ⚙️ How to Run
1. Clone the repo
2. Install dependencies (pandas, matplotlib, seaborn, scikit-learn, imbalanced-learn)
3. Open `notebooks/stroke_eda_model.ipynb` in Jupyter
