 AI-ML-Task3

Step-by-step Explanation:
   1. Data Loading & Cleaning:
         > Loaded dataset using pandas.
         > Removed missing values and duplicates to ensure clean input.
   2. Feature & Target Selection:
         > Chose one column for simple linear regression (X) and the dependent variable (y).
         > For multiple regression, select multiple features in X = df[['col1', 'col2', ...]].
   3. Train-Test Split:
         > Split data using train_test_split() with 80% for training and 20% for testing.
   4. Model Training:
         > Used LinearRegression() from Scikit-learn to fit the model on training data.
   5. Evaluation:
       Measured accuracy using:
           > MAE (Mean Absolute Error)
           > MSE (Mean Squared Error)
           > R² Score (Explains how well predictions match the real values)
   6. Visualization:
         > Plotted actual vs. predicted values with a regression line (only for simple regression).
 
