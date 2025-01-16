Census Data Analysis and Machine Learning Pipeline

This project explores a census dataset containing 569,740 observations across 19 features. The analysis includes descriptive analytics, classification, regression, association rule mining, and clustering to extract meaningful patterns and predictive insights.

Key Features:
Descriptive Analytics:

Analyzed the distribution of demographic and social attributes, identifying patterns such as regional religion distribution and correlations between age, hours worked, and social grade.
Addressed missing and redundant data, including handling the '-9' category and duplicate entries.
Visualized insights using heatmaps, scatter plots, and box plots.
Classification (Approximated Social Grade):

Applied three classifiers to predict social grade:
Decision Tree (Accuracy: 82.45%)
Random Forest (Accuracy: 83.65%)
Linear Discriminant Analysis (Accuracy: 74.90%)
Random Forest demonstrated the best performance, showcasing balanced precision and recall across all social grade categories.
Regression (No of Hours):

Compared Linear Regression and MLPRegressor for predicting the 'No of Hours' attribute.
MLPRegressor outperformed Linear Regression with a higher R² score (76.11%) and lower errors (MAE: 0.3366).
Association Rule Mining:

Applied the Apriori algorithm to uncover relationships between demographic attributes.
Derived rules such as "Employees, Male, White" are 1.241 times more likely to work 31–48 hours full-time.
Clustering:

Implemented DBSCAN and K-Means for unsupervised clustering of census data.
Both algorithms identified dominant clusters, with DBSCAN offering finer granularity (e.g., noise points).
Silhouette scores (~0.21) indicated moderate cluster cohesion.
Technologies and Libraries:
Python: Primary programming language for analysis.
Pandas and NumPy: Data manipulation and processing.
Matplotlib and Seaborn: Data visualization.
Scikit-learn: Classification, regression, and clustering.
Mlxtend: Association rule mining with Apriori.
Applications:
This project has applications in:

Social and demographic analytics for government policy-making.
Predictive modeling for workforce and social behavior trends.
Market segmentation and clustering for businesses targeting specific demographics.

Future Improvements:
Improve clustering by incorporating advanced algorithms such as Gaussian Mixture Models.
Apply deep learning models for regression to capture complex patterns.
Perform additional feature engineering to enhance model performance.
This project highlights the power of machine learning and statistical analysis in deriving actionable insights from large-scale datasets.
