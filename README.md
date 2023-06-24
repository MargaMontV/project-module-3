# project-module-3 

Ironhack Madrid - Data Analytics Part Time - June 2023 - Project Module 3

# :raising_hand: **Diamonds predictions - Machine learning**
![](diamond.gif)

The Diamonds Predictions Competition aims to predict the prices of diamonds using machine learning techniques. We are provided with a dataset containing various attributes of diamonds, such as carat, cut, color, clarity, weight, lenght, depth, city, etc. The objective is to develop a predictive model that accurately estimates the price of a diamond based on these attributes.

### :information_source: **Datasets**
The competition dataset consists of two CSV files: train and test. The train file contains the training data, including the target variable (price), while the test file contains the test data, without the target variable. We are expected to train their models on the training data and make predictions for the test data.

### :notebook: **Evaluation**
Submissions are evaluated based on the root mean squared error (RMSE) metric. Lower RMSE values indicate better predictions. The evaluation metric is calculated based on the predictions submitted for the test data.

### :fire: **Output**
* CSV file with the predictions that you upload to Kaggle, where they calculate the RMSE comparing with the real prices.

### :thread: **Model**
The data is cleaned and organized according to wich columns are relevant and need some proccessing. There are categorical columns that are converted to numeric values according to their importance. We also clean outliers and empty values.
There are also some columns created with feature engeneering that enhance other values and work better with the predictive models.
The model used to perform the training and predictions is CatBoost, which has a better performance compared to others.

### :computer: **Technology stack**
* Python 
* sqlite3
* Pandas
* Numpy
* Sklearn
* CatBoost
* Gridsearch
* Statistics
* Plotly
* Matplotlib
* Seaborn
* Math
* Jupyter notebook
* Visual Studio Code

### :file_folder: **Folder structure**
```
└── project
    ├── clean_notebooks
    │   ├── EDA_diamonds.ipynb
    │   └── predictions_gridsearch_CatBoost_515.ipynb  
    │   └── predictions_gridsearch_CatBoost_not_scaled_515.ipynb 
    │   └── preprocessing_diamonds.ipynb
    ├── predictions
    │   └── predictions_gridsearch_CatBoost_515.csv 
    │   └── predictions_gridsearch_CatBoost_not_scaled_515.csv  
    ├── README
```
### :love_letter: **Contact info**
[LinkedIn](https://www.linkedin.com/in/margarita-montenegro-data-analyst/)