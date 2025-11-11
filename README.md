✈️ Denver Airport Congestion Prediction using Machine Learning

This project focuses on predicting airport congestion at Denver International Airport (DEN) using advanced machine learning and data analytics techniques. The analysis explores two scenarios — one predicting a continuous variable (diff) representing the difference between scheduled and actual flights, and another predicting a categorical variable (status) indicating “normal” or “congested” conditions.

🔍 Key Highlights:

Data Preprocessing: Cleaned and transformed raw flight data by handling missing values, outliers (via IQR), and multicollinearity.

Feature Engineering: Encoded temporal features (day, month, year) and identified key influencers such as temperature and day of the week.

Scenario 1 – Regression:

Tested models — Linear Regression, Decision Tree, Random Forest, SVM, and Gradient Boosting.

Random Forest achieved the best performance (R² ≈ 0.66), effectively predicting the continuous difference in flight volume.

Scenario 2 – Classification:

Implemented Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and Neural Network.

Random Forest again performed best, with an accuracy of ~84%, identifying congestion patterns effectively.

PyCaret Comparison: Compared results from PyCaret AutoML with traditional modeling, observing differences in metric outputs due to preprocessing and parameter handling.

Tools & Libraries: Python, Pandas, NumPy, Scikit-learn, PyCaret, Matplotlib, Seaborn.

🚀 Future Enhancements:

Apply hyperparameter tuning (GridSearchCV, RandomizedSearchCV) to improve accuracy.

Address class imbalance using SMOTE or similar techniques.

Integrate external datasets (weather, flight delays).

Deploy models using Streamlit or Flask for real-time predictions.

This project demonstrates strong capabilities in data preprocessing, feature engineering, predictive modeling, and performance evaluation — providing actionable insights to improve airport operations and congestion management.
