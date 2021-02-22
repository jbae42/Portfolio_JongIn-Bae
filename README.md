# Portfolio_JongIn-Bae

## [Project 2. [Regression & Classification] Financial Performance Prediction](https://github.com/jbae42/Financial_Performance_Prediction)
### Project Overview
* Objective: The objective of this project is to select the best model out of 5 classification and regression models to predict a 
customer's capability to pay off the loan based on features such as income, education level, credit history, etc.
* Data Preprocessing: 3 approaches were used to pre-process the data set for modeling steps. 3 approaches that were used are [1. significant feature selection](https://github.com/jbae42/Financial_Performance_Prediction/blob/main/Approach%201.%20Significant%20Feature%20Selection/Approach%231a%20-%20Dimensionality%20Reduction.ipynb), [2. data scaling](https://github.com/jbae42/Financial_Performance_Prediction/blob/main/Approach%202.%20Data%20Scaling/Approach%232%20-%20Scaling%20Dataset.ipynb), and [3. removing outliers and normalizing data](https://github.com/jbae42/Financial_Performance_Prediction/blob/main/Approach%203.%20Outlier%20Removal%20and%20Data%20Normalization/Approach%233%20-%20Remove%20Outliers%20and%20Normalize%20Data.ipynb).
* Model Performance: Linear Regression model and XGBoost performed with accuracy scores of 90.43%.
Other models (Gradient_Boost, ADA Boost, and Random Forest Classifier) performed with higher than accuracy scores of 87%.\
![](/image/[2]PerformanceResults.png)
![](/image/[2]scatterplot2.png)
![](/image/[2]heatmap.png)
![](/image/[2]pairplot.png)

## [Project 1. [Classfication] Glassdoor_Job_Salary_Estimate](https://github.com/jbae42/Glassdoor_Job_Salary_Estimate)
### Project Overview
* Objective: The objective of this project is to build a classification model and a regression model that estimate the best fitting job type among data scientist, data analyst, and software engineering and the respective salary based on the set of skill set (input).
* Potential Use: The product of this project (job type classification model and salary regression model) can be used to assist any candidate seeking an entry level position in data analytics or software engineering field and provide the best fitting job type and estimated salary based on the candidate's skill sets.
* Model Performance: 93% accuracy achieved with classification model / salary estimate regression model (MAE ~ $18.06K)
* Comments on Model Performance: Low performance on salary estimate regression model may be due to the salary data from glassdoor estimates. Glassdoor estimates may be based on the job location (state), rather than the listed skill set.  

![](/image/1.png)

![](/image/Box%20Plots%20on%20Entry%20Level%20Salary%20by%20Job%20Type.png)

![](/image/wordcloud_datascientist.png)
