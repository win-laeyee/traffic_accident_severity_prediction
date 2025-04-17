# Traffic Accident Severity Prediction

This project aims to predict the severity level of traffic accidents in the United States using machine learning. Leveraging real-world data from [US Accident Dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents), the pipeline involves data preprocessing, feature engineering, model training, and evaluation.


## Project Overview

Understanding the potential severity of a traffic accident can help emergency responders, transportation agencies, and city planners make informed decisions and prioritize resource allocation.

This project focuses on:

- Cleaning and preprocessing raw accident data
- Extracting time-based and geospatial features
- Exploring multiple classification models
- Evaluating performance with metrics
- Visualizing feature importances and model insights

## Project Structure

```
traffic_accident_severity_prediction/
│
├── data/                    # Contains preprocessed datasets
├── notebooks/               # Jupyter notebooks for exploration, preprocessing and modeling
│   ├── models/              
│   ├── data_preprocessing/
│   └── eda.ipynb
├── requirements.txt         # Python dependencies
├── README.md                # Project documentation
└── .gitignore
```

## Features Used

Key features engineered and used in modeling include:

- Time features
- Weather conditions
- Location
- Road infrastructure details

## Models

- SVM
- Random Forest
- XGBoost
- OrdinalGBT
- Neural Networks

## Evaluation Metrics

- Accuracy1
- Accuracy2
- Weighted F1-score
- Confusion Matrix

## Requirements

Install dependencies using:

```pip install -r requirements.txt```

## Running the Project
Run the entire pipeline step-by-step using the provided Jupyter notebooks.
