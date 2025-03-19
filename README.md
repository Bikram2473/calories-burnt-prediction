# **Calories Burnt Prediction Model using Machine Learning**

# **Overview**
This project implements a Calories Burnt Prediction Model using various Machine Learning algorithms. The model is trained on a dataset that includes attributes such as Age, Height, Weight, Duration, and Gender to predict the number of calories burnt during physical activities.

# **Technologies Used**
**i) Pandas:** For data manipulation and loading the dataset into a DataFrame.<br/>
**ii) NumPy:** For numerical computations and efficient array operations.<br/>
**iii) Matplotlib & Seaborn:** For visualizing relationships and data distributions.<br/>
**iv) Scikit-learn (sklearn):** For preprocessing, model training, and evaluation.<br/>
**v) XGBoost:** For high-accuracy gradient boosting predictions.<br/>
**vi) RandomForest, LinearRegression, Lasso, Ridge:** For building regression models.<br/>

# **Dataset**

The model utilizes two datasets:<br/>
**i) calories.csv**<br/>
**ii) exercise.csv**<br/>

These datasets are merged to create a unified dataset for training and evaluation.

# **Data Preprocessing**
**i) Feature Selection:** Removed highly correlated features to reduce redundancy.<br/>
**ii) Encoding:** Converted categorical values like 'male' and 'female' to numerical values.<br/>
**iii) Train Test Split:** Split data into training (90%) and validation (10%) sets.<br/>
**iv) Scaling:** Standardized numerical features for better model performance.

# **Data Visualization**
i) Scatter plots were used to analyze relationships between features and calories burnt.<br/>
ii) Distribution plots provided insights into the spread of numerical data.<br/>
iii) A heatmap was generated to check for multicollinearity.

# **Machine Learning Models Used**
The following models were trained and evaluated using **Mean Absolute Error (MAE):**
i) Linear Regression<br/>
ii) XGBoost Regression<br/>
iii) Lasso Regression<br/>
iv) Random Forest Regressor<br/>
v) Ridge Regression<br/>

# **Model Performance**
The models were tested on both training and validation datasets, and their errors were recorded to compare performance.

# **How to use**
i) **Clone the repository:**<br/>
git clone https://github.com/Bikram2473/calories-burnt-prediction.git

ii) **Install Dependencies:**<br/>
pip install numpy pandas matplotlib seaborn scikit-learn xgboost

iii) **Run the scripts:**<br/>
python predict.py
