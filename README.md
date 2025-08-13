#  Rainfall Prediction using Decision Tree

A machine learning project to predict whether it will rain tomorrow in Australia using historical weather data.

---

## 📂 Dataset
- **File:** `weatherAUS.csv`
- **Source:** Australian Bureau of Meteorology
- **Target Column:** `RainTomorrow` (Yes/No)
- **Features:** Temperature, Humidity, Wind Speed, Pressure, Rainfall, and more.

---

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, seaborn, matplotlib
- **Model:** Decision Tree Classifier

---

## 📊 Workflow
1. **Data Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Train-test split
2. **Model Training**
   - Decision Tree Classifier
3. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix visualization

---

## 📈 Model Performance
- **Accuracy:** 85%  
- **Precision (Rain):** 0.74  
- **Recall (Rain):** 0.46  
- **F1-score (Rain):** 0.57  

---

## 📉 Confusion Matrix
![Confusion Matrix](Confusion%20Matrix.png)

|                | Pred. No Rain | Pred. Rain |
|----------------|---------------|------------|
| **Actual No Rain** | 8401 | 398 |
| **Actual Rain**    | 1349 | 1136 |










