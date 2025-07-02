# 🌍 Carbon Emission Prediction – (Internship Project - June 2025 Batch)

## 📁 Project Description

This project is part of the AI/ML Internship (June Batch – 2025).  
The goal is to explore and prepare a climate dataset (CO₂ emissions & other greenhouse gases) for future ML tasks.

## ✅ Week 1 Milestone Completed: Stage 1 – Data Cleaning & Preparation - (18 June,2025)

- Used the *original Excel dataset* (Dataset.xlsx) without converting to CSV
- Loaded different sheets directly using pandas.read_excel()
- Performed basic data cleaning (removed nulls, unnecessary rows/columns)
- Prepared the data for ML by exploring structure and converting into usable format
- Saved the cleaned dataset into a new file: 'data_clean.csv'
- No merging or CSV transformation was applied

## 📁 Files Included

- data_preparation.ipynb → Jupyter Notebook with data loading & cleaning steps
- Dataset.xlsx → Original provided dataset
- data_cleaned.csv → Cleaned dataset exported after preprocessing
- README.md → This file

## 🛠 Tools Used

- Python
- Pandas
- Jupyter Notebook


## ✅ Week 2 Milestone Completed: Stage 2 – Data Exploration & Visualization - (24 june,2025)

- *Imported Cleaned Dataset:* Used data_clean.csv generated in Stage 1.
- *Visualized Global Trends:* Plotted relationships between CO₂ emission and country-specific indicators.
- *Explored Columns and Units:* Identified key columns and decoded abbreviations from the dataset.
- *Feature Engineering:* Selected relevant features and removed unnecessary ones.
- *Created Visualizations:*
  - Correlation matrix heatmap for feature dependencies
  - Scatterplots to examine distribution
  - Histograms for pattern discovery
  - Outlier detection using visual tools
- *Detected Dependencies & Trends:* Observed connections and trends in the data based on the visualizations.

## 📁 Files Included
- data_exploration.ipynb → Jupyter Notebook for EDA, feature analysis, and plots

## 🛠 Tools Used

- Pandas 
- Matplotlib 
- Seaborn 
- numpy
- Jupyter Notebook


## ✅ Week 3 Milestone Completed: Final Stage – Predictive Modeling - (1 July, 2025)

- *Imported Data and Setup:* Used cleaned dataset for ML modeling  
- *Explored Features Again:* Final feature list confirmed based on visualization insights  
- *Defined Hypothesis:* Established emission prediction as the modeling target  
- *Selected Target and Features:* Chose independent and dependent variables  
- *Split Dataset:* Divided data into training and testing sets  
- *Feature Selection:* Applied recursive feature elimination with cross-validation  
- *Model Selection & Tuning:*
  - Used Random Forest Regressor  
  - Performed hyperparameter tuning using cross-validation  
- *Model Training:* Trained with best hyperparameters  
- *Model Evaluation:* Tested the model on unseen data to evaluate performance  

### 📁 Files Included

- model_training.ipynb → Jupyter Notebook with feature selection, training, and evaluation  

## 🛠 Tools Used

- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  



