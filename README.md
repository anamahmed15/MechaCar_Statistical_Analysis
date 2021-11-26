# MechaCar Statistical Analysis

# Purpose
AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. This is an exploratory analysis to pinpoint the problems in order to find solutions.

# Linear Regression to Predict MPG
To predict the effect of each variable in the given dataset on the MPG rating of the new MechaCar, I performed a multiple linear regression model. For the model, the null and alternative hypotheses are:

* H0 : The slope of the linear model is 0, indicating that there is no significant linear relationship.

* Ha: The slope of the linear model is not 0, indicating a linear relationship between at least some of the variables.

The resulted output is:

![alt text](https://github.com/anamahmed15/MechaCar_Statistical_Analysis/blob/main/Plots%20and%20Results%20Images/Output%201.PNG)

The significant variables are vehicle length, ground clearance and the intercept. Since they are significant, we can reject the null hypothesis, meaning that the slope of the model is not 0 and also that there is a relationship between at least some variables and the MPG measurement. But our model still does not provide a completely accurate prediction of MPG. The R2 value is 0.71 indicating a strong correlation. However, there are factors included which dont significantly influence the outcome.

# Summary Statistics on Suspension Coils
