Project scenario

A leading healthcare organization wants to predict the likelihood of a patient getting a stroke based on their medical history and demographic information. As a data scientist, you're responsible for building a well-validated stroke prediction model using patient characteristics. Your task will include loading, cleaning, processing, analyzing, visualizing data, and building and deploying the prediction model for clinical use. The model will help the organization mitigate the growing problem of strokes and improve patient outcomes.

Summary

Utilized Random Forest for stroke prediction; despite high accuracy, poor sensitivity in identifying strokes limits practical use, impacting patient care.


Solution
The solution achieved high accuracy but failed to detect any strokes (positive class). While sensitivity for no strokes was excellent, specificity for strokes was zero, indicating a critical issue in identifying positive cases. To meet project objectives, the model must accurately predict strokes, necessitating further refinement for improved sensitivity and specificity balance.


Approach

1.Data Preparation: Loaded dataset, handled missing values, encoded categorical variables.

2.Model Training: Used Random Forest for stroke prediction based on 11 features.

3.Evaluation: Analyzed confusion matrix, accuracy, sensitivity, and specificity.

4.Deployment Preparation: Serialized the model for future use in healthcare systems.

5.Analysis: Identified model's high accuracy but poor performance in detecting strokes, requiring further improvement.
