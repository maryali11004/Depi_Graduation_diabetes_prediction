
# Diabetes Prediction Using Machine Learning

## 📌 Project Overview

This project aims to **predict the likelihood of diabetes in patients** using various machine learning models. It utilizes the **Pima Indians Diabetes Dataset** to build and evaluate supervised learning models for **binary classification** (diabetic vs. non-diabetic). The project includes data preprocessing, exploratory data analysis (EDA), model training, and performance evaluation using metrics like **Accuracy** and **Recall**.

---

## 📂 Dataset

**Source:** Pima Indians Diabetes Dataset (`diabetes.csv`)
**Records:** 768
**Features:**

* `Pregnancies`: Number of times pregnant
* `Glucose`: Plasma glucose concentration
* `BloodPressure`: Diastolic blood pressure (mm Hg)
* `SkinThickness`: Triceps skin fold thickness (mm)
* `Insulin`: 2-hour serum insulin (mu U/ml)
* `BMI`: Body mass index (weight in kg/(height in m)^2)
* `DiabetesPedigreeFunction`: Diabetes pedigree function
* `Age`: Age of the patient (years)
* `Outcome`: Target variable (0 = non-diabetic, 1 = diabetic)

**Class Distribution:**

* Non-diabetic (0): 65.10%
* Diabetic (1): 34.90%

---

## 🗂️ Project Structure

* `Advance Project Diabetes Prediction Using ML.ipynb`: Complete notebook including data loading, preprocessing, EDA, model training, and evaluation
* `diabetes.csv`: Dataset file
* `PE_diabetes.jpeg`: Output file (bar chart comparing model performance — Accuracy and Recall)

---

## 🔍 Methodology

### ✅ Data Preprocessing:

* Loaded dataset using **Pandas**
* Checked for missing values and data types
* Used descriptive statistics for feature understanding

### 📊 Exploratory Data Analysis (EDA):

* Analyzed class distribution
* Visualized features (e.g., Age histogram)

### 🧠 Model Training:

* Dataset split into **80% training / 20% testing**
* Features standardized using `StandardScaler`
* Trained multiple ML models:

  * Logistic Regression (LR)
  * Decision Tree (DT)
  * Support Vector Machine (SVM)
  * K-Nearest Neighbors (KNN)
  * XGBoost
  * Random Forest (RF)
  * Gradient Boosting Decision Tree (GBDT)

### 📈 Model Evaluation:

* Evaluated models using **Accuracy** and **Recall**
* Generated a bar chart comparing model performance
* Produced classification reports and confusion matrices

---

## ⚙️ Requirements

Install dependencies:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn xgboost
```

Or use a `requirements.txt`:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/diabetes-prediction.git
   cd diabetes-prediction
   ```

2. **Install Dependencies** (see above)

3. **Launch the Notebook:**

   ```bash
   jupyter notebook
   ```

4. **Open `Advance Project Diabetes Prediction Using ML.ipynb`**

5. **Ensure `diabetes.csv` is in the same directory**

6. **Run all cells** to perform data analysis, model training, and evaluation

   * Evaluation results saved as `PE_diabetes.jpeg`

---

## 📊 Results

Model performance is summarized below (example values; update with actual output):

| Model         | Accuracy | 
| ------------- | -------- |
| Logistic Reg. | \~80%    |
| Decision Tree | \~82%    |
| SVM           | \~79%    |
| KNN           | \~78%    |
| XGBoost       | \~83%    |
| Random Forest | \~84%    |
| GBDT          | \~85%    |

---

## 📜 License

This project is licensed under the **MIT License** – see the `LICENSE` file for details.

---

## 🙏 Acknowledgments

* Dataset from **UCI Machine Learning Repository**
* Libraries used: **Scikit-learn, Pandas, XGBoost**, and others from the open-source community

---

Let me know if you'd like this saved as a `README.md` file.
