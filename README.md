# Customer Churn Analysis Project

## Technical Stack

### Technologies Used:
- PySpark
- Matplotlib
- Plotly Express
- Pandas

### Steps Involved:

1. **Loading the Data and Setting up the Environment:**
   - Installing PySpark using pip
   - Importing necessary modules
   - Building Spark Session
   - Loading the dataset
   
2. **Exploratory Data Analysis (EDA):**
   - Distribution Analysis
   - Correlation Analysis
   - Univariate Analysis
   - Finding Missing Values
   
3. **Data Preprocessing:**
   - Handling Missing Values
   - Removing Outliers
   
4. **Feature Preparation:**
   - Numerical Features:
     - Vector Assembling
     - Numerical Scaling
   - Categorical Features:
     - String Indexing
     - Vector Assembling
   - Combining Numerical and Categorical Feature Vectors
   
5. **Model Training:**
   - Train-Test Data Splitting
   - Creating the Decision Tree Model
   - Training the Model
   - Making Predictions
   
6. **Model Evaluation:**
   - Calculating Area Under the ROC Curve (AUC) for the test set
   - Calculating AUC for the training set
   - Hyperparameter Tuning
   
7. **Model Deployment:**
   - Giving Recommendations using the trained model

## Final Recommendation

The bar chart displays the number of churned customers based on their contract type. It is evident that customers with a "Month-to-month" contract have a higher churn rate compared to those with "One year" or "Two year" contracts. As a recommendation, the telecommunication company could consider offering incentives or discounts to encourage customers with month-to-month contracts to switch to longer-term contracts.
