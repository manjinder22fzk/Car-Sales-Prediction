

# Car Purchase Amount Prediction using Artificial Neural Networks (ANNs)

### Problem Statement

The objective of this project is to predict the dollar amount a customer is likely to spend on purchasing a car based on several independent variables. These variables include demographic information, annual income, and credit card debt.

### Data Exploration and Preparation

1. **Importing the Dataset**: The project begins by importing the dataset, which contains customer information and car purchase amounts.

2. **Data Cleaning**: Redundant variables such as customer names, email addresses, and country are removed as they do not contribute to the analysis.

3. **Data Visualization**: A pairplot is created to visually explore relationships between variables and gain insights into the data.

### Data Preprocessing

4. **Scaling Features**: Feature scaling is applied using Min-Max scaling to ensure that all input features are within the same numerical range. This helps the model converge efficiently.

### Model Development

5. **Splitting the Data**: The dataset is split into training and testing sets, with 80% used for training and 20% for testing.

6. **Creating the Neural Network**: An Artificial Neural Network (ANN) model is built using Keras. It consists of input, hidden, and output layers. ReLU activation functions are used in the hidden layers, and a linear activation function in the output layer.

7. **Compiling the Model**: The model is compiled using the Adam optimizer and Mean Squared Error (MSE) as the loss function.

8. **Training the Model**: The model is trained on the training data with a specified number of epochs and batch size. The training progress is tracked to monitor loss reduction.

### Model Evaluation

9. **Model Evaluation**: The trained model is evaluated using the testing data.

10. **Mean Squared Error (MSE)**: The MSE is calculated to assess the quality of predictions. It quantifies the average squared difference between predicted and actual values.

11. **R-squared (R²)**: The R-squared score is computed to measure how well the model explains the variance in the data. It provides an indication of the model's goodness of fit.

## Conclusion

This project demonstrates the use of Artificial Neural Networks (ANNs) for predicting car purchase amounts based on customer information. By preprocessing the data, training the model, and evaluating its performance, it becomes possible to make accurate predictions about potential car buyers' spending habits. The Mean Squared Error (MSE) and R-squared (R²) metrics are used to assess the model's accuracy and explanatory power, respectively, providing valuable insights for car sales prediction.
