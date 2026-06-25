# TASK 3 REPORT: CLINICAL HEART DISEASE PREDICTION

---

### 1. PROJECT NAME
* Diagnostic Risk Classification for Cardiac Conditions.


### 2. CORE OBJECTIVE
* To clean and preprocess clinical healthcare indicators by addressing missing features.
* To model binary risk parameters (0 for Healthy, 1 for Heart Disease Risk).
* To evaluate diagnostic model confidence using accuracy, confusion matrices, and ROC curves.


### 3. TECH STACK & LIBRARIES USED
* **Pandas** (For handling missing dataset symbols and labels)
* **Seaborn & Matplotlib** (For designing heatmaps and metric charts)
* **Scikit-Learn (`sklearn`)** (For split handling, model training, and performance metrics)


### 4. MACHINE LEARNING MODEL USED
* **Logistic Regression Classifier:** Implemented for reliable binary categorization and stable multi-feature medical weight optimizations.


### 5. KEY RESULTS & INSIGHTS
* **Model Performance:**
  * **Overall Accuracy:** 88.33% (Demonstrating reliable classification power on testing sets).
  * **ROC-AUC Score:** 0.95 (Reflecting an exceptional true-positive classification threshold against false alerts).
* **Clinical Indicators:** Feature analysis highlighted that chest pain indicators (`cp`), maximum heart rates (`thalach`), and visible fluoroscopy vessels (`ca`) act as the strongest structural risk signals.
