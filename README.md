# Airbnb Analysis
- Looking at the analysis, we see that the 2 most popular room types are entire home and private room.
- Number of new construction was not affected by the pandemic or financial crisis if we look at the graph, around 5000 rooms were newly constructed each year.
- The most popular neighborhood by listing count is Bedford-Stuyvesant (over 8000).
- New Dorp and Chelsea, Staten Island are the most expensive one according to average price.
- Considering the number of reviews per month, 'Come catch a Broadway Show & stay in Times Square' ranked first.
- Chelsea in Manhatan is the neighborhood that received most reviews.

# Breast Cancer Analysis
- Best split ratio for each model
    - Decision Tree: Train size=95, Test size=5, Avg performance=0.96
    - Random Forest: Train size=75, Test size=25, Avg performance=0.97
    - XGBoost: Train size=80, Test size=20, Avg performance=0.99
    - SVC: Train size=75, Test size=25, Avg performance=0.96
    - KNN: Train size=60, Test size=40, Avg performance=0.96
    - Logistic Regression: Train size=60, Test size=40, Avg performance=0.97 

- Top 3 important features in each classification models
    - **Decision Tree**:
        - Feature 7     1.0
        - Feature 0     0.0
        - Feature 16    0.0
    - **Random Forest**:
        - Feature 7     0.176556
        - Feature 22    0.144181
        - Feature 27    0.130188
    - **XGBoost**:
        - Feature 7     0.889295
        - Feature 27    0.110705
        - Feature 0     0.000000
