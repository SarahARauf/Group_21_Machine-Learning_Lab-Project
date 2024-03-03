
Principal Component Analysis (PCA)
-------------------------------------

Overview:

This lab enhancement focuses on Principal Component Analysis (PCA) for dimensionality reduction, data visualization and speeding ML model. Data visualization is done on the Wine Dataset(from sklearn) and Animal Image Dataset(from Kaggle). Speeding Machine Learning model is done on the Breast Cancer Dataset(from sklearn). The notebook covers various aspects, including data exploration, visualization and comparison.


Work Done in Lab Enhancement:


1. Explanation & Description of PCA concepts
        - History, Definition, Uses, Advantages & Disadvanatges.

2. Dimensionality Reduction 
        - simple code using wine dataset is done to show how to reduce dimension using PCA.

3. Data Exploration for Wine Dataset

4. Data Visualization for 1, 2 & 3 component (numerical data)
        - perform PCA to wine dataset for 1, 2 and 3 component
        - visualizing the PCA for 1, 2 and 3 component using a scatter plot 
        
5. Data Exploration for Animal Image Dataset

6. Data Visualization for 1, 2 & 3 component (image data)
        -  perform PCA to animal image dataset for 1, 2 and 3 component
        -  visualizing the PCA for 1, 2 and 3 component using a scatter plot 

7. PCA to speed up Machine Learning algorithm 
         - checking speed of Logistic Regression model before PCA and after PCA
         - comparing the time taken for the model to execute by visualizing it with a bar plot


Dataset Used:

1. Wine Dataset (from sklearn)
2. Animal Image Dataset - real world data but modified to fewer classes (from Kaggle)
3. Breast Cancer Dataset (from sklearn)

---------------------------------------------------------------------------------------------------------------------------

Steps done for Data Visualization (wine dataset)

1. Data Exploration
2. Adding label name
3. Normalization & Standardization
4. Performing PCA for 1, 2 and 3 component and identifying the explained variation per principal component.
5. Visualizing the PCA using scatter plot

Steps done for Data Visualization (animal image dataset)

1. Convert image to arrays, data splitting
2. Identifying minimum and maximum pixel 
3. Normalizing pixel values
4. Flattens image to 2D array
5. Performing PCA for 1, 2 and 3 component and identifying the explained variation per principal component
6. Visualizing the PCA using scatter plot

Steps done for Speeding ML model

1. Load dataset
2. Splitting and normalizing the features in dataset
3. Trains Logistic Regression model before PCA (identify accuracy and time taken)
4. Performing PCA with 3 component
5. Trains Logistic Regression model after PCA (identify accuracy and time taken)
6. Comparison of time taken using barplot


* explanation, description and docomentation are done in the notebook itself.