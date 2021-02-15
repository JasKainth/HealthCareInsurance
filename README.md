# HealthCareInsurance

## Summary

In this analysis, we will attempt to both analyze the factors which affect the price of health care insurance and also accuractely predict the health care insurance of an individual. 

## Static Analysis/Exploratory Data Anlysis

The table below shows some statistics of how the charges were distributed within the factors we had.  

![Factors Table](https://github.com/JasKainth/HealthCareInsurance/blob/main/variables%20table.png)  

We first note the difference in the mean and median; likely occuring due to the smoker charges being much higher than non-smoker charges. Also, it should be noted that the first Quartile of the smoker case has a value higher than the mean or median of any other case. 

The plots below shows us boxplots of these variables, with one plot adjusting for smokers. 
Factors Boxplot        |  Adjusted for Smoker
:------------------------:|:---------------------:
![Boxplot](https://github.com/JasKainth/HealthCareInsurance/blob/main/discrete.jpg)  |  ![Boxplot Adjusted](https://github.com/JasKainth/HealthCareInsurance/blob/main/discrete_smoker.jpg)