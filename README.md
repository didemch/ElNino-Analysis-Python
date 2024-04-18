# El Nino analysis
In this project, I explored the the underlying patterns and drivers of El Niño events through statistical analysis and machine learning techniques in Python.

__Data__: The El Niño dataset used in this project was obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/122/el+nino). All measurements come from nearly 70 moored buoys strategically deployed across the equatorial Pacific Ocean (shown in the figure below).

![Map](https://github.com/didemch/el-nino/blob/main/El%20Nino%20Buoys.png)

__Project Summary__:
To begin, I imported the El Niño dataset and performed data cleaning and preprocessing tasks to ensure the data's integrity and suitability for analysis. This involved handling missing values, normalization, and converting data types.

Once the data was prepared, I performed the exploratory data analysis (EDA) to uncover patterns, trends, and relationships within the El Niño dataset. I used various visualization methods such as time series plots, histograms, scatter plots, and heatmaps to visualize the data and gain insights into the behavior of El Niño events over time. I calculated summary statistics and correlation coefficients and explored the impact of El Niño events on various climatic variables, such as temperature, precipitation, and sea surface temperatures.

Then, I applied principal component analysis (PCA) to identify the key variables influencing sea surface temperature (SST) variability. By examining principal components and their loadings, I uncovered significant factors such as zonal winds, meridional winds, humidity, air temperature, latitude, and longitude, which play crucial roles in SST variations during El Niño occurrences.

After preprocessing the data and splitting it into training and test sets, I fit regression models to predict SST. Initially, I used linear regression models, followed by polynomial regression to capture potential non-linear relationships between predictors and SST. Additionally, I explored Lasso regression for feature selection and regularization, aiming to enhance model performance.

To assess the effectiveness of the models, I relied on evaluation metrics like mean squared error (MSE), mean absolute error (MAE), and coefficient of determination (R-squared). Through visualizations such as time series plots and residuals analysis, I gained insights into the accuracy of model predictions and potential areas for improvement.


Plot to visualize the predicted sea surface temperature (SST) values compared to the actual measured SST values over time for the test dataset using the Lasso regression model.
![Lasso Model performance](https://github.com/didemch/el-nino/blob/main/Lasso%20El%20Nino.png)
