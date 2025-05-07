# Soil-nutrients-prediction
Building a multi-output regression model to predict the availability of 11 essential soil nutrients (e.g., N, P, K, Ca, Mg, etc.) using soil and environmental data from farms across Africa. The goal is to help calculate nutrient gaps that maize crops need to achieve a target yield of 4 tons per hectare.
## Data set description
The dataset of 7744 samples and 44 columns, including:
Soil features (pH, organic carbon, bulk density, etc.)
Environmental features (climate variables like bio1, bio12)
Target columns: 11 nutrient levels in parts per million (ppm).This are: 'N', 'P', 'K', 'Ca', 'Mg', 'S', 'Fe', 'Mn', 'Zn', 'Cu', 'B'

## Model Building
You used a RandomForestRegressor inside a MultiOutputRegressor to predict all 11 nutrients at once:

## Model Evaluation
* Evaluated model performance using the following metrics:

* R² Score: Measures how well the model explains variance in the data.

* MAE (Mean Absolute Error): Average absolute error.

* RMSE (Root Mean Squared Error): Penalizes larger errors more than MAE
