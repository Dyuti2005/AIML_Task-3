https://colab.research.google.com/drive/13niADaPi_VNlFmUYDa_ZwgXgmjac2TQI?usp=sharing

Task 3: Linear Regression on Housing Data
 Objective
To build a Multiple Linear Regression model that predicts house prices based on features like area, bedrooms, bathrooms, and location factors.

Steps Taken
Preprocessing: Converted categorical variables (mainroad, airconditioning, etc.) into binary integers. Applied one-hot encoding to furnishingstatus.
Splitting: Divided the data into an 80/20 train-test split to ensure unbiased evaluation.
Modeling: Used Scikit-Learn to fit a Linear Regression model.
Evaluation: * MAE: Represents the average dollar amount the model is off.
R² Score: Indicates how much of the variance in house prices is explained by the model (e.g., 0.65 means 65% accuracy in trend).
Visualization: Plotted a regression line showing the strong positive correlation between area and price.

 Key Insights:
Area and Bathrooms typically have the highest positive coefficients, meaning they are the strongest drivers of house price.
The negative coefficient for furnishingstatus_unfurnished (if present) indicates that unfurnished houses sell for significantly less.
