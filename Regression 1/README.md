# Blueberry Yield Value Prediction Model Stacking

## Overview
This project focuses on predicting the yield for blueberries using a stacking model approach. Multiple data manipulation techniques were applied to ensure optimal conditions for the dataset.

---

## Important Steps in the Project

### 1. K-means 'Segment' Feature Creation
I implemented K-means clustering on the dataset (excluding the target column) to create a robust feature representing segments within the data.

![K-means Feature Engineering](screenshots/feature_eng_Kmeans.png)

### 2. Model Architecture
The architecture of the model used for prediction is as follows:

![Model Architecture](screenshots/model_architecture.png)

### 3. Results
The Mean Absolute Error (MAE) was used as the competition metric. Below are the prediction results showcasing the model's performance:

![Prediction/Model Performance](screenshots/prediction_results.png)

---

## Conclusion
This project demonstrates the effectiveness of using advanced modeling techniques and feature engineering in predicting blueberry yields. The results indicate potential improvements in yield prediction accuracy.

