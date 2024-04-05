# sales-forcasting

# Notebook Documentation

---

## 1. Introduction:
   - This notebook aims to provide insights into a sales dataset and develop predictive models for sales forecasting.

## 2. Libraries Used:
   - The notebook utilizes various Python libraries for data manipulation, visualization, preprocessing, model building, and evaluation:
     - NumPy and Pandas for data handling.
     - Seaborn and Matplotlib for visualization.
     - Scikit-learn for preprocessing and modeling.

## 3. Data Import:
   - The dataset is imported from two CSV files: `train.csv` and `test.csv`.

## 4. Exploratory Data Analysis (EDA):
   - Basic information about the dataset such as column names, data types, and sample data are displayed.
   - Visualizations are created to analyze sales trends over time, by month, day, country, store, and product.

## 5. Feature Engineering:
   - Date columns are transformed to extract features like month, day, day of week, quarter, week of year, etc.
   - New features such as weekend, Sunday, Fourier features, COVID feature, and holiday features are engineered based on date and country-specific holidays.

## 6. Data Preprocessing:
   - Categorical variables like country, store, and product are encoded to ordinal values.
   - Irrelevant columns like 'id' and 'date' are dropped.
   - Standard scaling is applied to numerical features.

## 7. Model Building and Evaluation:
   - Two models are trained and evaluated:
     - Linear Regression
     - Gradient Boosting Regressor
   - Cross-validation scores and evaluation metrics are calculated for each model.
   - Visualization of model scores is presented.

## 8. Conclusion:
   - The notebook concludes with a summary of the models' performance and recommendations for further analysis or model refinement.
