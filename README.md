**Crop Yield Prediction Using Random Forest Regression**

This project demonstrates how to predict crop yield using a Random Forest Regressor based on agricultural and environmental features. The model is trained and evaluated using the full dataset and visualized with a scatter plot.
____

**Features**

Uploads dataset using Google Colab

Preprocesses categorical data using one-hot encoding

Trains a Random Forest Regression model

Evaluates performance using R² Score and Mean Squared Error (MSE)

Visualizes Actual vs Predicted Crop Yield
____
**Technologies Used**

Python

Pandas

Scikit-learn

Matplotlib

Google Colab
____
**Expected Columns**

soil_type (categorical)

crop_type (categorical)

yield (target variable)

Other numerical features related to agriculture/environment
_____
**Workflow**

Upload dataset using files.upload()

Load dataset with Pandas

Convert categorical columns into numerical format using get_dummies()

Split features (X) and target (y)

Train the Random Forest Regressor

Predict crop yield on training data

Evaluate model using R² Score and MSE

Plot Actual vs Predicted Yield
_____

**Model Evaluation**

R² Score indicates how well the model explains yield variation

Mean Squared Error (MSE) measures prediction error
_____
**Output**

Console output showing:

R² Score

Mean Squared Error
_____
