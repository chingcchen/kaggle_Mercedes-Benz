# kaggle_Mercedes-Benz
My second data science competition on Kaggle, "Mercedes-Benz Greener Manufacturing". This notebook demonstrates data exploration, data processing, feature engineering, and supervised machine learning techniques in python.
The goal of this repository is to record where I started as a beginner in the the field of data science and Kaggle's competitions.

#### File Descriptions 
* Variables with letters are categorical. Variables with 0/1 are binary values.
* Datasets: *train.csv* &  *test.csv*
* Notebook: *Benz.ipynb*
* Result: *submission.csv*


## Kaggle Competition Description | Mercedes-Benz Greener Manufacturing
#### Can you cut the time a Mercedes-Benz spends on the test bench?

> To ensure the safety and reliability of each and every unique car configuration before they hit the road, Daimler’s engineers have developed a robust testing system. But, optimizing the speed of their testing system for so many possible feature combinations is complex and time-consuming without a powerful algorithmic approach. As one of the world’s biggest manufacturers of premium cars, safety and efficiency are paramount on Daimler’s production lines.

> In this competition, Daimler is challenging Kagglers to tackle the curse of dimensionality and reduce the time that cars spend on the test bench. Competitors will work with a dataset representing different permutations of Mercedes-Benz car features to predict the time it takes to pass testing. Winning algorithms will contribute to speedier testing, resulting in lower carbon dioxide emissions without reducing Daimler’s standards.

From the competition [homepage](https://www.kaggle.com/c/mercedes-benz-greener-manufacturing).

**In this notebook you can see how I predict the time a Mercedes-Benz car takes to pass testing:**

### Data Exploration 
* Importing Data with Pandas
* Checking if there is any missing value 

### Data Processing 
* Convert categorical variable into dummy variables
* PCA (n_components=12)

### Feature Engineering 
Supervised Machine learning Techniques:
* Random Forest Regressor 
* Gradient Boosting Regressor
Tuning Parameters:
* GridSearchCV

### Model Evaluation 
* Cross Validation


## Result 
Based on this analysis, I got a score of 0.513 and ranked top 88% (06/06/2017). 
See my [profile](https://www.kaggle.com/chingchen) on Kaggle. 

