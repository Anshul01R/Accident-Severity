# Predicting Accident Severity using Machine Learning

This project analyzes the US Road Accidents dataset and uses machine learning techniques to predict the severity of traffic accidents. By leveraging this dataset, the goal is to build reliable models, gain insights into contributing factors, and propose strategies to enhance road safety.

# Dataset

The dataset contains extensive details of road accidents that occurred in the United States, including features like weather conditions, road types, time of day, and more.

Key Features:

Numerical Features: Temperature, Wind Speed, etc.

Categorical Features: Weather Condition, Road Surface, etc.

Target Variable: Accident Severity (1 to 4).

Methodology

  # 1. Data Preprocessing:

      Data Cleaning:

      Handled missing values and outliers.

      Encoded categorical variables using one-hot encoding.

      Scaled numerical features.

      Feature Engineering:

            Created new features such as time-based categories (e.g., rush hours).

            Assessed feature importance for model optimization.

  # 2. Data Splitting:

      Training Set: 75%

      Validation Set: 15%

      Test Set: 10%

  # 3. Model Training:

      The following algorithms were implemented and evaluated:

                Logistic Regression: Achieved a maximum accuracy of 75%.

                K-Nearest Neighbors (KNN): Accuracy reached 74%.

                Decision Trees: Moderately accurate with potential overfitting.

                Random Forest: Performed similarly to Logistic Regression with an accuracy of 75%.

# Results

| Model                  | Accuracy |
|------------------------|----------|
| Logistic Regression    | 75%      |
| K-Nearest Neighbors    | 74%      |
| Decision Trees         | 73%      |
| Random Forest          | 75%      |

# Traffic Accident Data Visualizations

## Heatmap of Accidents
This heatmap shows the density of road accidents across the United States:
![Heatmap of Accidents](images/heatmap_accidents.png)

## County-Wise Accident Clustering
This scatter plot shows the spatial distribution of accidents categorized by counties:
![County Accident Scatter Plot](images/scatter_plot_counties.png)



# Key Findings:

    Logistic Regression and Random Forest are the best-performing models, each achieving 75% accuracy.

    Accident severity prediction depends significantly on weather, road conditions, and time of day.

    Feature engineering (e.g., creating time-based categories) helped improve model performance slightly.

# Recommendations

    Feature Refinement: Use advanced feature selection techniques or domain knowledge to uncover more influential predictors.

    Data Augmentation: Incorporate external datasets like real-time traffic or weather data for improved predictions.

    Mitigation Strategies:

          Enhance road infrastructure in high-accident areas.

          Adjust traffic rules during bad weather or high-risk times.
