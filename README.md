# Parkinsons-Detection
> A Machine Learning Model that Detects Parkinsons Disease with a 98% Accuracy Score

____

### Modules/Libraries Required:
 - NumPy
 - Pandas
 - MinMaxScaler
 - XGBoost Classifier

____

### Features & Labels
 - Features --> Columns that are used as inputs for prediction. In this case, every column except "status" is a feature.
 - Labels --> The predicted value(s) of the dataset.  In this case, "status" is a label as it tells us the final predicted value of the given input(s) of the dataset.

____

### Normalizing Dataset
 Scale the values of the features between -1 and 1 to normalize them.

____

### Testing & Training Dataset
 - Used for splitting the existing dataset into test & train.
 - Train Dataset is used for training the model.
 - Test Dataset is used to validate the trained model with data it has not seen before.
 - It helps give an objective Accuracy Score of the model

____

### XGBoost Classifier Model
 - XGBoost --> eXtreme Gradient Boosting
 - Uses Gradient Boosting Machine Learning Algorithm

____

#### Prediction
 - Testing the trained model with the Validation/Test Dataset.
 - Calculating the Accuracy Score of the Predicted Values with the Actual Values
