# Flight Price Prediction: EDA & Feature Engineering

## Project Overview
This project aims to predict **flight prices** using machine learning. We start with **Exploratory Data Analysis (EDA)** and apply **Feature Engineering (FE)** to prepare the dataset for modeling.

## Key Components

### 1. Exploratory Data Analysis (EDA)
- **Data Overview**: Loaded the dataset and explored its basic structure using methods like `head()` and `info()`.
- **Missing Values**: Identified missing values and used appropriate methods (e.g., forward-fill) to handle them.
- **Univariate Analysis**: Explored individual features (e.g., flight prices, duration) to understand their distributions.
- **Bivariate Analysis**: Analyzed relationships between features (e.g., price vs. duration).
- **Outlier Detection**: Visualized and handled outliers.

### 2. Feature Engineering
- **Time-based Features**: Extracted useful information such as total travel time, hours, and day of the week from date-time columns.
- **Categorical Encoding**: Applied label encoding and one-hot encoding to transform categorical variables (e.g., airline, source, destination).
- **Price Binning**: Grouped prices into different bins for more granular prediction analysis.
  
## Tools & Libraries
- **Pandas**: Data manipulation and cleaning.
- **Matplotlib/Seaborn**: Data visualization during EDA.
- **Scikit-learn**: Preprocessing and feature transformation.

## How to Run
1. Clone this repository.
2. Install the required libraries via `requirements.txt`.
3. Open and run the `eda_feature_engineering.ipynb` notebook to perform data exploration and preprocessing.

## Next Steps
With the data prepared, the next phase will involve training machine learning models to predict flight prices accurately. Stay tuned for updates!
