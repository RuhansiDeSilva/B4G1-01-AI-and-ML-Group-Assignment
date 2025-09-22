# B4G1-01-AI-and-ML-Group-Assignment

## Project Overview

This project aims to predict the placement status of graduate students based on global migration and higher education trends. By analyzing factors such as country of origin, destination, field of study, and academic performance, we seek to understand patterns influencing student placement outcomes.

## Dataset Details

- **Source:** [Global Student Migration & Higher Education Trends](https://www.kaggle.com/datasets/atharvasoundankar/global-student-migration-and-higher-education-trends)
- **Size:** 5,000 international students
- **Timeframe:** Data from 2019 to 2023
- **Features Include:**
  - Country of origin
  - Destination country
  - Field of study
  - Academic performance metrics
  - Placement status (target variable)

## Preprocessing Techniques

To prepare the dataset for machine learning models, the following preprocessing steps were applied:

### 1. Label Encoding - IT24100425 - Udayanga D A D N 
- **Purpose:** Convert categorical variables with ordinal relationships into numerical format.
- **Implementation:** Applied to fields such as 'Field of Study' to assign integer values representing different categories.

### 2. One-Hot Encoding - IT24100387 - De Zoysa T.N.D 
- **Purpose:** Transform categorical variables without ordinal relationships into a binary matrix.
- **Implementation:** Applied to 'Country of Origin' and 'Destination Country' to create binary columns for each category.

### 3. Outlier Removal - IT24100548 - Galagama S.T 
- **Purpose:** Eliminate data points that significantly differ from other observations to improve model accuracy.
- **Implementation:** Used statistical methods (e.g., IQR, Z-score) to identify and remove outliers in numerical features like 'Academic Performance'.

### 4. Principal Component Analysis (PCA) - IT24100514 - Ahamed M.M.S 
- **Purpose:** Reduce the dimensionality of the dataset while retaining most of the variance.
- **Implementation:** Applied PCA to the dataset to transform features into a smaller set of uncorrelated components.

### 5. Scaling / Normalization - IT24103804 - Rijiwan M. F.
- **Purpose:** Standardize the range of numerical features to improve model performance.
- **Implementation:** Applied Min-Max scaling to features such as 'Academic Performance' to normalize the data.

### 6. Feature Engineering - IT24100391 - De Silva T R S 
- **Purpose:** Create new features or select important ones to improve model accuracy.
- **Implementation:** Derived new metrics from existing features and applied feature selection to reduce irrelevant variables.

##  How to Run the Code

