# House Price Prediction

## Project Overview
This project aims to predict house sale prices based on various housing features using machine learning techniques in Python. The goal is to build a model that can estimate the market value of houses accurately, which can assist buyers, sellers, and real estate professionals in making informed decisions.

## Dataset
The dataset includes multiple features describing houses such as:
- **MSSubClass**: Type of dwelling (e.g., single-family, duplex)
- **MSZoning**: General zoning classification (residential, commercial, etc.)
- **LotArea**: Lot size in square feet
- **LotConfig**: Configuration of the lot (corner, inside, etc.)
- **BldgType**: Type of building structure
- **OverallCond**: Overall condition rating of the house
- **YearBuilt**: Year when the house was built
- **YearRemodAdd**: Year when the house was remodeled or added onto
- **Exterior1st**: Exterior covering material of the house
- **BsmtFinSF2**: Type 2 finished square feet of basement area
- **TotalBsmtSF**: Total basement square feet
- **SalePrice**: Sale price of the house (target variable)

## Methodology

1. **Data Import and Exploration**: Load the dataset and perform initial exploration.
2. **Data Cleaning**: Handle missing values and remove irrelevant columns such as `Id`.
3. **Feature Encoding**: Convert categorical features to numeric using One-Hot Encoding.
4. **Data Splitting**: Split the dataset into training (80%) and testing (20%) subsets.
5. **Model Training**: Train several regression models including:
   - Linear Regression
   - Support Vector Regression (SVR)
   - Random Forest Regression
6. **Model Evaluation**: Evaluate model performance using Mean Absolute Percentage Error (MAPE) to measure prediction accuracy.

## Results
- Random Forest Regression generally performs best with the lowest MAPE.
- Linear Regression and SVR also provide reasonable performance but may underperform compared to Random Forest.
- Correlation heatmaps and categorical feature distribution plots provide insights into important predictors affecting house prices.

## How to Use

1. Clone the repository:
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction

2. Install dependencies:
pip install -r requirements.txt

3.Run the Python scripts or Jupyter notebooks to explore the data, train models, and evaluate predictions.

4.Future Improvements
Perform hyperparameter tuning to optimize model parameters.
Explore additional regression algorithms such as Gradient Boosting and XGBoost.
Deploy the model as a web application or API for real-time house price predictions.
Incorporate additional features like neighborhood statistics or economic indicators to improve accuracy.

5.Technologies Used
Python 3.x
Pandas (Data manipulation)
Matplotlib, Seaborn (Visualization)
Scikit-learn (Machine learning models and preprocessing)

Author
Veeranjaneya Inti
Email: intiveeru6619@gmail.com
LinkedIn: https://www.linkedin.com/in/veeranjaneya-inti-138157255

Feel free to contribute or raise issues for improvements!
