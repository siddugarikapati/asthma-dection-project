Asthma Disease Prediction (Machine Learning Project)

This project predicts Asthma severity based on symptoms and demographic features using Machine Learning models. The dataset consists of binary symptom indicators such as dry cough, sore throat, breathing difficulty, age groups, gender, and severity labels.

🔍 Project Workflow
1. Data Preprocessing

Loaded dataset from ZIP file

Removed 311k+ duplicate rows

Final cleaned dataset: 5,760 unique records

Performed normalization on selected features

Checked feature distributions and class balance

2. Exploratory Data Analysis

Line plots and histograms for symptom patterns

Compared Asthma vs Non-Asthma feature distributions

No missing values found

3. Model Training

Models used:

Logistic Regression

Linear Regression (Baseline)

Train-test split: 70% training | 30% testing (stratified)

4. Results

Logistic Regression Accuracy: ~73.55%

Class	Precision	Recall
No Asthma (0)	0.79	0.88
Asthma (1)	0.46	0.31
🛠 Tech Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn

Google Colab

📁 How to Run
pip install numpy pandas matplotlib seaborn scikit-learn


Open notebook → Run all cells.

📌 Future Scope

Balance dataset (SMOTE / undersampling)

Try Random Forest, XGBoost, SVM

Build a deployment interface (Flask/Streamlit)
