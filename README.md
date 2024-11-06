# Project Overview

This project analyzes and predicts the quality of grape samples using various features, including environmental factors, physical characteristics, and chemical properties. The main objective is to classify grape samples into predefined quality categories (Low, Medium, High, Premium) and approximate a continuous quality score for each sample.

Using a dataset of grape samples, this project applies multiple machine learning models—Random Forest, Gradient Boosting Trees, etc.—and performs feature analysis to understand which factors influence grape quality most. Key steps include data preprocessing, feature engineering, model training, and evaluation.

## Dataset

The dataset used for this project contains detailed information on grape samples, including:

- Sample Identification: sample_id, variety, region
- Quality Metrics: quality_score, quality_category
- Physical and Chemical Properties: sugar_content_brix, acidity_ph, cluster_weight_g, berry_size_mm
- Environmental Factors: day_of_year (derived from harvest_date), sun_exposure_hours, soil_moisture_percent, rainfall_mm

Each sample is labeled with a quality category, which serves as the target variable for classification tasks.

## Project Structure

    Grape-Quality-Classification/
    ├── data/                   # Folder containing the raw dataset and any derived datasets
    ├── notebooks/              # Jupyter notebooks for data analysis, preprocessing, and modeling
    ├── src/                    # Source code for data processing, feature engineering, and modeling
    ├── models/                 # Trained models and serialized versions for future use
    ├── results/                # Output files, including evaluation results and visualizations
    └── README.md               # Project documentation

## Key Files

data/: Contains the dataset (e.g., grape_quality.csv) and any preprocessed versions.
notebooks/: Jupyter notebooks for exploring the data, running feature analysis, and evaluating models.
src/: Python scripts for data preprocessing, feature engineering, and model training.
results/: Stores outputs, including feature importance charts, model evaluation metrics, and plots.
