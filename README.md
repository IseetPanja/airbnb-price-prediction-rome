# Airbnb Price Prediction - Rome, Italy

This project applies supervised machine learning and sentiment analysis to predict Airbnb listing prices in Rome using structured data and guest reviews.

## Team Members
- AJ Payzant
- Iseet Panja
- Rohit Sarna

## Project Overview
We used Airbnb data from March 2025, integrating listing details, calendar pricing, and over 1.9 million reviews. Sentiment was extracted from guest reviews using Hugging Face’s multilingual BERT and XLM-Roberta.

### Key Steps:
- Data cleaning and preprocessing
- Feature engineering (e.g., host experience, review density)
- Sentiment analysis of guest reviews
- Training 9 ML models, including XGBoost, Random Forest, Stacking, and more
- Performance comparison with and without sentiment features

## Results
- **Best Model:** Stacking Regressor with sentiment
- **R² Score:** 0.869
- **RMSE:** 18.03
- **MAE:** 9.78

## Key Features
- Revenue per review
- Review-to-monthly ratio
- Sentiment scores (positive, neutral, negative)
- Occupancy rate and accommodation capacity

## Insights
- Sentiment features significantly improve price prediction.
- Hosts benefit from better reviews and higher occupancy.
- Airbnb could use sentiment in its smart pricing algorithm.

## Tools Used
- Python (pandas, scikit-learn, XGBoost)
- Hugging Face Transformers
- NLTK
- Jupyter Notebook

## Files
- `Group_5_Final_Report.pdf` – Detailed report of the project
- `Project_Group_5_AI_Milestone_2_Final.ipynb` – Full notebook with all code and model outputs

## Acknowledgments
- Inside Airbnb for the data
- UMass Amherst – AI & Machine Learning course