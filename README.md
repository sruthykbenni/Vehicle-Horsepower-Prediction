Vehicle Horsepower Prediction using Multiple Linear Regression

Project Overview:

This project applies Multiple Linear Regression (MLR) to predict engine horsepower using real-world vehicle data. The dataset contains various features like vehicle dimensions, fuel efficiency, and engine statistics. The goal is to build a predictive model that accurately estimates a vehicle’s horsepower based on its attributes.

Dataset:

The dataset used in this project includes the following key features:

-Vehicle Dimensions (Height, Length, Width)

-Engine Specifications (Number of Forward Gears, Torque, Horsepower)

-Fuel Efficiency (City MPG, Highway MPG)

-Categorical Attributes (Encoded using One-Hot Encoding)

Methodology:

1. Data Preprocessing

-Loaded the dataset and performed Exploratory Data Analysis (EDA).

-Handled missing values and removed duplicate rows.

-Encoded categorical variables using One-Hot Encoding.

2. Feature Engineering & Selection

-Standardized numerical features using StandardScaler.

-Checked for multicollinearity using Variance Inflation Factor (VIF).

-Dropped highly correlated variables to enhance model performance.

3. Model Training & Evaluation

-Split the dataset into 80% training & 20% testing.

-Trained a Linear Regression model.

-Evaluated performance using:

-Mean Squared Error (MSE)

-R-squared Score (R²)

4. Outlier Detection & Improvement

-Used Z-score to identify and remove outliers.

-Retrained the model on the cleaned dataset and compared performance.

Results & Insights:

-Removing multicollinear features improved model stability.

-Handling outliers led to better generalization and an improved R² score.

-Feature selection played a key role in enhancing model accuracy.

Installation & Usage:

#Requirements:

Python 3.x

Pandas

NumPy

Scikit-learn

Seaborn

Matplotlib

Statsmodels

▶️ Run the Project

1. Clone the repository

2. Navigate to the project folder

3. Install dependencies

4. Run the Python script
