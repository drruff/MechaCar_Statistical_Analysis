# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

- From the below image we can see that the intercept, vehicle length, and ground clearance have a non-random effect on MPG

insert image:

Is the slope of the linear model considered to be zero? Why or why not?

- The slope of the linear model would not be considered zero when we look at the below image we can see our p-value is much below 0.05 which says we can reject the null hypothesis, and thus the slope cannot be considered zero.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

- This model does not predict mpg of MechaCar prototypes effectively due to overfitting of our data. There was only 2 of our variables that had an impact out of the six and our intercept was statstically significant. All together this would imply we cant use this model to predict.

 
## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

- Looking below we can see that the Total Lot variance, and Lot 1 and Lot 2's variance are all below 100 PSI, however, we can see that Lot 3's variance is 170 PSI (rounded to integer), Lot 3 has a large variance and removing Lot 3 will result in the total variance to be much lower than it currently is.

- This shows that just looking at Total can be misleading as Lot 3 does not meet the design specificiations for MechaCar suspension coils.