# Exploratory Data Analysis
## By Innocent Wesa

 # Dataset 1(insurance.csv)
 > The second dataset contains information about health insurance charges.A person is offered insurance depending on a number of factors like age, bmi or if the person is a smkoker or non-smoker.
 > I did some feature engineering and divided the age and bmi columns into different categories
 
## Summary of Findings(Dataset 1)


> A majority of the smokers belong to the old_adults bracket and the young_adults are the least.

> Their is not that much of a relationship between age and bmi because their is a slight difference in their mean,older adults have a higher bmi compared to young adults.

> Females and males have almost the same bmi, although the male's bmi is higher seconded by females.

> The old adults are charged the most and the young adults the least.

> People with a higher bmi are charged more compared to those with less.

> Both smokers and non-smokers have almost the same bmi.

>I applied a gradient boosting algorithm to do predictive analysis. My independent variable was bmi and dependant charges.

>The model did not perform well with an accuracy of 0.07 on the test set and 0.02 on the training data.The model was not fit for the predictive analysis. 