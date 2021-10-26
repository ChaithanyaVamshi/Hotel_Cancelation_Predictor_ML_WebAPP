# Hotel Cancelation Predictor ML WebAPP

## Predicting Hotel Booking Cancellations Using Machine Learning With Python

- Have you ever wondered what if there was a way you could predict which guests who are likely to cancel the reservation at Hotel? That would be great right? Check out this ML model which gives best prediction for the guests who are likely to cancel the reservation.

## Machine Learning Project Life Cyle
1. Understanding the Business Problem
2. Data Collection and Understanding
3. Data Exploration
4. Data Preparation
5. Modeling
6. Model Deployment

## 1. Understanding Business Problem
### Hotel Booking Cancellations, A Growing Problem…
- Hotel Booking Cancellations have a substantial Impact on demand Management Decisions and Revenue in the Hospitality Industry. When Analyzing the past 5 years data, the Global Average Cancellation rate on Hotel Bookings has reached 40% and this trend produces a very negative impact on Hotel Revenue.

- The Goal of this project is to Predict the Guests who are likely to Cancel the Hotel Booking using Machine Learning with Python. Therefore, predicting reservations which might get canceled and preventing these cancellations will create a surplus revenue, better forecasts and reduce uncertainty in business management decisions.

## 2. Data Collection and Understanding

- I've collected the dataset from the kaggle. Dataset is available at https://www.kaggle.com/jessemostipak/hotel-booking-demand

This dataset contains booking information for a City hotel and a Resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces etc.

## 3. Data Exploration

- In this step, we will apply Exploratory Data Analysis (EDA) to extract insights from the data set to know which features have contributed more in predicting Cancellations by performing Data Analysis using Pandas and Data visualization using Matplotlib & Seaborn. It is always a good practice to understand the data first and try to gather as many insights from it.

Below are tasks to be performed:

1. Importing Libraries
2. Storing the data into MongoDB Database
3. Loading (Fetching) data from MongoDB Database
4. Exploratory Data Analysis (EDA) on all Features
5. Data Visualisation on all Important Features

# Description:
- Dataset is collected from https://www.kaggle.com/jessemostipak/hotel-booking-demand
- Data Cleaning, Data Visualization, EDA and model is built to predict which guests at the Hotel are likely to cancel the reservation.
- Please check out my medium blog which got featured in Analytics Vidhya which helps in understanding Exploratory Data Analysis (EDA) performed on the data set : https://medium.com/analytics-vidhya/exploratory-data-analysis-eda-for-predicting-hotel-booking-cancellations-using-machine-learning-3990be4af2ff
- Applied Feature Engineering and Feature Encoding techniques like One Hot encoding, Label Encoding, Custom Mapping etc
- Applied various Classification Algorithms on the data set like Logistic Regression, Decision Trees, Random Forest and Boosting Algorithm like XGBOOST.
- The model is successfully built and has achieved  highest accuracy of 89% with Random Forest Algorithm after applying Cross Validaton Techniques.
- Applied Hyper Parameter tuning using GridSearchCV to get the best score and best parameters for building the model.
- Built a web app using Python and Streamlit library.
- Deployed the Model on Heroku. Please do check out the web app : https://hotel-cancel-predictor.herokuapp.com/
