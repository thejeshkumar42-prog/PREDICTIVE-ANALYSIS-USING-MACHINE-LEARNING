# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

# TASK 2: MACHINE LEARNING PREDICTIVE ANALYSIS

# COMPANY: CODTECH IT SOLUTIONS PRIVATE LIMITED

NAME: N THEJESH KUMAR

INTERN ID: CITS575

DOMAIN: DATA ANALYTICS

DURATION: 8 WEEKS

MENTOR: NEELA SANTHOSH KUMAR

# DESCRIPTION

This project was completed as part of the Data Analytics Internship at CODTECH IT Solutions Private Limited. The objective of this task was to build a machine learning model capable of predicting sales using historical retail data. Machine learning is an important area of data analytics because it enables organizations to make predictions and support data-driven decision-making. In this project, a Linear Regression algorithm from the Scikit-learn library was used to develop a predictive model.

The project was implemented using Python in Google Colab. Several Python libraries were used, including Pandas for data handling, NumPy for numerical operations, Matplotlib for visualization, and Scikit-learn for machine learning model development and evaluation. The dataset used for this project was the Sample Superstore dataset, which contains information about customer orders, product categories, quantities, discounts, profits, and sales.

The first step involved loading the dataset into a Pandas DataFrame. After confirming that the data was loaded correctly, the relevant input features and target variable were selected. The model used Quantity, Discount, and Profit as input features, while Sales was selected as the target variable to be predicted. These variables were chosen to demonstrate the complete machine learning workflow while keeping the project simple and easy to understand.

The dataset was divided into training and testing sets using the train_test_split() function. Eighty percent of the data was used to train the model, while the remaining twenty percent was reserved for testing. This approach helps evaluate how well the trained model performs on unseen data and reduces the risk of overfitting.

A Linear Regression model was created using the Scikit-learn library and trained using the training dataset. Once the model finished training, predictions were generated for the testing dataset. The predicted sales values were then compared with the actual sales values to measure the performance of the model.

Several evaluation metrics were calculated to assess prediction quality. These included Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and the R² Score. The obtained results were:

Mean Absolute Error (MAE): 245.08
Mean Squared Error (MSE): 680377.46
Root Mean Squared Error (RMSE): 824.85
R² Score: -0.1518

The negative R² Score indicates that the Linear Regression model did not accurately predict the Sales values using only the selected features. This outcome is expected because sales are influenced by many additional factors such as product category, customer segment, shipping mode, region, state, and other business variables that were not included in the model. This demonstrates the importance of feature selection and feature engineering in machine learning projects.

To visualize the model's performance, an Actual vs Predicted Sales scatter plot was created using Matplotlib. This visualization provides a simple comparison between the actual sales values and the values predicted by the model. Such visualizations help analysts understand prediction patterns and identify areas where the model could be improved.

Overall, this project successfully demonstrated the complete machine learning pipeline, including data loading, preprocessing, feature selection, model training, prediction, performance evaluation, and visualization. It also highlighted the importance of selecting meaningful features to improve prediction accuracy. The project enhanced practical knowledge of supervised machine learning, regression analysis, and model evaluation techniques, providing valuable hands-on experience in predictive analytics.

# OUTPUT

<img width="1045" height="808" alt="Image" src="https://github.com/user-attachments/assets/b4f0e920-c7f8-406d-8774-a93338903389" />
