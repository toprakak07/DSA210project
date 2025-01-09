Step Count Analysis Project



About the Project (Motivation)


This project analyzes personal step count data collected over the years, aiming to answer the following questions:

->What are my daily, weekly, and monthly activity patterns?

->How do my step counts vary by season?

->Is there a noticeable difference in activity between weekdays and weekends?

->Can I predict future step counts using machine learning models?

->Are there any trends or correlations in my activity over time (e.g., increasing or decreasing levels of activity)?

Understanding personal activity patterns can provide valuable insights into overall health and fitness. By analyzing this data, I aim to improve my physical activity and set better goals for the future.

--------------------------------------------------------------------------------------------------------------------------
Data Source

The data used in this project is personal step count data collected between 2022 and 2024 from a fitness tracker or mobile application. The data contains the following fields:

->startDate: The starting time of the activity (in datetime format)

->endDate: The ending time of the activity (in datetime format)

->value: The total number of steps taken during the activity period

-The data has been processed and structured into a Pandas DataFrame for easier analysis and visualization.

--------------------------------------------------------------------------------------------------------------------------

Project Plan
1. Data Collection
   
->The step count data was exported from a fitness tracker application.

->The data was cleaned and structured into a format suitable for analysis using Python’s Pandas library.

2. Data Analysis

->Exploratory Data Analysis (EDA)

->Missing Data: Checked for missing values and handled them appropriately.

->General Statistics: Computed key statistics such as mean, median, and standard deviation of step counts.

->Distribution Analysis: Daily Patterns: Identified variations in step counts by time of day (morning, afternoon, evening).

->Analyzed the overall distribution of step counts using histograms and boxplots.

->Time-Based Analysis:

->Daily patterns: Identified variations in step counts by time of day (morning, afternoon, evening).

->Weekly patterns: Analyzed differences in step counts between weekdays and weekends.

->Seasonal trends: Explored how step counts vary by season (spring, summer, fall, winter).

3. Visualization
   
Step count patterns and trends have been visualized using various techniques to gain deeper insights into the data:

->Bar Charts: Display the average step count by day of the week and season.

->Line Graphs: Visualize step count trends over time (monthly and yearly).

->Boxplots: Detect outliers and understand the variability in step counts.

->Heatmaps: Show the correlation between different time periods and step counts.


----------------------------------------------------------------------------------------------------------------------

Statistical Analysis

1. ANOVA Test

->To assess whether there is a significant difference in step counts across different seasons, an ANOVA test was conducted. The test resulted in an F-value and a p-value, which indicated whether the differences were statistically significant

2. Mevsimsel Korelasyon Analizi
   
->A seasonal correlation analysis was performed to understand the similarity in step counts across different years for each season. The correlation heatmap visually represents how step counts vary between years based on seasonal patterns.

----------------------------------------------------------------------------------------------------------------------


Machine Learning Models

->The project uses machine learning models to predict future step counts:

1.Linear Regression:

->A simple model to predict step counts based on time features (year, month, day).

->The model was evaluated using Mean Absolute Error (MAE) and R² score.

2. Model Results
The following performance metrics were obtained for the linear regression model:

-->Mean Absolute Error (MAE): 43332.41
->R² Score: -0.536
(best regression model is this for this project. in the future, with more crowded data, will work better.)

----------------------------------------------------------------------------------------------------------------------

Goals

The main goals of this project are:

->Understand personal activity patterns by analyzing daily, weekly, and seasonal trends in step counts.

->Visualize step count data using insightful graphs.

->Build predictive models to forecast future step counts.

->Gain insights into how physical activity changes over time and identify areas for improvement.

Tools and Technologies

The following tools and technologies were used in this project:

->Python: For data analysis and visualization

->Pandas: For data manipulation and cleaning

->Matplotlib and Seaborn: For creating customized and aesthetically pleasing visualizations

->Scikit-Learn: For building and evaluating machine learning models

--------------------------------------------------------------------------------------------------------------------------

Future Work

->Collect more data to improve the accuracy of machine learning models.

->Use advanced machine learning models (e.g., Random Forest or ARIMA) to better capture complex patterns in the data.

->Incorporate additional features such as weather conditions or heart rate data to enhance analysis.

->Develop a step count recommendation system based on personal activity patterns and goals.
