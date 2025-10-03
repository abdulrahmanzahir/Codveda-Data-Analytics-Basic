# 📊 Task 2 — Exploratory Data Analysis (EDA)

## 📝 Overview
In this task, we explored the **Iris dataset** using various descriptive and visualization techniques.  
The goal was to gain insights into the structure of the data, identify correlations between features, and highlight patterns that can guide future modeling tasks.  

---

## 🎯 Objectives
- Generate descriptive statistics (mean, standard deviation, min, max) grouped by species.  
- Explore correlations among features.  
- Visualize distributions, pairwise relationships, and differences between species.  
- Identify patterns, overlaps, and outliers.  

---

## 🛠️ Steps Performed
1. **Setup & Imports**  
   - Installed required dependencies (`requirements.txt`).  
   - Imported libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`.  

2. **Descriptive Statistics**  
   - Computed mean, median, mode, std, min, and max values for each feature grouped by species.  
   - Observed distinct feature ranges between *setosa*, *versicolor*, and *virginica*.  

3. **Correlation Analysis**  
   - Generated a correlation heatmap.  
   - Found strong positive correlation between petal length & petal width (≈ 0.96).  
   - Sepal features showed weaker/negative correlations.  

4. **Feature Distributions**  
   - Plotted histograms for each numeric feature.  
   - Revealed petal features provide clearer separation across species compared to sepal features.  

5. **Pairwise Relationships**  
   - Used pairplots to compare features across species.  
   - Observed *setosa* is easily separable, while *versicolor* and *virginica* overlap.  

6. **Boxplots by Species**  
   - Compared feature distributions per species.  
   - Highlighted distinct ranges in petal features and presence of outliers in sepal width.  

---

## 🔑 Key Insights
- 🌸 Petal features (length & width) are the most discriminative for species classification.  
- 🌱 Sepal features have considerable overlap, making them less reliable predictors.  
- 📉 Outliers were observed in sepal width.
- 🎨 Clear evidence of species separation: *setosa* stands out, *versicolor* and *virginica* overlap partially.  

---

## 📂 File Structure
Task 2 - Exploratory Data Analysis (EDA)

│

├── Task 2 - Exploratory Data Analysis (EDA).ipynb # Jupyter Notebook with analysis & visualizations

├── README.md # Documentation for Task 2

├── Demo # Folder containing a short demo

   └── Task 2 (Demo).mp4 # A short Demo

└── Plots/ # Folder containing all saved plots

   ├── correlation_heatmap.png

   ├── feature_distributions.png

   ├── pairplot_species.png

   └── boxplots_by_species.png

---

## ✅ Conclusion
This exploratory analysis provided a solid understanding of the Iris dataset.  
The strong separation in **petal measurements** suggests these features will play a key role in future classification models.  
The results from this step will guide the **next phase — Task 3: Data Visualization**, where I'll focus on presenting insights more effectively.  