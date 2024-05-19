# New-York-Taxi Analysis

Ojective:
Predict average fare amounts for NYC taxi rides based on time, weather, and location factors.

Data Source: 
Yellow Taxi Trip Records for January 2019.

Initial Exploration: 
Examined dataset shape and visualized key features.

Data Cleaning:
Removed rows with null values.
Filtered out rows with fare amounts less than 0 or greater than 200.

Feature Engineering:
Extracted date and time components.
Added weather data and merged with NYC borough information.

Model Training:
Trained various models including a benchmark Decision Tree model.

Model Evaluation:
Used metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² score.

Hyperparameter Tuning:
Performed randomized search for optimizing Random Forest model.

Results:
Compared performance across models.
Random Forest model showed best predictive accuracy after optimization.

Conclusion:
Emphasized importance of data preprocessing, feature engineering, and model tuning.
Demonstrated a robust predictive model for estimating taxi fares.
