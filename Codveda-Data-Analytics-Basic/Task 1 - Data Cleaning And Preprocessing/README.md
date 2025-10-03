# 🧹 Task 1 — Data Cleaning and Preprocessing

## 📌 Objectives
- Load the dataset using **pandas**.  
- Identify and handle missing values (imputation or removal).  
- Remove duplicate rows and standardize inconsistent data formats.  
- Ensure categorical variables are consistent and ready for analysis.  
- Save the cleaned dataset for use in subsequent tasks.  

---

## 📊 Dataset
- **Name:** Iris Dataset  
- **Size:** 150 rows × 5 columns  
- **Features:** sepal_length, sepal_width, petal_length, petal_width, species  

---

## 🛠️ Steps Performed
1. **Installed dependencies** listed in `requirements.txt` (pandas, numpy, matplotlib, seaborn).  
2. **Imported libraries** into Jupyter Notebook.  
3. **Loaded raw dataset** from `../Raw-Dataset/1) iris.csv`.  
4. **Checked for missing values** → none found.  
5. **Identified duplicate rows** → 3 rows detected and removed.  
6. **Verified categorical consistency** for `species` → only 3 valid unique classes: setosa, versicolor, virginica.  
7. **Exported cleaned dataset** to a dedicated folder for reuse in Task 2 and Task 3.  

---

## 📂 Output
The cleaned dataset is saved at: ../Task1-Data-Cleaning-And-Preprocessing/Cleaned-Dataset/iris_cleaned.csv

---

## ✅ Result
- Final dataset: **147 rows × 5 columns**  
- Clean, consistent, and ready for **Task 2 — Exploratory Data Analysis (EDA)**.  

---

## 📂 File Structure
Task 1 - Data Cleaning And Preprocessing

│

├── Task 1 - Data Cleaning And Preprocessing.ipynb # Jupyter Notebook with preprocessing steps

├── README.md # Documentation for Task 1

├── Task 1 - Demo.mp4 # A short Demo

└── Cleaned-Dataset

└── iris_cleaned.csv # Cleaned & Processed Dataset