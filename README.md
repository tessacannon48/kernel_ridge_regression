## Overview
This repository contains my completed coursework for COMP186: Foundations of Artificial Intelligence. The coursework involves building and evaluating machine learning models using a real-world dataset of video lectures. Key tasks include data preprocessing, exploratory data analysis, feature engineering, and model evaluation.

## Objectives
The coursework aims to:
1. Develop a systematic approach to training machine learning models.
2. Enhance understanding of regression models and their implementation.
3. Demonstrate theoretical and practical knowledge of machine learning concepts.

## Repository Structure
```
root/
├── README.md         # This file
├── notebook.ipynb    # Jupyter notebook containing code and analysis
├── lectures_dataset.csv  # Dataset used in the analysis
```

## Key Components
### Exploratory Data Analysis (EDA)
- Analyzed dataset to understand distributions and relationships.
- Visualized numeric and categorical variables.
- Checked for missing values and outliers.

### Data Preprocessing
- Implemented frequency encoding for high-cardinality categorical variables.
- Applied KNN imputation for missing data.
- Removed outliers using interquartile range thresholds.
- Selected key features using statistical methods.
- Normalized numeric features to improve model performance.

### Model Development
- Trained and evaluated two models:
  - Ridge Regression
  - Kernel Ridge Regression with Gaussian Kernel
- Conducted hyperparameter tuning to optimize model performance.

### Evaluation Metrics
Implemented:
1. Root Mean Square Error (RMSE) for model error.
2. R-squared (R²) for goodness of fit.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
   ```
2. Navigate to the directory:
   ```bash
   cd repository-name
   ```
3. Open the notebook in Jupyter:
   ```bash
   jupyter notebook notebook.ipynb
   ```
4. Run the cells in order to execute the analysis and train the models.

## Notes
- This repository showcases my approach to solving the coursework problems.
- Original coursework-related details (e.g., specific instructions and TA contact information) have been removed for professional presentation.

## License
This project is for educational purposes and should not be used for commercial purposes.

---

For any questions or feedback, feel free to reach out or open an issue in the repository.
