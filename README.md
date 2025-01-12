# Strategic Customer Segmentation and Demand Prediction

- This project leverages machine learning techniques for customer segmentation and demand prediction in the retail domain.
- By analyzing historical sales data, we categorize customers into meaningful segments and predict daily and weekly demand trends.
- The insights are aimed at optimizing inventory management, pricing strategies, and personalized marketing campaigns.

---

## 📚 Project Overview

- **Customer Segmentation**: Implemented k-means and hierarchical clustering to group customers based on purchasing behaviors and profitability.
- **Demand Prediction**: Utilized XGBoost regression to forecast daily and weekly sales, employing time series cross-validation for model evaluation.
- **Dataset**: Historical retail sales data with over 51,000 records and 24 fields, containing information about orders, customers, and products.

---

## 🔑 Key Features

1. **Customer Segmentation**:
   - Segments identified:
     1. Stable Performers
     2. High Achievers
     3. Challenged Margins
     4. Balanced Growth
   - Methodology:
     - K-means clustering with elbow method for optimal cluster count.
     - Hierarchical clustering to validate k-means results.
   - Insights:
     - High Achievers generate the highest sales but may require strategic targeting for profitability.

2. **Demand Prediction**:
   - **Daily Demand**: Predicted using XGBoost with features like sales, profit, shipping cost, and order priority.
   - **Weekly Demand**: Aggregated predictions using key metrics such as quantity and profit.
   - **Performance Metrics**: Evaluated with MAPE and RMSPE.

---

## 📊 Tools and Technologies

- **Programming Language**: Python
- **Libraries**:
  - Machine Learning: `scikit-learn`, `xgboost`
  - Visualization: `matplotlib`, `seaborn`
  - Data Manipulation: `pandas`, `numpy`
- **Other Tools**: Jupyter Notebook

---

## 📂 Repository Structure

```plaintext
├── data/                        # Placeholder for the dataset
├── notebooks/
│   ├── Segmentation_and_sales_prediction.ipynb  # Jupyter notebook with EDA, clustering, and predictions
├── reports/
│   ├── Strategic Customer Segmentation and Demand Prediction.pdf  # Full project report
├── scripts/                     # Placeholder for reusable Python scripts
├── README.md                    # Project documentation
```

---

## 🚀 How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Notebook**:
   Open `Segmentation_and_sales_prediction.ipynb` in Jupyter Notebook or JupyterLab.

---

## 📈 Results

1. **Customer Segmentation**:
   - Optimal clusters: 4 (using elbow method).
   - Higher silhouette score observed with hierarchical clustering, but k-means was retained for scalability.

2. **Demand Prediction**:
   - **Daily**: Best performance with MAPE = 22.04 and RMSPE = 28.66 for one segment.
   - **Weekly**: Improved accuracy compared to daily, suggesting better performance with aggregated predictions.

---

## 🛠 Future Enhancements

- Explore additional clustering techniques (e.g., DBSCAN, Gaussian Mixture Models).
- Incorporate advanced feature engineering for better demand prediction.
- Expand dataset to include customer demographics for richer insights.
