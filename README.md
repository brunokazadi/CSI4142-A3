
# CSI4142 Assignment 3: Predictive Analysis

This repository contains the Jupyter Notebooks for Assignment 3 of CSI4142 Fundamentals of Data Science. The project involves two separate empirical studies:
- **Regression:** Predicting numerical values using linear regression.
- **Classification:** Predicting categorical outcomes using decision trees.

Both notebooks follow an end-to-end machine learning pipeline including data cleaning, exploratory data analysis (EDA), outlier detection, feature engineering, model training, evaluation, and result analysis.

---

## Repository Contents

- **A3_Part1.ipynb**  
  *Regression Empirical Study with Linear Regression*  
  - **Dataset:** Medical Insurance Cost Prediction Dataset  
  - **Key Features:** Age, Sex, BMI, Children, Smoker, Region, Charges  
  - **Objective:** Predict insurance charges using a linear regression model.
  - **Highlights:**
    - Data cleaning (missing values, invalid entries)
    - One-hot encoding of categorical variables
    - Outlier detection using IQR and Local Outlier Factor (LOF)
    - Feature engineering to create additional predictors
    - Model evaluation with train/validation/test split and 4-fold cross-validation (using metrics like MSE and R²)

- **A3_Part2.ipynb**  
  *Classification Empirical Study with Decision Trees*  
  - **Dataset:** Clothes Price Prediction Dataset  
  - **Key Features:** Brand, Category, Color, Size, Material, Price  
  - **Objective:** Predict the category of clothing items using a decision tree classifier.
  - **Highlights:**
    - Data cleaning (handling missing values and duplicates)
    - EDA and visualizations (using matplotlib and seaborn)
    - Outlier detection with LOF
    - Feature engineering to derive new features (e.g., price squared, relative price)
    - Model training using DecisionTreeClassifier with cross-validation (evaluated using accuracy and other relevant metrics)

- **CSI4142-Assignment3-Description.pdf**  
  Detailed assignment instructions and evaluation criteria.

---

## Datasets

### Medical Insurance Cost Prediction Dataset (Regression)
- **Purpose:** Predict medical insurance charges.
- **Attributes:**
  - **Age:** Policyholder's age
  - **Sex:** Gender
  - **BMI:** Body mass index
  - **Children:** Number of children covered
  - **Smoker:** Smoking status
  - **Region:** Residential area
  - **Charges:** Medical insurance charges (target variable)
- **Source:** [Kaggle Medical Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

### Clothes Price Prediction Dataset (Classification)
- **Purpose:** Predict the category of clothing items.
- **Attributes:**
  - **Brand:** Clothing brand name
  - **Category:** Type of clothing item (e.g., T-shirt, Jeans)
  - **Color:** Color of the item
  - **Size:** Item size (e.g., XS, S, M, L, XL)
  - **Material:** Fabric type (e.g., Cotton, Wool)
  - **Price:** Numerical price of the item
- **Source:** *Link provided within the notebook or dataset description*

---

## How to Use

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/brunokazadi/CSI4142-A3.git
   cd CSI4142-A3
   ```

2. **Install Dependencies:**

   Ensure you have Python 3.x installed. Install the required packages using pip:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

3. **Run the Notebooks:**

   Launch Jupyter Notebook or JupyterLab:

   ```bash
   jupyter notebook
   ```

   Open and run the notebooks sequentially:
   - `A3_Part1.ipynb` for the regression study.
   - `A3_Part2.ipynb` for the classification study.

4. **Examine Outputs:**

   Each notebook is designed to be executed cell by cell. Outputs, visualizations, and evaluation metrics will be generated to help you understand each step of the process.

