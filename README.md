**Customer LTV Prediction**

Predict customer lifetime value using purchase history to identify high-value customers.

**Features:**
- RFM (Recency, Frequency, Monetary) analysis
- XGBoost prediction model
- Customer segmentation (High/Medium/Low LTV)
- Visualizations of key insights

**Quick Start:**
1. Install: `pip install pandas xgboost matplotlib`
2. Run: `python ltv_prediction.py`
3. Input: CSV with columns: `customer_name, purchase_date, amount`

**Files:**
- `ltv_prediction.py` - Main prediction script
- `Retail_transaction_dataset.csv` - Example transaction data
- `results/` - Outputs predictions and charts

**Results:**
- Predicts future customer value
- Segments customers by value
- Shows most important factors

