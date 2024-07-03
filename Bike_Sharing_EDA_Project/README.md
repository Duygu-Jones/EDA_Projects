
<h1 align="center">
📍 Bike-Sharing Demand Analysis and Prediction  🚲♻️🌱
  
EDA + ML Project🚀
</h1>


<p align="center">
  <img src="https://github.com/Duygu-Jones/EDA_Projects/blob/main/Bike_Sharing_EDA_Project/img/bike.gif" alt="Bike Sharing GIF">
</p>


## Executive Summary:

- This project aims to analyze and predict bike-sharing demand using historical data.
- By examining factors such as seasonality, weather conditions, and time of day, we developed a predictive model to forecast bike share counts. 
- The insights gained from this analysis can help optimize bike-sharing operations, ensuring better resource allocation and improved user satisfaction.


### Business Problem

- The bike-sharing program must effectively manage its fleet to meet varying yearly demands. 
- Key challenges include understanding how seasonal changes, weather conditions, holidays, and weekends impact bike usage. 
- Accurate demand prediction is essential for efficient bike distribution, reducing operational costs, and enhancing user experience.

  
### Objectives

1. **Analyze Bike Sharing Patterns**: Understand seasonal, daily, and hourly trends in bike sharing usage.
2. **Assess Impact of External Factors**: Evaluate how weather conditions, holidays, and weekends affect bike sharing demand.
3. **Feature Engineering**: Develop and transform features to improve model accuracy.
4. **Build Predictive Model**: Train a Random Forest model to predict bike share counts.
5. **Evaluate Model Performance**: Use performance metrics and visualizations to assess model accuracy.
6. **Provide Actionable Insights**: Recommend optimising bike sharing operations based on analysis findings.



### About the Dataset: 

