# Big Mart Sales Prediction

This project involves predicting item outlet sales for Big Mart using machine learning techniques. The dataset includes various features related to items and outlets, and the aim is to develop a predictive model that can estimate the sales of items in different outlets.

## Installation

Python libraries installed:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- klib
  
## Dataset Information

- **Source**: https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data/download?datasetVersionNumber=1
- **Number of Rows**: 8523
- **Number of Columns**: 12
- **Features**: 
  - `item_weight`: Weight of the item.
  - `item_fat_content`: Fat content of the item (Low Fat, Regular).
  - `item_visibility`: The visibility of the item in the store.
  - `item_type`: Type of the item (e.g., Dairy, Snack Foods, etc.).
  - `item_mrp`: Maximum retail price of the item.
  - `outlet_establishment_year`: Year the outlet was established.
  - `outlet_size`: Size of the outlet (Small, Medium, High).
  - `outlet_location_type`: Type of location (Tier 1, Tier 2, Tier 3).
  - `outlet_type`: Type of outlet (Supermarket, Grocery Store, etc.).
- **Target Variable**: `item_outlet_sales` - Sales of the item in the outlet.
- **Data Format**: CSV
- **Missing Values**: Handled by imputation.
