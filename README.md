# Big-Data-Optimal-Discount-Timing-Optimization-for-Adidas-Retail-Products
Big Data Analytics project developed at Tunis Business School (2025/2026).

## Objective
Build an end-to-end big data pipeline to simulate, clean, transform and analyze Adidas retail data, and apply machine learning models to determine the optimal discount level and the optimal timing for promotional campaigns.

## Architecture
Synthetic Data → Ingestion → Cleaning → Feature Engineering → ML (ElasticNet & Random Forest) → Dashboards (4 Key Visualizations)

## Technologies Used
- Python (NumPy, Pandas, Matplotlib)
- Apache Spark (PySpark)
- Spark SQL
- Spark MLlib (ElasticNet, Random Forest)
- Local Parquet Storage
- Google Colab / VS Code

## Dataset
- Type: Synthetic Adidas-like retail dataset  
- Period: 1990–2024 (daily data)
- Variables: prices, discounts, liquidity, turnover, category, channel, demand, revenue
- Storage format: Parquet (local filesystem)

## Repository Structure
- `00_generate_synthetic_data.py` → Generate synthetic dataset  
- `10_ingest_clean_to_curated_local.py` → Ingestion & cleaning  
- `20_feature_engineering_to_features_local.py` → Lag features & moving averages  
- `30_train_models_local.py` → Pricing & timing ML models  
- `40_visualize_dashboards.py` → Final dashboards  
- `data/` → CSV + curated Parquet + features  
- `models/` → Saved ML models  
- `outputs/` → Figures (PNG)

## Authors
- **Adem Mani**  
- **Achref Chbichib**

## Academic Supervisor
- **Manel Abdelkader**
