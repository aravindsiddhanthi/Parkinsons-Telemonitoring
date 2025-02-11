**Overview :** 

This project focuses on predicting Parkinson’s disease severity using machine learning techniques. The dataset, sourced from the UCI Machine Learning Repository, contains 5875 records and 22 features, with "motor_UPDRS" and "total_UPDRS" as target variables. Our objective is to develop models that forecast Parkinson’s disease progression and its impact on daily life, aiding in early diagnosis and personalized treatment strategies.

**Key Steps & Methodology**

Data Exploration & Preprocessing:

Ensured data quality with no null values.
Performed statistical analysis to understand feature relationships.
Applied f-scores, mutual information, backward elimination, and Lasso regularization for feature selection.

Data Visualization:

Used histograms to analyze data distribution.
Generated correlation heatmaps to identify feature dependencies.

Model Training & Evaluation:

Implemented Random Forest Regressor and K-Neighbors Regressor within a Multi-output Regressor framework.
Evaluated models using Mean Square Error (MSE) and correctness scores.
Random Forest outperformed KNN, achieving lower MSE and higher accuracy.

Optimization & Performance Improvement:

Applied GridSearchCV for hyperparameter tuning.
Used cross-validation for robust model evaluation.
Conducted feature importance analysis to understand key predictors in Parkinson’s progression.

Key Takeaways

Machine learning models enable precise Parkinson’s progression prediction, facilitating early diagnosis and personalized treatment.
Random Forest Regression proved to be the most effective model, demonstrating superior accuracy and lower MSE.
The project underscores the importance of real-world validation, model interpretability, and clinical relevance in healthcare AI applications.

References

Dataset: UCI Machine Learning Repository - Parkinson’s Telemonitoring

Research: National Center for Biotechnology Information (NCBI)

This project showcases the potential of machine learning in healthcare, emphasizing accurate disease monitoring, improved patient outcomes, and enhanced decision-support systems for clinicians
