# Effect_of_Different_Models_and_Hyperparameters
This repository explores the impact of different machine learning models and hyperparameter tuning techniques on the performance of regression tasks. Specifically, it focuses on training models to predict ship travel time using various feature sets and comparing the results across multiple models and hyperparameter configurations.

Key Features:
Multiple Model Comparisons: The project tests various models, including traditional machine learning algorithms like Gradient Boosting and Neural Networks using Keras.
Hyperparameter Tuning: Utilizes GridSearchCV for hyperparameter optimization, including tuning model architecture, learning rate, dropout rate, batch size, and epochs for neural networks.
Data Preprocessing: Features include geospatial data (latitude, longitude), speed over ground (SOG), and temporal features like timestamp and time of day (AM/PM).
Performance Metrics: Models are evaluated using standard regression metrics, including mean absolute error (MAE), mean squared error (MSE), and R² score to assess the quality of predictions.
Objective:
The goal of this repository is to analyze and compare the performance of various regression models and assess how tuning hyperparameters impacts their predictive capabilities. The experiments aim to provide insights into the best models and hyperparameters for predicting travel times based on the given ship dataset.

Technologies Used:
Python
Pandas (for data manipulation)
Scikit-learn (for model training and hyperparameter tuning)
TensorFlow/Keras (for deep learning models)
Matplotlib (for data visualization)
Use Cases:
Predicting travel times in logistics or shipping industries.
Benchmarking different machine learning models for regression tasks.
Understanding the effects of hyperparameter tuning on model performance.
