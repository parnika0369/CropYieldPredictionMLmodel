This repository contains a machine learning model designed to predict crop yield using historical agricultural data. The project leverages data preprocessing, feature engineering, and regression-based algorithms to estimate crop production with improved accuracy.


Key Features

Utilizes historical crop, soil, and weather datasets

Data cleaning, normalization, and exploratory data analysis (EDA)

Machine learning model trained using regression techniques (e.g., Linear Regression, Random Forest, or LSTM for time-series)

Model evaluation using metrics such as MAE, RMSE, and R²

Visualizations to understand yield trends



Applications

Agricultural planning & decision-making

Yield forecasting for farmers and stakeholders

Smart farming and agri-tech solutions

Tech Stack


Python • NumPy • Pandas • Scikit-learn • Matplotlib/Seaborn • TensorFlow/PyTorch



Random Forest: Actual vs Predicted Crop Yield

The plot visualizes the performance of the Random Forest regression model by comparing the actual crop yield values (x-axis) with the predicted yield values (y-axis).
Each blue point represents a test sample, while the red dashed line indicates the ideal perfect-prediction line where predicted = actual.

<img width="921" height="668" alt="Screenshot 2025-11-25 213248" src="https://github.com/user-attachments/assets/29c5cd31-1286-4a89-b999-d72ce52fce7d" />

Linear Regression: Actual vs Predicted Crop Yield

This plot shows how the Linear Regression model performs by comparing actual crop yield values (x-axis) with the predicted yield values (y-axis).
Each blue point represents a sample from the test set. The red dashed diagonal line indicates the ideal prediction line where actual and predicted values would perfectly match.

The wide spread of points away from this line demonstrates that the Linear Regression model struggles to capture the complex relationships in the data, leading to higher prediction errors compared to more advanced models like Random Forest.


<img width="838" height="697" alt="Screenshot 2025-11-25 213300" src="https://github.com/user-attachments/assets/fe57a1ff-011f-4b4b-8c32-1940442eef96" />




Model Performance Visualization
This scatter plot displays the actual vs. predicted crop yield values using the best-performing model (Random Forest in this case) for Rice cultivation in Uttar Pradesh.


<img width="907" height="867" alt="Screenshot 2025-11-25 213625" src="https://github.com/user-attachments/assets/473776de-eced-4a89-bbf4-6cb0ab56ddb0" />


Live Prediction Interface
This screenshot demonstrates the crop yield prediction system in action, showcasing a real-world usage example for Maize cultivation.




<img width="631" height="470" alt="Screenshot 2025-11-25 213841" src="https://github.com/user-attachments/assets/ca5b526c-3f5f-4f36-b6eb-87cb3aa3af13" />





<img width="1726" height="518" alt="Screenshot 2025-11-25 214058" src="https://github.com/user-attachments/assets/ae0fb7b3-2bf5-4b38-afc8-f37e458ad704" />





<img width="1777" height="554" alt="Screenshot 2025-11-25 214349" src="https://github.com/user-attachments/assets/83358f6c-7aa8-4d1c-9f45-6d88a284d7f7" />

