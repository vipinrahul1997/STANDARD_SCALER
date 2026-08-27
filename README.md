Standard Scaler standardizes numerical features by subtracting the mean and dividing by the standard deviation, 
resulting in features with mean 0 and standard deviation 1.

Standard Scaler does not change the relationship between the observations. 
It changes the scale and center of the feature.

Also, Standard Scaler is sensitive to outliers, because mean and standard deviation are affected by extreme values.
When there are many outliers, Robust Scaler may be more appropriate.
