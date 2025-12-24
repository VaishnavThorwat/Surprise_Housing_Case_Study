# Surprise Housing Case Study

## 1. Executive Summary

This project identifies the primary drivers of residential property values in Surprise, USA, using advanced regression techniques. By analyzing 1,460 home sales and 81 features, we developed a model capable of predicting SalePrice with high accuracy.

Key Analytical Findings:

Predictive Power: The final model explains roughly 90% of the variance in housing prices on the training set, with Lasso regression providing the most reliable feature selection.

Top Value Drivers: Property value is most sensitive to Overall Quality, Above Grade Living Area (GrLivArea), and Modernity (YearBuilt/YearRemodAdd).

Market Skew: Initial analysis revealed a significant positive skew in prices (Skewness: 1.88), which was successfully corrected using a Log Transformation to normalize the target variable.

## 2. Project Overview

Housing price prediction is a critical challenge for buyers, sellers, and real estate professionals. The Surprise Housing Case Study addresses this by exploring a comprehensive dataset of residential properties to uncover patterns and build models that estimate sale prices with high accuracy. The solution developed combines statistical analysis and machine learning to provide actionable insights and reliable predictions.

## 3. Data

- **Source:** [Kaggle](https://www.kaggle.com/), open housing dataset for Surprise, USA.
- **Size:** ~1,400 records, 81 features per record.
- **Key Features:**
  - `SalePrice`: Final price of the house (target variable)
  - `GrLivArea`: Above-ground living area
  - `TotalBsmtSF`: Basement area
  - `OverallQual`: Overall material and finish quality
  - `YearBuilt`, `YearRemodAdd`: Construction and renovation year
  - Multiple categorical features related to location, style, and amenities

## 4. Methodology

1. **Data Cleaning:** Handling missing values, correcting data types, and removing outliers.
2. **Exploratory Data Analysis (EDA):** Visualizing distributions, correlations, and trends with plots and summary statistics.
3. **Feature Engineering:** Creating new features, encoding categorical variables, and selecting relevant predictors.
4. **Modeling:** Building regression models (Linear Regression, Ridge, Lasso) and evaluating performance using metrics like R² and RMSE.
5. **Validation:** Cross-validation and test set evaluation to ensure generalizability.

## 5. Key Inferences/Findings

- **Model Performance:** The best model achieved an R² score of 0.81, explaining 81% of the variance in house prices.
- **Influential Features:** `OverallQual`, `GrLivArea`, and `TotalBsmtSF` were the most impactful predictors.
- **Market Insights:** Recently renovated homes command a ~15% premium, and material quality strongly affects price.
- **Data Gaps:** Some amenities, such as pools and garages, had limited influence compared to area and quality.

## 6. Technologies/Libraries

- **Programming Language:** Python
- **Libraries/Tools:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook

## 7. How to Use

1. **Clone the repository:**
    ```bash
    git clone https://github.com/VaishnavThorwat/Surprise_Housing_Case_Study.git
    ```
2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3. **Run the analysis:**
    - Open the Jupyter notebooks in the `notebooks/` folder.
    - Follow the step-by-step workflow: data cleaning, EDA, feature engineering, and modeling.

## 8. Contact

For questions or feedback, please contact:

- **Name:** Vaishnav Thorwat  
- **GitHub:** [VaishnavThorwat](https://github.com/VaishnavThorwat)  
- **Email:** thorwatvaishnav@gmail.com

---
