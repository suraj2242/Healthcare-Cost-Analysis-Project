# Healthcare-Cost-Analysis-Project
---

## Two-Way ANOVA Analysis

This repository contains a Jupyter Notebook that performs a Two-Way ANOVA analysis on a medical cost dataset. The analysis aims to explore the impact of age and smoking status on medical charges.

## Dataset

The dataset used in this analysis is the **Medical Cost Dataset**. It contains the following columns:
- **Age**: Age of the individual.
- **Smoker**: Smoking status (smoker or non-smoker).
- **Charges**: Medical charges incurred by the individual.

## Hypotheses

1. **Age and Medical Charges**:
   - **Null Hypothesis (H₀₁)**: Age is not associated with differences in medical charges.
   - **Alternative Hypothesis (Hₐ₁)**: Age is associated with differences in medical charges.

2. **Smoking Status and Medical Charges**:
   - **Null Hypothesis (H₀₂)**: Smoking status (smoker vs. non-smoker) is not associated with differences in medical charges.
   - **Alternative Hypothesis (Hₐ₂)**: Smoking status is associated with differences in medical charges.

3. **Interaction Effect**:
   - **Null Hypothesis (H₀₃)**: There is no interaction effect between age and smoking status on medical charges.
   - **Alternative Hypothesis (Hₐ₃)**: There is an interaction effect between age and smoking status on medical charges (the impact of one factor on charges depends on the level of the other factor).

## Analysis Steps

1. **Importing Libraries**:
    - Pandas
    - Statsmodels
    - Matplotlib

2. **Loading Data**:
    - Load the dataset from a CSV file.

3. **Data Preprocessing**:
    - Filter the columns of interest (age, smoker, charges).
    - Handle missing values by dropping any rows with missing data.

4. **Data Exploration**:
    - Display the first few rows of the dataset.
    - Perform stratified sampling to ensure a balanced representation of smokers and non-smokers.

5. **Fitting the Model and Running ANOVA**:
    - Fit a Two-Way ANOVA model using age and smoking status as factors.
    - Perform the ANOVA and display the results.

## Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/TwoWayAnova.git
    ```
2. Navigate to the repository directory:
    ```sh
    cd TwoWayAnova
    ```
3. Install the required libraries:
    ```sh
    pip install pandas statsmodels matplotlib
    ```
4. Run the Jupyter Notebook:
    ```sh
    jupyter notebook TwoWayAnova.ipynb
    ```

## Results

The results of the Two-Way ANOVA are displayed in the notebook. They include the sum of squares, degrees of freedom, F-statistic, and p-values for the main effects and interaction effects.

## Acknowledgements

- The dataset was obtained from a publicly available source.
- The analysis was performed using the Python programming language and various data science libraries.
