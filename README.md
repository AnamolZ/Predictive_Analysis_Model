# Predictive_Analysis_Model

Predicting the price of a Context based on its features using a machine learning model. We have implemented the following features:

1. **Data Loading and Preprocessing**: The code reads the car price data from the CSV file and preprocesses it. We handle missing values and perform label encoding for the 'Brand' and 'Condition' columns.

2. **Model Training**: The data is split into training and testing sets using a 80-20 split. We use a Random Forest Regressor model to train on the data.

3. **User Input Prediction**: The user can input the features - car's mileage, age, previous owners number, brand, and condition. The model then predicts the price of the context - car based on this input.

4. **Model Evaluation**: We evaluate the model's performance using the R-squared score and Root Mean Squared Error (RMSE) on the test set.

5. **Visualization**: We visualize the user's input prediction and the actual price for a few samples from the test set.

Feel free to explore the code and experiment with different datasets or models to improve the car price prediction accuracy.
