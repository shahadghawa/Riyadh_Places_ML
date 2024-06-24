## Riyadh Places Analysis - README

#### Overview <br />
This repository contains the project files for the analysis of cafes and restaurants in Riyadh using advanced data mining techniques. The aim is to understand their distribution, ratings, and proximity to key landmarks.


#### Abstract <br />
This study provides an in-depth analysis of cafes and restaurants in Riyadh, focusing on their distribution, ratings, and proximity to key landmarks. The methodology included data collection and preprocessing, exploratory data analysis (EDA), outlier detection, normality testing, and regression modeling. Key preprocessing steps involved handling missing values, removing duplicates, and adding new features such as neighborhood and distance metrics. Various regression models were developed, with XGBoost achieving the best performance after hyper-parameter tuning.

#### Methodology
1. Data Collection and Preprocessing
   - Handled missing values and duplicates.
   - Added new features like neighborhood and distance metrics.
   
2. Exploratory Data Analysis (EDA)
   - Analyzed the distribution and ratings of cafes and restaurants.
   - Used visualization tools to create plots and maps.
   - Detected and handled outliers.

3. Normality Testing
   - Applied Shapiro-Wilk, Anderson-Darling, and D'Agostino-Pearson tests.
   - Used Log, Square Root, and Box-Cox transformations to address non-normality.

4. Predictive Modeling
   - Implemented Linear Regression, Random Forest, and XGBoost models.
   - Performed hyper-parameter tuning on XGBoost.
   - Evaluated models using Mean Squared Error (MSE) and R² scores.

#### Results
- Distribution Analysis
  - Central Riyadh has the highest concentration of cafes and restaurants.
  - Al Yasmin, Al Shifa, and Al Aziziyah are neighborhoods with the highest concentrations.
  
- Ratings Analysis
  - Cafes generally have higher average ratings compared to restaurants.
  - Restaurants receive a significantly higher number of total ratings.

- Regression Models
  - XGBoost performed best with the lowest MSE and highest R² scores after hyper-parameter tuning.

 #### Future Work
1. Data Feature Engineering
   - Add new features like social media engagement metrics, customer demographics, and seasonal trends.

2. Normality Test and Transformation
   - Explore additional data transformation techniques to better address non-normality.

3. Separate Models for Cafes and Restaurants
   - Develop distinct models to capture specific patterns for each type of establishment.
![image](https://github.com/shahadghawa/Riyadh_Places_ML/assets/94755943/6beb37e0-59ce-4af4-9a37-d7f1bda7b794)
