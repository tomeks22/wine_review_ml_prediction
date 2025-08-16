# wine_review_ml_prediction
Prediction if wine would get high review (>=4.5/5)

This is my first project, which is intended to demonstrate some of what I am currently learning. It is a simple project, the purpose of which is to predict whether a given wine will receive a high rating based on available data, which I have previously cleaned and prepared.

Project Pipeline
1. Load and clean data (remove missing values, process categorical columns)  
2. Create new features (`wine_age`, `winery_top10`)  
3. Balance target classes (`high_rating`) using undersampling  
4. One-hot encode categorical features  
5. Scale numerical features (`StandardScaler`)  
6. Split data into training and testing sets (80/20)  
7. Train Logistic Regression model  
8. Evaluate model (`accuracy`, `classification_report`)


Results
Test set accuracy:0.82 
The model performs reasonably well at predicting high-rated wines
