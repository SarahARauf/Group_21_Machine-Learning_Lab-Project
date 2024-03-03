Project (40%)
---------------

Overview:

This folder contains notebooks and datasets related to the final project, which involves Exploratory Data Analysis (EDA), Data Preprocessing, Principal Component Analysis (PCA) for Data Visualization, and using PCA to speed up the Machine Learning (ML) model. The primary dataset used is KL_weather.csv.


Notebooks:

5_Project_EDA.ipynb
      - This notebook focuses on Exploratory Data Analysis (EDA).
      - It is recommended to run this notebook first to gain insights into the dataset.

5_Project_DataPreprocessing.ipynb
      - This notebook involves the preprocessing steps for the original dataset KL_weather.csv
      - The result is a cleaned dataset named cleaned_data (No feature selection).csv
      - Feature selection is performed using ANOVA, generating cleaned_data(Top_20features_Anova).csv

5_Project_PCA for Data Visualization.ipynb
      - This notebook utilizes cleaned_data(Top_20features_Anova).csv.
      - It demonstrates the use of Principal Component Analysis (PCA) for data visualization.

5_Project_PCA to Speed Up ML Model.ipynb
      - This notebook employs cleaned_data(Top_20features_Anova).csv.
      - It showcases how PCA can be utilized to speed up the ML model.


Dataset Used:

1. cleaned_data (No feature selection).csv
      - Resultant dataset after basic preprocessing steps.

2. cleaned_data(Top_20features_Anova).csv
      - Dataset after feature selection using ANOVA in 5_Project_DataPreprocessing.ipynb.

3. KL_weather.csv
      - Original dataset that undergoes preprocessing in 5_Project_DataPreprocessing.ipynb.
      

Instructions:

1. Run the notebooks in the following order:
   - 5_Project_EDA.ipynb
   - 5_Project_DataPreprocessing.ipynb

2. Once preprocessing is complete, you can choose between:
   - Exploring data visualization using PCA in 5_Project_PCA for Data Visualization.ipynb
   - Evaluating PCA's impact on speeding up ML models in 5_Project_PCA to Speed Up ML Model.ipynb

** Ensure to follow the provided sequence for a seamless execution of the project notebooks.
** Explanation, description and docomentation are done in the notebook itself.


