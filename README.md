Task 3: Linear Regression – Home Price Prediction
📘 Objective

The goal of this task is to implement and understand simple and multiple linear regression using the Home Price Prediction dataset. This task demonstrates how to build, train, and evaluate a regression model to predict house prices based on various features.

🧰 Tools & Libraries

Pandas – Data loading and preprocessing

NumPy – Mathematical operations

Matplotlib & Seaborn – Data visualization

Scikit-learn (sklearn) – Model training, evaluation, and splitting dataset

🗂️ Steps Followed
1️⃣ Import and Load the Dataset

The dataset is downloaded from Kaggle and uploaded to Google Colab.

Used pandas.read_csv() to load the dataset into a DataFrame.

2️⃣ Data Preprocessing

Checked for missing values and handled them appropriately (e.g., mean/median imputation).

Encoded categorical variables (if any).

Selected the target variable (Price) and feature columns (e.g., Area, Bedrooms, Bathrooms, etc.).

3️⃣ Train-Test Split

Used train_test_split from sklearn.model_selection to split the dataset into training (80%) and testing (20%) sets.

4️⃣ Model Training

Created a Linear Regression model using LinearRegression() from sklearn.linear_model.

Trained the model on the training data using .fit().

5️⃣ Model Evaluation

Made predictions on the test data using .predict().

Evaluated performance using metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

6️⃣ Visualization

Plotted:

Regression line vs actual values.

Residual plot to visualize errors.

Feature vs Target scatter plots.

📊 Key Insights

The regression line closely followed actual prices, indicating a good model fit.

Positive coefficients showed which features most influenced the increase in house price.

The R² Score represented how much variation in the target variable was explained by the model.
💡 Conclusion

This task helped understand how Linear Regression can be applied for predictive modeling. It demonstrated key ML workflow steps – data preparation, training, evaluation, and visualization.
