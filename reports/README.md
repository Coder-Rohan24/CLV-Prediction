# Customer Lifetime Value (CLV) Prediction

## Project Overview
This project develops a comprehensive framework for predicting Customer Lifetime Value using historical transaction data. By leveraging RFM (Recency, Frequency, Monetary) analysis and machine learning techniques, I've created a system that accurately segments customers and forecasts their future value to the business.

## Key Insights

### Customer Segmentation
Using K-means clustering on RFM metrics, I identified three distinct customer segments:
- **High-Value Customers**: Frequent shoppers with recent purchases and high spending
- **Mid-Value Customers**: Moderate purchase frequency with average spending
- **Low-Value Customers**: Infrequent shoppers with longer periods between purchases

### Predictive Modeling
The XGBoost classifier achieved impressive results:
- 93% precision in identifying high-value customers
- Strong overall accuracy across customer segments
- Reliable predictions for future customer spending patterns

### Business Applications
This model enables:
- Targeted marketing campaigns tailored to specific customer segments
- More efficient resource allocation based on customer value
- Early identification of high-potential customers
- Data-driven customer retention strategies

## Methodology
1. Transaction data preprocessing and feature engineering
2. RFM metric calculation and customer segmentation
3. Temporal feature creation to capture purchasing patterns
4. Machine learning model development using XGBoost
5. Performance evaluation and business insight extraction

## Future Improvements
- Integration of additional customer data sources
- Enhanced feature engineering for improved model performance
- Development of more granular customer segments
- Implementation of time-series forecasting for dynamic CLV prediction

---

**Author**: Anirban Halder  
**Contact**: halder.anirban03@gmail.com