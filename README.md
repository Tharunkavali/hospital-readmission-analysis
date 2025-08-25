# hospital-readmission-analysis
Analysis of hospital readmissions using the Diabetes 130-US Hospitals dataset. Includes data cleaning, exploratory data analysis, visualization, and predictive modeling with Logistic Regression and Random Forest. Highlights key factors affecting patient readmission.


# Hospital Readmission Analysis

Analysis of hospital readmissions using the **Diabetes 130-US Hospitals dataset**.  
This project includes **data cleaning, exploratory data analysis, visualization**, and **predictive modeling** with Logistic Regression and Random Forest.  
It highlights key factors affecting patient readmission and provides actionable insights for healthcare interventions.

---

## 📂 Project Structure
hospital_readmission_project/
│── data/ # Dataset (diabetic_data.csv)
│── notebooks/ # Jupyter Notebook with analysis
│ └── 01_data_exploration.ipynb
│── visuals/ # Optional: screenshots of plots
│── README.md # Project overview


## 🧰 Tools & Libraries Used

- Python 3.13  
- Jupyter Notebook  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn (Logistic Regression, Random Forest)

---

## 📝 Project Steps

### 1. Data Loading & Cleaning
- Loaded dataset using `pandas`
- Replaced missing values (`?`) with `NaN`
- Filled missing `race` values with mode
- Dropped irrelevant columns: `encounter_id`, `patient_nbr`

### 2. Exploratory Data Analysis (EDA)
- Visualized distribution of `readmitted` patients  
- Checked readmission patterns by `age`, `gender`, `admission_type_id`, `time_in_hospital`, `num_medications`  
- Observed higher readmission rates among older patients and emergency admissions

### 3. Feature Encoding & Scaling
- Encoded categorical columns using `LabelEncoder`  
- Scaled numeric features with `StandardScaler`  
- Split dataset into **training (80%)** and **testing (20%)** sets

### 4. Predictive Modeling
- **Logistic Regression**: Accuracy ~63%  
- **Random Forest**: Accuracy ~72%  
- Evaluated models using **classification reports** and **confusion matrices**  

---

## 📊 Key Insights

- Older patients and those with more inpatient visits are at higher risk of readmission  
- Longer hospital stays and higher number of medications increase readmission likelihood  
- Emergency admissions contribute significantly to readmission probability  
- Hospitals can use these insights for **targeted patient monitoring** and interventions

---

## 🖼 Visualizations

- Readmission distribution  
- Readmission by gender and age group  
- Top 10 important features from Random Forest model  

*(All visualizations are available in the notebook and optional visuals folder)*

---


## 🔗 How to View

- Open the `01_data_exploration.ipynb` notebook in Jupyter to see the full analysis, code, and visualizations.  
- Optional: Download the PDF version (if included) to view without running code.  

---

## 📄 References

- [Diabetes 130-US Hospitals Dataset - Kaggle](https://www.kaggle.com/datasets/uciml/diabetes-130-us-hospitals-for-clinical-notes)  
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/)  
- [Pandas Documentation](https://pandas.pydata.org/)

---

## 🏆 Author

**Tharun Kavali**  
- GitHub: [github.com/Tharunkavali](https://github.com/Tharunkavali)  
- Email: tkavalims@gmail.com

