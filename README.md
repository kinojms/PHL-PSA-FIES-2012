# STINTSY Group 9 MP: Family Income and Expenditure Survey 2012 Analysis

## Overview

This project analyzes the [Family Income and Expenditure Survey (FIES) 2012 Vol 1](https://psada.psa.gov.ph/catalog/38/get-microdata) dataset from the Philippine Statistics Authority. The analysis includes data cleaning, preprocessing, exploratory data analysis, feature categorization, normalization, and visualization.

## Group Members

- Brillantes, Althea Kaitlin
- Flores, Jerimaya Dennielle
- Sacdalan, Justine Morrie
- Togado, Dalrianne Francesca

## Getting Started

1. **Requirements**
   - Python 3.x
   - Jupyter Notebook
   - pandas, numpy, matplotlib, seaborn, shap, xgboost, scikit-learn

2. **Installation**
   Install dependencies using pip:
   ```sh
   pip install pandas numpy matplotlib seaborn shap xgboost scikit-learn
   ```

3. **Usage**
   - Open the notebook either in VS Code or Jupyter Notebook.
   - Run the cells to reproduce the analysis.

## Project Workflow

1. **Data Loading**
   - The raw data is loaded from `DATA.CSV`.

2. **Data Cleaning**
   - Missing values and duplicates are handled.
   - Whitespace is replaced with zeros.
   - Cleaned data is saved as `cDATA.csv`.

3. **Exploratory Data Analysis**
   - Statistical summaries and visualizations are generated.
   - Features are categorized as categorical or numerical.

4. **Normalization**
   - Z-score normalization is applied to numerical features.

5. **Visualization**
   - Various plots and charts are created to explore the data.

## Data Dictionary

See [`fies_2012_v1_metadata(dictionary).xlsx`](PHL-PSA-FIES-2012-V1-PUF/fies_2012_v1_metadata(dictionary).xlsx) for variable descriptions.

## License

This project is for academic purposes only. Data is provided by the Philippine Statistics Authority.

---

*For questions, please contact me using sacdalanjme@gmail.com with the Subject "FIES Project"

Thanks for dropping by, cheers!
