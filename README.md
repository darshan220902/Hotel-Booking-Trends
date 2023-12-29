# Project Overview:
The project aimed to perform comprehensive data analysis and implement machine learning models to understand and potentially reduce hotel booking cancellations. The project followed a structured approach, starting with data preprocessing, exploratory data analysis (EDA), and concluding with the application of machine learning models.

## I. Data Processing
Import Libraries:

Pandas, NumPy, Matplotlib, Seaborn for data manipulation and visualization.
Scikit-learn for machine learning models.
Data Processing:

Converted object data types to category data types.
Addressed missing values and outliers.

## II. Exploratory Data Analysis (EDA)
Cancellation Counts: Plotted a count plot comparing canceled and not-canceled bookings.
Observed instances where cancellations were less than non-cancellations.
Hotel Type vs Cancellation:

Examined cancellation rates for different hotel types.
Discovered that city hotels had a higher cancellation rate compared to resort hotels.
Monthly Cancellation Trends:

Plotted cancellation and non-cancellation counts vs. months.
Identified that January exhibited a higher cancellation rate, while August had a higher non-cancellation rate.
Country-wise Cancellation Rate:

Utilized a pie plot to visualize the top 10 countries with the highest cancellation rates.
Noted that PRT (Portugal) had the highest cancellation rate at 70.1%.
Cancellation and ADR (Average Daily Rate) Analysis:

Investigated the relationship between cancellation status and the sum of ADR.
Discovered that high cancellation rates in January were associated with higher prices.

## III. Machine Learning
### Feature Selection:

Selected relevant features for model training, including hotel type, reservation status, etc.
Models Used:Logistic Regression, Decision Tree, Random Forest.

Model Evaluation:

Logistic Regression:
Accuracy: 98.94%,
Precision: 99.79%,
Recall: 97.39%,
F1 Score: 98.58%,

Decision Tree:
Accuracy: 100%,
Precision: 100%,
Recall: 100%,
F1 Score: 100%,

Random Forest:
Accuracy: 99.99%,
Precision: 100%,
Recall: 99.99%,
F1 Score: 99.99%,

## IV. Conclusion and Recommendations

### Key Findings:

City hotels have a higher cancellation rate than resort hotels.
January exhibits a higher cancellation rate, correlated with higher prices.
Portugal (PRT) has the highest country-wise cancellation rate.

Recommendations:
Implement targeted strategies during high cancellation months.
Explore pricing strategies, especially during peak cancellation periods.
Consider region-specific initiatives to address cancellation patterns.

