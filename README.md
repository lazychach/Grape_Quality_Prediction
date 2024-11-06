Project Overview

This project analyzes and predicts the quality of grape samples using various features, including environmental factors, physical characteristics, and chemical properties. The main objective is to classify grape samples into predefined quality categories (Low, Medium, High, Premium) and approximate a continuous quality score for each sample.

Using a dataset of grape samples, this project applies multiple machine learning models—Random Forest, Gradient Boosting Trees, etc.—and performs feature analysis to understand which factors influence grape quality most. Key steps include data preprocessing, feature engineering, model training, and evaluation.
Dataset

The dataset used for this project contains detailed information on grape samples, including:

    Sample Identification: sample_id, variety, region
    Quality Metrics: quality_score, quality_category
    Physical and Chemical Properties: sugar_content_brix, acidity_ph, cluster_weight_g, berry_size_mm
    Environmental Factors: day_of_year (derived from harvest_date), sun_exposure_hours, soil_moisture_percent, rainfall_mm

Each sample is labeled with a quality category, which serves as the target variable for classification tasks.

