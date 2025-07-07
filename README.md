# Insurance-Product-Recommendation-Engine

This project builds a recommendation system that suggests suitable insurance products to customers based on their demographics, policy history, and predicted behavior.

### Features
- Predicts customer response using LightGBM Classifier
- Estimates Customer Lifetime Value (CLV) using LightGBM Regressor
- Ranks customers by recommendation score (probability × CLV gap)
- Generates simple natural-language explanations

### Tools Used
- Python (Google Colab)
- pandas, scikit-learn, LightGBM
- Matplotlib, Plotly (optional)

### Output
The system outputs a ranked list of customers with:
- Recommendation score
- CLV prediction
- Purchase probability
- Personalized explanation

### Data
Used a vehicle insurance dataset (AutoInsurance) with customer details, policy types, and lifetime value information.


