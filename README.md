# Classification-of-Astronomical-Objects-

This Python-based project harnesses machine learning techniques for the classification of stellar objects - galaxies, stars, and quasars - using data from the Sloan Digital Sky Survey (SDSS). SDSS, renowned for its extensive space observations, utilizes a 2.5m diameter telescope at the Apache Point Observatory in New Mexico, equipped with a 30 CCD-Chip camera. This setup captures high-resolution images across five optical filters (u, g, r, i, z), enabling detailed space analysis. Our project focuses on processing this rich data through sophisticated algorithms to accurately categorize various celestial bodies. It's an innovative blend of astrophysics and machine learning, offering valuable insights into the cosmos.

## Methodologies:

We start exploring visually the data in order to try to understanding patterns in the quantitative variables gathered from the measurements. In order to solve the classification problem, after doing some feature engineering and a train/test split of 33% size, we use the ensemble learning XGBoost algorithm in order to retrieve the features hierarchy importances. In a second step in order to validate the model we use GridSearchCV with 2 folds and obtain the score on the test set  for the 1st fold 0.9904477611940299 and 0.991044776119403 for the second.
