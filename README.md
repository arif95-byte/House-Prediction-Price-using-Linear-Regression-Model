# House-Prediction-Price-using-Linear-Regression-Model
Hi, I come up with a new project called house prediction price using linear regression model. Hope you guys enjoyed it.

# Problem Statement:
A real estate company want to predict of a house based on features like the number of bedrooms, sqaure footage, and location.

# Dataset:
Help from ChatGPT to create a dataset with bedrooms, square footage, location score and price as a column.

![output (2)](https://github.com/user-attachments/assets/7646000b-143f-477e-8956-16e3045dbc9a)
The image above represents the price of house depends on the number of bedrooms and square footage of the house.

# Model Choice: Linear Regression
Since the target variable (house price) is a continous number, hence I use Linear Regression model.
The model learns a relationship between the input features (Bedrooms, Square Footage, Location Score) and the target variable (Price).

# Prediction Example:
- 3 bedrooms
- 1700 square foot
- location score of 7

# Use Case:
- Real estate agents can use this model to estimate home prices for buyers and sellers.
- Companies can adjust prices dynamically based on location and demand.

# Model Performance:
- Mean Absolute Error (MAE): $483.21 - $ on average, predictions are off by about $483
- Mean Squared Error (MSE): 234
- Root Mean Squared Error (RMSE): 483.89
- Predicted Price for New House (3 beds, 1700 sqft, location score 7): $267,95.12

# Recommendation:
- Feature Engineering: Adding more features like age of the house, number of bathrooms, or neighborhood quality could improve accuracy.
- Hyperparameter Tuning: Trying different polynomial degrees or using regularization techniques (Ridge/Lasso) to avoid overfitting.
- More Data: A larger dataset would help the model generalize better.

# Trend Analysis:
![output (3)](https://github.com/user-attachments/assets/65ff86f8-fa60-4f8a-baeb-448bfec67b09)
House Prices vs Square Footage
- The trend shows a positive correlation between square footage and house price.
- Larger homes tend to have higher prices.

![output (4)](https://github.com/user-attachments/assets/4ec1213c-093e-4c96-b62c-70fb2de030d7)
House Prices vs Number of Bedrooms
- There is a weaker correlation between the number of bedrooms and house price.
- While more bedrooms generally increase the price, other factors (e.g., house size, location) influence pricing more significantly.

# Key Takeaways:
- Square footage has a stronger impact on price compared to just the number of bedrooms.
- A larger house (sqft) is a better indicator of price than simply the number of rooms.

# Conclusion:
I have fun in doing this project, working on this project help me to understand better on how linear regression model works. I hope you guys enjoyed this project as much as I do. Thank you.
