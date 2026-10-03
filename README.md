# MainCrafts AIML Internship - Task 1

## California Housing Price Prediction using Linear Regression

This project was completed as part of the MainCrafts Technology Artificial Intelligence and Machine Learning Internship.

The objective of this task is to build a Machine Learning model using Linear Regression to predict California housing prices based on various housing and demographic features.

---

## Project Objective

The main objectives of this project are:

- Load and understand the California Housing dataset
- Perform Exploratory Data Analysis (EDA)
- Check for missing values
- Analyze relationships between variables
- Split the dataset into training and testing sets
- Train a Linear Regression model
- Generate predictions
- Evaluate the model using MAE, RMSE, and R²
- Visualize actual and predicted house values
- Interpret the model results and discuss possible improvements

---

## Dataset

The project uses the California Housing dataset available through Scikit-learn.

The dataset contains:

- 20,640 records
- 8 input features
- 1 target variable

### Features

| Feature | Description |
|---|---|
| MedInc | Median income |
| HouseAge | Median house age |
| AveRooms | Average number of rooms |
| AveBedrms | Average number of bedrooms |
| Population | Population of the area |
| AveOccup | Average household occupancy |
| Latitude | Geographic latitude |
| Longitude | Geographic longitude |

### Target Variable

**MedHouseVal** - Median house value.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Model

A Linear Regression model was trained using 80% of the dataset and evaluated using the remaining 20%.

### Data Split

- Training data: 16,512 records
- Testing data: 4,128 records
- Test size: 20%
- Random state: 42

---

## Model Evaluation

The trained Linear Regression model produced the following results on the test dataset:

| Metric | Result |
|---|---:|
| MAE | 0.5332 |
| RMSE | 0.7456 |
| R² Score | 0.5758 |

The R² score indicates that the model explains approximately 57.58% of the variation in the target variable for the test data.

---

## Visualization

The project includes a scatter plot comparing actual house values with the values predicted by the Linear Regression model.

The visualization helps understand how closely the predictions follow the actual values.

---

## Project Files

### `task1_ml_linear_regression.ipynb`

Jupyter Notebook containing:

- Dataset loading
- Data exploration
- EDA
- Missing-value analysis
- Data splitting
- Model training
- Predictions
- Model evaluation
- Visualization
- Model interpretation

### `MainCrafts_AIML_Task1_Report.pdf`

A detailed project report containing the methodology, results, evaluation metrics, visualization and conclusions.

---

## Conclusion

A Linear Regression model was successfully developed to predict California median house values.

The model achieved an MAE of 0.5332, RMSE of 0.7456 and R² score of 0.5758 on the test dataset.

The project demonstrates the complete basic Machine Learning workflow, from data loading and exploration to model training, prediction, evaluation and visualization.

---

## Possible Improvements

The model could potentially be improved by:

- Trying more advanced regression algorithms
- Performing feature engineering
- Applying feature scaling where appropriate
- Hyperparameter tuning
- Handling outliers
- Comparing multiple Machine Learning models
- Using cross-validation
