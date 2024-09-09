# Predicting-Hazardous-NEOs-Nearest-Earth-Objects-
Training a Machine learning model that can accurately predict whether a NEO is hazardous or not.

## Table of Contents
- Installation
- Usage
- Contributing
- License
- Acknowledgements

## Installation
https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024/data
### Prerequisites
- Data Cleaning
- Data Preprocessing:
- EDA
- Model Training and Evaluation:

### Steps
1.Data Cleaning:
   Removing duplicates
   Remove irrelevent data
   Convert data type 
   Handling outliers 
   Fix errors
   
2. Data Preprocessing:

   Cleaned the dataset by handling missing values and removing irrelevant or duplicate entries.
   Converted categorical variables to numerical format using encoding techniques.
   Normalized features to ensure consistent scaling for the machine learning model.
   
3. Exploratory Data Analysis (EDA):

    Analyzed the dataset to understand the distribution of features and the relationship between variables.
    Visualized data using plots to identify patterns and correlations.

4. Feature Selection:

    Selected relevant features based on their importance and impact on the target variable (is_hazardous).

5. Handling Imbalanced Classes:

    The "is_hazardous" target column is likely imbalanced,
    with far fewer hazardous objects compared to non-hazardous ones.
    using the techniques "Class Weight Adjustment" , to balance the data cause the wide difference percentage
    found between the values of "is_hazardous" column and sure that is the best way to choose.

6. Model Building:

   Split the dataset into training and test sets to evaluate model performance.
   Trained a Random Forest classifier on the training set to predict hazardous NEOs.
   Tuned hyperparameters to optimize the model's performance.

7. Model Evaluation:

   Evaluated the model using metrics such as accuracy, confusion matrix, precision.
   Validated the model’s predictions on the test set to ensure robustness.

8. Results Interpretation:

   Analyzed the model’s predictions and performance metrics to assess its effectiveness.
   Generated visualizations to illustrate the model’s results and accuracy.      

### Results 

The Random Forest model achieved an accuracy of approximately 91% on the test dataset. The model's confusion matrix shows the following:

True Negatives (TN): 57,185
False Positives (FP): 1,808
False Negatives (FN): 4,642
True Positives (TP): 4,004
