# World War Two Weather Prediction Using Linear Regression
This project analyzes and predicts daily mean temperatures using meteorological station data from the World War II era. By leveraging historical records, I developed a Linear Regression model to estimate the 'MeanTemp' value.

## Performance Metrics
Following feature engineering and optimization, the model achieved the following results:
* **R2 Score:** 0.938
* **Mean Absolute Error (MAE):** 1.53
* **Mean Squared Error (MSE):** 4.26

## Feature Engineering
The high model performance was achieved through careful data preprocessing, including the removal of highly correlated features to prevent multicollinearity, handling null values, imputing inconsistent data points, and eliminating duplicate records.

## Visualizations
(results.png) 
* The tight distribution along the identity line indicates low variance in prediction errors.
(correlation_heatmap.png)
* Shows the strong relationship between MaxTemp and MeanTemp.
(weather_boxplot.png)
* Visualizes the temperature distribution and potential outliers.

## Technologies Used
* **Pandas** (Data manipulation)
* **Scikit-Learn** (Linear Regression & Evaluation)
* **Matplotlib/Seaborn** (Visualization)


## How to Run
* 1. Clone the repository
* 2. Install dependencies
* 3. Run the analysis

