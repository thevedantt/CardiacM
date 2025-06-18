# CardiacM : 🩺 Heart Health Checker

A simple Python-based tool that uses Logistic Regression and Gemini AI to predict a person's risk of heart disease based on 6 basic health indicators.

---

## 🚀 Features

- Predicts heart disease risk using Logistic Regression.
- Asks 6 simple health-related questions.
- Uses Gemini AI to provide a natural language explanation of results.
- Confidence score is shown to indicate prediction certainty.

---

## 📊 Input Features

The model uses the following features:
- **Age**
- **Chest pain type (cp)**
- **Maximum heart rate achieved (thalach)**
- **Exercise-induced ST depression (oldpeak)**
- **Exercise-induced angina (exang)**
- **Number of major blood vessels (ca)**

---

## 🧠 How It Works

1. You answer six health-related questions via terminal.
2. The model predicts your risk level using a Logistic Regression model.
3. Confidence of the prediction is displayed.
4. Gemini AI provides a human-readable explanation of the result.

---

## ⚠️ Known Limitations

- **Not a full-featured model**: It only uses 6 features instead of the full dataset.
- **No hyperparameter tuning** or cross-validation applied.
- **Hardcoded API and model**: Gemini is used but not customized deeply.
- **Not deployed**: Must be run locally with manual input.

---

## 🔧 Future Improvements

- Use all features from the heart dataset.
- Implement better models (Random Forest, XGBoost, etc.).



- Add UI for better accessibility (Streamlit or Flask).
- Improve AI explanation prompt and validation.
- Enable file upload for batch predictions.

---

## 📁 Dataset Used

- File: `heart.csv`
- Path: `/content/heart.csv`
- Target column: `target` (1 = at risk, 0 = not at risk)

---

## 💡 Final Note

This project is for educational purposes only and should not be used for medical diagnosis. Always consult a healthcare professional for medical concerns.
