# Analysis-on-Airline-Passenger-Satisfaction-using-ML

✈️Airline Passenger Satisfaction – ML Classification
 Overview:

This project predicts airline passenger satisfaction using machine learning models.
Airlines receive thousands of feedback entries daily, and analyzing them helps in:

Improving customer experience

Retaining loyal passengers

Identifying weak service areas

 Objective:

Predict whether a passenger is Satisfied or Neutral/Dissatisfied.

Build classification models and identify the most accurate model.

 Dataset:

Size: ~129,000 records, 25+ features

Features include:

Demographics: Age, Gender, Customer Type, Travel Type, Class

Service Ratings: Seat comfort, Inflight WiFi, Boarding, Cleanliness, etc.

Delay details: Arrival & Departure delays

Target Variable: Passenger Satisfaction

 Data Preprocessing

Dropped duplicates and unnecessary columns (id, unnamed:0)

Handled missing values (e.g., filled Arrival Delay with mean)

Outlier treatment using IQR method

Encoded categorical variables → numeric format

Dummy variables created for Class

 Exploratory Data Analysis (EDA):

Boxplots: Outliers in flight distance & delays

Histograms: Age distribution → mostly adults (20–50)

Count plots: More loyal customers & business travelers

Key Insights:

Seat comfort, inflight entertainment, online boarding & cleanliness drive satisfaction.

Flight delays reduce satisfaction significantly.

Business travelers are more satisfied than personal travelers.

 Best Model :– XGBoost

After testing multiple models (Logistic Regression, KNN, SVM, Decision Tree, Random Forest, Bagging, Boosting, ANN):

✅ XGBoost achieved the highest accuracy

Accuracy: ~96–97%
