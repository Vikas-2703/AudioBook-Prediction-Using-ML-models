# 📘 Prediction of Audiobook Ratings Using Machine Learning

This project predicts **audiobook ratings (Stars out of 5)** using structured metadata such as price, duration, release date, category, language, author, etc.

It is developed in **two phases**:

### ✔ Phase 1 — Data Cleaning & Exploratory Data Analysis (EDA)
### ✔ Phase 2 — Machine Learning Model Development & Evaluation

The project demonstrates a full data science workflow from raw data → cleaning → feature engineering → EDA → model training → evaluation → comparison.

---

# 📁 Project Structure

```text
AudioBook-Prediction-Using-ML-models/
│
├── data/
│   ├── Phase1_Group90.csv          # raw/cleaned dataset (optional)
│   └── Phase2_Group90.csv          # processed dataset (optional)
│
├── notebooks/
│   ├── Phase1_Group90.ipynb        # Phase 1: Cleaning & EDA
│   └── Predictive Modelling.ipynb  # Phase 2: ML models
│
├── requirements.txt                # dependencies
└── README.md                       # project documentation
```

---

# 🔹 Phase 1 — Data Cleaning & Exploratory Data Analysis

**Notebook:** `notebooks/Phase1_Group90.ipynb`

Key tasks performed:

### 1. Initial Data Inspection
- Checked for missing values  
- Reviewed datatypes, duplicates, inconsistent fields  

### 2. Text & Metadata Cleaning
- Standardised column names  
- Cleaned author names  
- Fixed narrator formatting  
- Standardised language formats  

### 3. Numeric Field Cleaning
- Converted prices into numeric floats  
- Converted audiobook time into numeric minutes  
- Extracted star ratings into numeric values  
- Extracted number of ratings  

### 4. Date Formatting
- Converted release dates into datetime  

### 5. EDA (Exploratory Data Analysis)
Visualised:
- Rating distribution  
- Price distribution  
- Time distribution  
- Correlation heatmaps  
- Bubble & 3D scatter plots  

Output: a **fully cleaned & feature-engineered dataset** ready for ML modelling.

---

# 🔹 Phase 2 — Machine Learning Modelling

**Notebook:** `notebooks/Predictive Modelling.ipynb`

### 1. Dataset Sampling

### 2. Categorical Encoding

### 3. Train-Test Split

### 4. Feature Selection (RFE)

### 5. ML Models Built
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- KNN Regressor  
- Gradient Boosting Regressor  
- Neural Network (Keras)  

### 6. Evaluation
Models compared using **Mean Squared Error (MSE)**.

---

# 🧠 Tech Stack

### Languages
- Python  

### Libraries
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  
- keras, tensorflow  
- jupyter  

---

# ▶️ How to Run This Project

### 1. Clone the repo
```bash
git clone https://github.com/Vikas-2703/AudioBook-Predictions-Using-ML-models.git
cd AudioBook-Predictions-Using-ML-models
```

### 2. Install requirements
```bash
pip install -r requirements.txt
```

### 3. Add dataset files in `/data`

### 4. Run notebooks
```bash
jupyter notebook notebooks/Phase1_Group90.ipynb
jupyter notebook notebooks/Predictive Modelling.ipynb
```

---

# 📌 Future Enhancements
- Add SHAP explainability  
- Try XGBoost/LightGBM  
- Deploy as API  
- Streamlit dashboard  

---

# 📬 Contact
**LinkedIn:** https://www.linkedin.com/in/vikas-66161921b/  
**GitHub:** https://github.com/Vikas-2703
