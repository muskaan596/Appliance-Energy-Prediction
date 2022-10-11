# Appliance-Energy-Prediction
•	Analyzed the dataset in jupyter’s notebook by initializing all the python libraries which are required for EDA.  
•	Many columns in the dataset were not normally distributed and target column is also right skewed. 
•	Cleaned the data by checking for null values, duplicate values and outliers. 
•	Then we used matplotlib and seaborn to do Exploratory Data Analysis on sample data by plotting different graphs like  bar plot, boxplot, subplot and heat map (from this we got useful insights and correlation between target column and other features) 
•	Hours column is in high correlation with dependent variable and there were a lot of features having less than 0.1 correlation with dependent variable. 
  It is a non-linear dataset. 
•	Energy consumption in the month of march is high and low in the month of January. 
•	Increase in temperature leads to more energy consumption and Decrease in Humidity leads increase in power consumption. Humidity is inversely proportional to dependent variable. 
•	Hour of the Day is the most important influencing parameter for Energy consumption
• High Electricity consumption of >140Wh is observed during evening hours 16:00 to 20:00.  
•	Weekends (Saturdays and Sundays) are observed to have high consumption of electricity. (> 25% than Weekdays) 
• Polynomial regression is the best model. Its performance is good as compared to others algorithms. It has high r2 value. 
