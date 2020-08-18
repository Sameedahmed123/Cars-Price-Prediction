# Background Information

- So called Second hand's car have a huge market base. Many consider to buy a Used Car intsead of buying of new one, as it's is feasible and a better investment.

- The main reason for this huge market is that when you buy a New Car and sale it just another day without any default on it, the price of car reduces by 30%.

- There are also many frauds in the market who not only sale wrong but also they could mislead to wrong price.

- So, here I used the dataset to Predict the price of any used car.

## Used Car Price Estimator : Project Overview
- Predicted Price of Used Car to help People predict price of their cars.
- From Data Cleaning to Data Manipulation
- Engineered features to normalize and standardized variable to help understand data.
- Optimized Linear, Decision Tree and Random forrest Regressors to reach the best model.

### Code and Resources Used

**Python Version** : 3.7

**Packages** : Pandas, Matplotlib, Seaborn, Sklearn, numpy, scipy

### Data Cleaning

- Find out how many missing values are in each coloumn
- Replaced missing values in numerical variable with mean value
- Replaced missing values in categorical variabel with mode value
- Corrected data types
- Standardized city and highway variables
- Normalized length, height and width

### Model Building

First, I transformed all categorical variables into dummy variables, I also split the test and train data.

I tried three different models, evaluated them using mean absolute error, I chose MAE because it is relatively easy to interpret.

I tried these models:
- **Linear Regression** - Baseline for the model
- **Decision Tree** - Better classification and regression model than linear
- **Random Forest** - With the sparsity of the data, I thought this would be good model

### Model Performance

- **Linear Regression**: MAE = 2346
- **Decision Tree**: MAE = 1684
- **Random Forest** : MAE = 1282
