# Phone-Price-Prediction-using-Regression
About Dataset
CONTEXT
The used and refurbished device market has grown considerably over the past decade as it provide cost-effective alternatives to both consumers and businesses that are looking to save money when purchasing one. Maximizing the longevity of devices through second-hand trade also reduces their environmental impact and helps in recycling and reducing waste. Here is a sample dataset of normalized used and new pricing data of refurbished / used devices.

Our data has 3454 values and 15 columns, Here we will use the "used_device_data.csv" database that has been made available for use, below you will see an analysis of the data, the processing of that data and the use of machine learning classification models to achieve our goal.

OBJECTIVE

The objective is to do Exploratory Data Analytics and apply Linear Regression to create a model which can help in pricing of such devices.

Variables

device_brand: Name of manufacturing brand

os: OS on which the device runs

screen_size: Size of the screen in cm

4g: Whether 4G is available or not

5g: Whether 5G is available or not

front_camera_mp: Resolution of the rear camera in megapixels

back_camera_mp: Resolution of the front camera in megapixels

internal_memory: Amount of internal memory (ROM) in GB

ram: Amount of RAM in GB

battery: Energy capacity of the device battery in mAh

weight: Weight of the device in grams

release_year: Year when the device model was released

days_used: Number of days the used/refurbished device has been used

normalized_new_price: Normalized price of a new device of the same model

normalized_used_price (TARGET): Normalized price of the used/refurbished device

Life cycle of this Machine learing project

-Understanding the problem statement

-Data Collection

-Exploratory Data Analysis

-Data Cleaning

-Filling the missing values

-Data Pre-Processing

-Outlier Detection using IQR method

-Model Training- Six Regression Algorithms(linear,ridge,lasso,svm,decision,randomforest)

Conclusion

Looking at our Machine Learning models we can see that we have some models that performed their function well and others not so much, the best model we had was the Random Forest model with the best score, when we look at our RMSE we see that the Random Forest model had the best score, so it depends on the management objective to choose the best model, in my view the model of Random Forest is the one that best satisfies looking at all metrics.
