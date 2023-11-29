# Handling Missing Data: Imputation

## Analysis of Missing Values in NHANES Data

This project focuses on handling missing values in the National Health and Nutrition Examination Survey (NHANES) dataset. The goal is to explore different strategies for addressing missing values and understand how these strategies impact the quality and interpretation of the data.

## Introduction

In this project, various techniques and methods were explored and applied to handle missing values in NHANES data. Python tools such as Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn were used to perform the analysis and imputation of missing values.

## Content

The project unfolded across the following six points:

1. Initial Exploration of Missing Values: In this section, an initial exploration of the quantity and distribution of missing values in the dataset was conducted. Graphs and visualizations were used to better understand the nature of missing values.

2. Analysis of Missing Value Patterns: This section investigated possible patterns behind missing values. Correlations and relationships between variables were explored to determine if the absence of values was related to certain factors.

3. Simple Imputation Strategies: This section examined simple imputation strategies, such as imputation with constant values, median, and mean. The advantages and disadvantages of each approach were evaluated, and visualizations were generated to compare the results.

4. Imputation Based on Statistical Methods: More advanced methods, such as imputation by interpolation and imputation using the KNN algorithm, were explored. The concepts behind these methods were explained, and demonstrations of how to apply them to NHANES data were provided.

5. Imputation by Regression Models: Regression model imputation was employed to estimate missing values based on relationships between variables. The model-building process was detailed, and the application for filling missing values was demonstrated.

6. Multiple Imputations by Chained Equations (MICE): The MICE approach, which uses conditional regression models for iterative imputation, was introduced. The methodology was discussed, and an implementation in the project was demonstrated.

## Results

Throughout the project, the following was achieved:

- Identification and understanding of the distribution of missing values in the NHANES dataset.
- Evaluation and comparison of different imputation strategies, from simple approaches to more complex model-based methods.
- Application of advanced techniques such as interpolation, KNN, and regression models for imputation.
- Understanding how the choice of an imputation strategy affects the data distribution and relationships between variables.
- Familiarity with the MICE approach and its application for iterative imputation.

## Conclusion

Missing values analysis is a crucial step in the data analysis process. Choosing the right strategy depends on the dataset context and analysis objectives. This project provides a comprehensive introduction to handling missing values and offers a variety of approaches to address this challenge.

# Author
José Pablo Cabrera Romo

## Additional Resources

If you want to explore more about handling missing values and enhance your data analysis skills, here are some additional resources:

- [Numpyninja's Explanation of the MICE Algorithm](link_to_numpyninja_explanation)
- [Pandas Documentation](link_to_pandas_docs)
- [scikit-learn Documentation](link_to_scikit_learn_docs)
- [Seaborn Documentation](link_to_seaborn_docs)
  
## Installation guide

Please read [install.md](install.md) for details on how to set up this project.

## Project Organization

    ├── LICENSE
    ├── tasks.py           <- Invoke with commands like `notebook`.
    ├── README.md          <- The top-level README for developers using this project.
    ├── install.md         <- Detailed instructions to set up this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries.
    │
    ├── notebooks          <- **1.0-download-data-and-load-it.ipynb:** Notebook for downloading and loading data.
  - **2.0-pandas-missing-extension.ipynb:** Notebook for Pandas missing extension.
  - **3.0-imputation-missing-values.ipynb:** Notebook for missing values imputation.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures         <- Generated graphics and figures to be used in reporting.
    │
    ├── environment.yml    <- The requirements file for reproducing the analysis environment.
    │
    ├── .here              <- File that will stop the search if none of the other criteria
    │                         apply when searching head of project.
    │
    ├── setup.py           <- Makes project pip installable (pip install -e .)
    │                         so imputation can be imported.
    │
    └── imputation               <- Source code for use in this project.
        ├── __init__.py    <- Makes imputation a Python module.
        │
        ├── data           <- Scripts to download or generate data.
        │   └── make_dataset.py
        │
        ├── features       <- Scripts to turn raw data into features for modeling.
        │   └── build_features.py
        │
        ├── models         <- Scripts to train models and then use trained models to make
        │   │                 predictions.
        │   ├── predict_model.py
        │   └── train_model.py
        │
        ├── utils          <- Scripts to help with common tasks.
            └── paths.py   <- Helper functions to relative file referencing across project.
        │
        └── visualization  <- Scripts to create exploratory and results oriented visualizations.
            └── visualize.py

---
