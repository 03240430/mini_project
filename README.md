# mini_project
# Retail Sales Forecasting Using LSTM for Inventory Planning and Business Decision-Making

## 1. Project Overview

This group project explores the use of time series forecasting to predict future retail sales and support better inventory planning and business decision-making. The project will analyse historical sales data, identify trends and seasonal patterns, and develop forecasting models to estimate future demand.

An LSTM (Long Short-Term Memory) neural network will be investigated alongside suitable baseline forecasting methods to evaluate whether deep learning improves forecasting performance.

## 2. Objectives

- Analyse historical retail sales data and identify trends and seasonality.
- Clean and preprocess the dataset for time series forecasting.
- Develop suitable baseline forecasting models and an LSTM model.
- Evaluate forecasting performance using MAE, RMSE, and MAPE where appropriate.
- Compare actual sales with predicted sales using visualisations.
- Recommend ways businesses can use forecasts to improve inventory planning.

## 3. Project Scope

The project will cover data exploration, preprocessing, chronological training and testing, model development, performance evaluation, visualisation, and business recommendations.

## 4. Tools and Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- TensorFlow/Keras
- Jupyter Notebook or Google Colab
- Git and GitHub

## 5. Group Members and Work Division

| Member | Responsibilities |
|---|---|
| Probin | Introduction, problem statement, objectives, literature review, dataset description, and project background |
| Ugyel | Data preprocessing, exploratory data analysis, chronological data splitting, baseline forecasting, LSTM implementation, and evaluation metrics |
| Chimi | Results analysis, actual-versus-predicted visualisations, discussion, business recommendations, conclusion, references, and final report formatting |

All members will review the final report, verify the results, and contribute to the final presentation.

## 6. Project Workflow

1. Define the forecasting problem and select a suitable dataset.
2. Explore and clean the historical sales data.
3. Analyse trends, seasonality, and other relevant patterns.
4. Split the data chronologically into training, validation, and test sets.
5. Develop baseline forecasting methods.
6. Build and train the LSTM model.
7. Evaluate and compare model performance using appropriate metrics.
8. Visualise the results and interpret their business implications.
9. Prepare the final report and presentation.

## 7. Evaluation Metrics

- **MAE:** Mean Absolute Error
- **RMSE:** Root Mean Squared Error
- **MAPE:** Mean Absolute Percentage Error, when appropriate for the dataset

The LSTM model will be compared with baseline methods using the same test period. The evaluation will consider forecasting accuracy, limitations, and practical usefulness for inventory planning.

## 8. Repository Structure

```text
Retail-Sales-Forecasting/
├── data/
│   └── README.md
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_preprocessing.ipynb
│   └── 03_forecasting_models.ipynb
├── src/
│   └── README.md
├── results/
│   └── README.md
├── report/
├── presentation/
├── requirements.txt
├── .gitignore
└── README.md
```

## 9. Getting Started

1. Clone this repository.
2. Install the required Python libraries listed in `requirements.txt`.
3. Obtain the dataset and place it in the appropriate data directory.
4. Open the notebooks in Jupyter Notebook or Google Colab.
5. Run the notebooks in the documented order.

## 10. Expected Outcomes

The project aims to produce a comparison of forecasting approaches, interpretable visualisations, an evaluation of model performance, and practical recommendations for improving retail inventory planning.

Actual performance and conclusions will be reported after the experiments are completed.

## 11. Academic Integrity and Data Sources

The dataset, research papers, libraries, and other external resources used in the project will be acknowledged in the final report. The methodology and findings will be documented transparently.

## 12. Project Status

**Status:** In progress

**Topic:** Time Series Forecasting

**Project Type:** Group academic project
