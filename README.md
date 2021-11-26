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
The design specifications indicate that the variance of the suspension coils must not exceed 100 pounds per square inch. To ensure we adhere to this, I created data frames containing summary statistics on suspension coil data from three different manuafacturing lots. 

![alt_text](https://github.com/anamahmed15/MechaCar_Statistical_Analysis/blob/main/Plots%20and%20Results%20Images/total_summary.PNG)

The output above shows only 76.2 pounds per square inch over all manufacturing lots, which is well within our limit. But when we group the lots together, we see:

![alt_text](https://github.com/anamahmed15/MechaCar_Statistical_Analysis/blob/main/Plots%20and%20Results%20Images/Lot%20summary.PNG)

Lots 1 and 2 have quite low variance than lot 3, which shows malmost twice the maximum allowable variance. This huge gap explains why the overall measure looks acceptable while the true results are not.

# T-Tests on Suspension Coils