![](https://github.com/Duygu-Jones/EDA_Projects/blob/main/Bike_Sharing_EDA_Project/img/londonbike.jpg)


- **Structural Analysis**  
    - **Dataset**: store.sharing.csv
    - **Content:** The change in the number of bike shares in London according to seasons, temperature, wind speed, etc.
    - **Number of Rows**: 17414
    - **Number of Columns**: 10   

   
INPUTS:

    - **timestamp**: Timestamp field for grouping the data
    - **cnt**: The count of new bike shares
    - **t1**: Real temperature in °C
    - **t2**: Temperature in °C "feels like"
    - **hum**: Humidity in percentage
    - **wind_speed**: Wind speed in km/h
    - **weather_code**: Category of the weather
          - "weather_code" category description:
             1 = Clear; mostly clear but have some values with haze/fog/patches of fog/fog in vicinity
             2 = Scattered clouds / few clouds
             3 = Broken clouds
             4 = Cloudy
             7 = Rain/light rain shower/light rain
             10 = Rain with thunderstorm
             26 = Snowfall
             94 = Freezing fog
    - **is_holiday**: Boolean field - 1 holiday / 0 non-holiday
    - **is_weekend**: Boolean field - 1 if the day is a weekend
    - **season**: Category field meteorological seasons: 0-spring; 1-summer; 2-fall; 3-winter.


---

### Methodology


1. **Data Cleaning:** 
   - Handled missing values by imputing or removing them.
   - Removed duplicate records.
   - Corrected inconsistencies in data formatting and values.

2. **Data Transformation:** 
   - Converted data types where necessary (e.g., dates to datetime).
   - Created new features such as day, month, hour, and binary variables for holidays and weekends.
   - Aggregated data to analyze patterns over different periods.

3. **Descriptive Statistics:** 
   - Calculated mean, median, standard deviation, and other relevant statistics for numerical features to understand data distribution and central tendencies.

4. **Univariate Analysis:** 
   - Visualized the distribution of individual variables using histograms, box plots, and KDE plots to identify patterns and outliers.

5. **Bivariate Analysis:** 
   - Explored relationships between two variables using scatter plots, bar plots, and correlation matrices to understand interactions and correlations.

6. **Multivariate Analysis:** 
   - Analyzed interactions between multiple variables using pair plots and heatmaps to visualize complex relationships and patterns in the data.

7. **Time Series Analysis:** 
   - Examined trends and patterns over time using line plots to identify seasonal effects and other temporal patterns.
   - Conducted seasonal decomposition to separate time series data into trend, seasonal, and residual components.

8. **Model Training and Evaluation:** 
   - Split data into training and test sets.
   - Trained a Random Forest model to predict bike share counts.
   - Evaluated model performance using metrics like Mean Squared Error (MSE) and R² score.
   - Visualized model performance with scatter plots (actual vs. predicted values) and histograms of prediction errors.

9. **Conclusion:** 
   - Summarized key findings from the analysis, highlighting the impact of seasonality, weather, and commuting patterns on bike share demand.
   - Provided actionable recommendations for optimizing bike-sharing services based on the analysis.

This methodology outlines the steps taken in the notebook for a comprehensive analysis and modelling of bike-sharing demand.

<br>

### Skill Set:

- **Python**: Pandas, Matplotlib, Seaborn, Numpy, data cleaning, data visualization, statistical analysis.
- **Data Analysis**: Exploratory Data Analysis (EDA), handling missing values, descriptive statistics, feature engineering, correlation analysis.
- **Data Visualization**: Creating plots and charts to visualize data insights (histograms, scatter plots, heatmaps, line plots).
- **Machine Learning**: Model training (Random Forest), performance evaluation (MSE, R²), train-test split, model tuning.
- **Time Series Analysis**: Trend and seasonal pattern identification, seasonal decomposition.


<br>

#### Next Steps

To further improve the analysis and model performance:
- Integrate real-time weather data and additional external factors like public events and road conditions to enhance prediction accuracy.
- Experiment with different machine learning algorithms and hyperparameter tuning to find the best-performing model.
- Consider deploying the model for dynamic bike availability adjustments based on demand forecasts.

🚲🩵 As someone who loves cycling, I had an amazing time working on this project. It gave me deeper insights into bike-sharing systems and helped me anticipate future demand. 🔍

📍If you found this work valuable, please don't forget to give it a star🌟 and share it with your network ♻️

🌱 Every pedal counts! Keep biking and enjoy the ride! 🚴‍♂️🚴‍♀️

---

*For more details about the analysis and visualisation, check out the notebook.*

- **Notebook:** [Bike_Sharing_Demand_EDA_Project.ipynb](https://github.com/Duygu-Jones/EDA_Projects/blob/main/Bike_Sharing_EDA_Project/Bike_Sharing_Demand_EDA_Project.ipynb)
- **Download the Dataset:** [store_sharing.csv](https://github.com/Duygu-Jones/EDA_Projects/blob/main/Bike_Sharing_EDA_Project/store_sharing.csv)

*To view the notebook online, visit my Kaggle profile. Don't forget to join the discussion!*

- **Kaggle Notebook**: [Bike Sharing Demand (EDA+Prediction) 🔥🚀](https://www.kaggle.com/code/duygujones/bike-sharing-demand-eda-prediction)

---

## 🤝Contributing

Contributions are welcome! If you have any improvements, suggestions, or additional datasets and EDA projects to share, please fork the repository and create a pull request.

<br>

## 🌱About Me 

I'm Duygu Jones, a Data Scientist, passionate about data visualization, analysis, and machine learning. 

♻️ You can find more about me and my work through the following links:

- **Linkedin**: [Linkedin/duygujones](https://www.linkedin.com/in/duygujones/)
- **Website**: [duygujones.com](https://duygujones.vercel.app/)
- **Kaggle**: [kaggle.com/duygujones](https://www.kaggle.com/duygujones)
- **GitHub**: [github.com/Duygu-Jones](https://github.com/Duygu-Jones)
- **Medium**: [medium.com/@duygujones](https://medium.com/@duygujones)
- **Tableau Public**: [Duygu Jones on Tableau Public](https://public.tableau.com/app/profile/duygu.jones/vizzes)

🌐Feel free to connect with me!

<br>

🎯 Boost your exploratory data analysis skills,<br>
💡 Share your insights with the community,<br>
✨ If you find this repository helpful, don't forget to give it a ⭐ star.<br>

Code with joy! 👩‍💻✨

---



##### 📜 License

##### This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
