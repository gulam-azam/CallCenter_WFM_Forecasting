# Call Center Workforce Requirement Analysis with Time Series Model

**Author:** A H M Gulam Azam  


## Introduction

Customer service over the phone or online is integral to many industries, especially financial institutes and mobile operators. Call centers serve as the primary point of contact for customers seeking assistance, resolving issues, or obtaining information. In an increasingly competitive business landscape, delivering exceptional customer service is essential for building and maintaining customer loyalty. However, inadequate staffing often leads to customer dissatisfaction and affects the company's brand image. One common reason for understaffing is incorrect call forecasting.

This project aims to forecast incoming calls for the next month using a machine learning model and calculate the required workforce based on the forecasted calls.

## Model Selection

The ARIMA (AutoRegressive Integrated Moving Average) model was selected for this task. The ARIMA model is a flexible and adaptable framework that can handle various types of time series data. It considers autocorrelation in the time series data, which refers to the relationship between a data point and its previous values. The AR component captures this relationship by considering the weighted sum of past observations, helping to capture trends and patterns in the data.

## Data Collection and Processing

Data was collected from [Kaggle](https://www.kaggle.com/), an open-source data repository for data science. The data was processed using Python libraries to handle anomalies and missing values. The dataset was split into 80% for training and 20% for testing the model.

## Model Training and Evaluation

- **Training Data:** Plotted with different numbers of lags to observe trend changes and check for stationarity.
- **Differencing:** Tried different numbers of training data differences to observe the impact on the trend.
- **ARIMA Model Order:** The model was called with order number (1,1,0), which predicted incoming calls close to the test numbers.

The model was evaluated using RMSE (Root Mean Squared Error) and normRMSE to assess its performance.

## Workforce Calculation

Research and discussions with industry experts were conducted to calculate the required workforce to maintain a 90% service level in a call center. The workforce calculation was cross-checked with online resources and industry experts to ensure accuracy.

## Conclusion

This project demonstrates the use of the ARIMA model to forecast call center incoming calls and calculate the required workforce based on the forecast. The model's performance was evaluated and validated with industry standards to ensure reliable workforce planning.

## Acknowledgments

- Data sourced from [Kaggle](https://www.kaggle.com/).
- Python libraries used for data processing and model implementation.
- Industry experts for providing insights on workforce calculation.

## Contact

For any queries or further information, please contact [A H M Gulam Azam](https://gulam-azam.github.io/).
