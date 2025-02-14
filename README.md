# 📊 Income Redistribution Analysis

This project explores the socioeconomic factors influencing public attitudes toward income redistribution. Using survey data, the analysis applies **predictive and interpretive modelling techniques** to uncover key drivers of redistribution preferences.

## 📂 Project Structure

- **[`ees_dataset_combine.ipynb`](ees_dataset_combine.ipynb)** – Prepares and merges survey datasets, cleaning and structuring them for analysis.
- **[`modelling_and_evaluation.ipynb`](modelling_and_evaluation.ipynb)** – Implements various machine learning models, including logistic regression, Naïve Bayes, and SVM, KNN, to predict redistribution preferences. Also includes feature selection, hyperparameter tuning (GridSearchCV), and interpretability analysis.
- **[`full_analysis.ipynb`](full_analysis.ipynb)** – A comprehensive notebook that integrates both data processing, visulization, and modelling.
- **[`combined_data.csv`](combined_data.csv) / [`cleaned_combined_data_1.csv`](cleaned_combined_data_1.csv)** – Processed datasets used for the whole project.
- **[`updated_variable_list.csv`](updated_variable_list.csv)** – Overview of the variables included in the dataset.
- **[`educational_level_table.png`](educational_level_table.png)** – A visualization of educational mobility levels.

## 🔍 Key Methods

- **Feature Selection**: RFE and Mutual Information.
- **Predictive Modelling**: One-vs-All Logistic Regression, Naïve Bayes, and SVM, KNN.
- **Hyperparameter Tuning**: GridSearchCV for optimizing logistic regression parameters.
- **Interpretability**: Logistic regression coefficients and odds ratios to analyze the impact of socioeconomic factors.

## 📊 Results & Insights

- **Educational Mobility & Income** significantly impact redistribution support.
- **Predictive Models** struggled with class imbalance (74% respondents in "Agree"), affecting Neutral & Disagree classifications.
- **Logistic Regression Interpretation** aligns with economic theory but has limitations in capturing complex relationships.


## 🚀 Future Directions

Further research could explore **non-linear models (Neural Networks)** to capture complex relationships beyond linear and tree-based approaches.

---


