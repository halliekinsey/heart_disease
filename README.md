## Heart Disease Analysis

### Repository Overview

This repository contains an in-depth analysis of heart disease using various datasets. The goal is to understand the factors affecting heart disease and to build predictive models to identify its presence based on patient data.

---

### Datasets

There are multiple datasets in this repository that provide data related to heart disease. The primary datasets used for the analysis include:

- `processed.cleveland.data`
- `processed.switzerland.data`
- `processed.va.data`
- `reprocessed.hungarian.data`

For a more comprehensive analysis and exploratory data investigation, a combined dataset `all_data_heat_disease.csv` has been created. This dataset amalgamates the information from the datasets mentioned above.

---

### Repository Structure

```
heart+disease/
│
├── costs/                          # Directory containing data related to costs
│
├── Final_Report_0_4.ipynb          # Main analysis Jupyter notebook
│
├── Index                           # File providing index information
│
├── WARNING                         # File containing warnings related to data or analysis
│
├── all_data_heat_disease.csv       # Combined dataset for exploratory analysis
│
├── analysis.ipynb                  # Additional analysis Jupyter notebook
│
├── ask-detrano                     # File with specific queries or information
│
├── bak                             # Backup file
│
├── cleve.mod                       # Model file related to the Cleveland dataset
│
├── cleveland.data                  # Dataset providing data from Cleveland
│
├── heart-disease.names             # File describing dataset names and details
│
├── hungarian.data                  # Dataset providing data from Hungary
│
├── long-beach-va.data              # Dataset providing data from Long Beach VA
│
├── new.data                        # New dataset with potential updates
│
├── processed.cleveland.data        # Processed dataset from Cleveland for refined analysis
│
├── processed.hungarian.data        # Processed dataset from Hungary for refined analysis
│
├── processed.switzerland.data      # Processed dataset from Switzerland for refined analysis
│
├── processed.va.data               # Processed dataset from VA for refined analysis
│
└── reprocessed.hungarian.data      # Reprocessed dataset from Hungary with additional refinements
```

---

### Project Summary

The Heart Disease dataset is a comprehensive collection of patient data aimed at understanding the presence of heart disease. The primary focus of our analysis using this dataset has been to distinguish between the presence and absence of heart disease.

We began with data acquisition and cleaning, followed by preliminary data exploration. The analysis then delved into correlation analysis to understand the relationship between various variables. We also compared multiple models to determine the most effective ones for predicting heart disease.

Furthermore, the analysis provided a deep dive into influential factors in heart disease prediction, as well as an exploration into gender differences in the dataset. Through extensive analysis and modeling, we identified key variables that are influential in predicting heart disease. The models utilized have varying degrees of accuracy, with Random Forest and Logistic Regression performing exceptionally well. The deep dive into gender differences provided insights into physiological and lifestyle variables that significantly differ between males and females.

---

### Contributing

For any questions, issues, or contributions, please open an issue on the GitHub repository. Your feedback and contributions are highly appreciated.

---

### Authors

- **Zain Ali**
- **Ben Hopwood**
- **Hallie Kinsey**

---

### Clone the Repository

To clone this repository, open your terminal or command prompt and run the following command:

```bash
git clone https://github.com/zainalijp/AAI-500-01.git
```

---

### Acknowledgments

We would like to express our gratitude to the UCI Machine Learning Repository for providing the dataset, and to our professors and mentors for their guidance throughout the project.

---

**Repository Link**: [Heart Disease Analysis GitHub Repository](https://github.com/zainalijp/AAI-500-01)
