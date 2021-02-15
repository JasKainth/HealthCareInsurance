# HealthCareInsurance

## Summary

In this analysis, we will attempt to both analyze the factors which affect the price of health care insurance and also accuractely predict the health care insurance of an individual. 

## Static Analysis/Exploratory Data Anlysis

### Factors/Discrete Variables


The table below shows some statistics of how the charges were distributed within the factors we had.  

![Factors Table](https://github.com/JasKainth/HealthCareInsurance/blob/main/variables%20table.png)  

We first note the difference in the mean and median; likely occuring due to the smoker charges being much higher than non-smoker charges. Also, it should be noted that the first Quartile of the smoker case has a value higher than the mean or median of any other case. 

The plots below shows us boxplots of these variables, with one plot adjusting for smokers. 
Factors Boxplot        |  Adjusted for Smoker
:------------------------:|:---------------------:
![Boxplot](https://github.com/JasKainth/HealthCareInsurance/blob/main/discrete.jpg)  |  ![Boxplot Adjusted](https://github.com/JasKainth/HealthCareInsurance/blob/main/discrete_smoker.jpg)  

### Continuous Variables

The continuous variables we had for our data were the Age and BMI of the individual. BMI (Body Mass Index) is calculated as the mass of a person divided by their square height (expressed as kg/m^2). The plot below shows the relationship of the variables vs the response variable, after we adjust for a person being a smoker.  
![Continuous Plot](https://github.com/JasKainth/HealthCareInsurance/blob/main/continuous_smoker.jpg)


### Response Variable

The response variable for our dataset was the charges of a person (in USD). Since we want to determine which factors increase/decrease our response variable, we will first create a linear model, so we need to test if our response variable is normally distributed. Below, are two plots of the unadjusted & adjusted response variable (log transformation).


![Response](https://github.com/JasKainth/HealthCareInsurance/blob/main/response.jpg)

 ![Adjusted Response](https://github.com/JasKainth/HealthCareInsurance/blob/main/response_adjusted.jpg) 