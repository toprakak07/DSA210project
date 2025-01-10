Step Count Analysis Project Report

1. Introduction
   
In this project, we analyzed personal step count data collected between 2022 and 2024. The primary goal of this analysis was to explore daily, weekly, and seasonal activity patterns, uncover potential trends, and evaluate whether machine learning models can be used to predict future step counts.

Understanding personal activity patterns can provide valuable insights into overall health and fitness, which can help in setting achievable goals for improving physical well-being.

2. Data Source
   
The data was collected using a fitness tracker or mobile application over the period of 2022 to 2024. It includes the following fields:

->startDate: Start time of the activity (datetime format)

->endDate: End time of the activity (datetime format)

->value: Total number of steps taken during the activity period

->The dataset was cleaned and structured into a Pandas DataFrame for analysis.

3. Data Analysis
   
3.1 Exploratory Data Analysis (EDA)

Missing Data:

->We checked for missing values and handled them by filling missing entries with the mean value of the respective column.

->No significant amount of missing data was found.

General Statistics:

->Key statistics such as mean, median, and standard deviation were computed to understand the distribution of step counts.

Outlier Analysis:

->Using boxplots, we identified outliers in the step count data. While some extreme values were present, they were retained as they represented valid activity data.

3.2 Weekly and Seasonal Patterns

Weekly Patterns

We analyzed the average step count for each day of the week. The results are summarized below:

Most Active Days:

->The most active days were Saturday and Sunday, indicating increased activity during weekends.

Least Active Days:

->The least active days were Monday and Tuesday, likely due to the start of the workweek.

Seasonal Trends

We divided the data into four seasons (Winter, Spring, Summer, and Fall) and calculated the average step count for each season:

Most Active Season:

->The highest activity was observed during Summer.

Least Active Season:

->The lowest activity was observed during Winter.

->An ANOVA test was performed to check whether there were significant differences in step counts between seasons. The results showed a statistically significant difference, indicating that step counts vary significantly across different seasons.

3.3 Correlation Analysis

Seasonal Correlation

We calculated the correlation between step counts across different years on a seasonal basis. A heatmap was used to visualize the correlation.

Key insight:

->There was a moderate positive correlation between step counts in different years, suggesting similar seasonal activity patterns over time.

4. Machine Learning Models

->To predict future step counts, we used machine learning model: Linear Regression. The model was evaluated using Mean Absolute Error (MAE) and R² score.

4.1 Linear Regression

Mean Absolute Error (MAE): 43,332.41

R² Score: -0.536

The negative R² score indicates that the linear regression model performed poorly, meaning it could not capture the variability in step counts effectively.

5. Visualizations
   
The following visualizations were created to support our analysis:

->Weekly Step Count Bar Chart

->Displays the average step count for each day of the week.

->Seasonal Step Count Bar Chart

->Shows the average step count for each season.

->Monthly Step Count Line Plot

->Visualizes the total step count for each month across different years.

->Step Count Distribution Histogram

->Displays the overall distribution of step counts.

->Seasonal Correlation Heatmap

->Shows the correlation of step counts between different years on a seasonal basis.

3-Month Moving Average Line Plot

->Illustrates the smoothed trend of step counts using a 3-month moving average.

6. Key Insights
   
Weekend Activity:

->Step counts were significantly higher on weekends compared to weekdays, indicating more leisure time for physical activities during weekends.

Seasonal Variations:

->Activity levels were highest in summer and lowest in winter, likely due to weather conditions and outdoor activity preferences.

7. Conclusion
   
This project provided valuable insights into personal activity patterns by analyzing step count data over several years. While simple models like linear regression struggled to make accurate predictions, the analysis highlighted key trends in weekly and seasonal activity. With further data collection and model refinement, more accurate predictions and actionable insights can be achieved in future iterations.

Appendix

Tools and Libraries Used:

->Python

->Pandas

->Matplotlib & Seaborn

->Scikit-Learn

->Statsmodels

->Dataset: Personal step count data collected from a fitness tracker application.
