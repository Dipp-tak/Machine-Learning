
# 💓 Heart Disease Prediction Using Logistic Regression

This project is a simple yet powerful machine learning model that predicts the presence of heart disease based on clinical and diagnostic data. The model is trained using **Logistic Regression** on a heart disease dataset containing key medical features like age, chest pain type, blood pressure, cholesterol levels, and more.

## 📁 File Structure
|
|-Heart Disease Predicition.ipynb
|
|-heart_disease_data


## 📁 Dataset Features

The dataset contains the following features:

- `age`: Age of the patient
- `sex`: Sex (1 = male, 0 = female)
- `cp`: Chest pain type (0–3)
- `trestbps`: Resting blood pressure (mm Hg)
- `chol`: Serum cholesterol (mg/dl)
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- `restecg`: Resting electrocardiographic results (0–2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes; 0 = no)
- `oldpeak`: ST depression induced by exercise
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy (0–3)
- `thal`: Type of thalassemia (0–3)
- `target`: Heart disease (1 = disease, 0 = no disease)

## 🔍 Exploratory Data Analysis (EDA)

To understand the data better, several visualizations were created, including:

- Distribution of age, cholesterol, and max heart rate
- Relationship between chest pain type and heart disease
- Correlation heatmap of features
- Boxplots of key features against the target variable

## 🧠 Model: Logistic Regression

The Logistic Regression model was chosen for its interpretability and effectiveness in binary classification. The pipeline includes:

- Data preprocessing and scaling using `StandardScaler`
- Train-test split with stratified sampling
- Evaluation using accuracy, precision, recall, and F1-score

## 📈 Results

- Achieved high accuracy in predicting heart disease on the test set
- Hyperparameter tuning improved model performance
- Generated classification report and confusion matrix for evaluation

## 🛠 Tech Stack

- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn

## 🚀 Future Improvements

- Add other ML models like Random Forest, XGBoost for comparison
- Build a web app using Streamlit or Flask for real-time predictions
- Integrate SHAP or LIME for model interpretability

## 📌 How to Run

1. Clone this repo
2. Install dependencies using `pip install -r requirements.txt`
3. Run `logistic_regression_heart_disease.py`
