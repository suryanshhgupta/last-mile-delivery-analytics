Last-Mile Delivery Analytics and Route Optimization

Project Overview:

This project analyzes e-commerce delivery performance using Python and the Brazilian E-Commerce Public Dataset by Olist. The goal is to identify delivery delays, understand logistics costs, explore geographic patterns, and demonstrate how data analytics can support better logistics planning.

Objectives:

- Analyze order and delivery performance.
- Calculate key logistics KPIs.
- Identify states with higher late-delivery rates.
- Compare freight costs for late and on-time orders.
- Build an exploratory machine learning model for late-delivery classification.
- Explore geographic clustering and demonstrate vehicle route optimization.

Tools and Technologies:

- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Google OR-Tools
- Google Colab

Key Findings:

- Orders analyzed: 96,470
- Late-delivery rate: 8.11%
- Average delivery lead time: 12.09 days
- Average freight cost: R$22.79 per order
- Baseline model F1-score: 16.31%
- Model with customer-state feature F1-score: 20.02%
- Geographic clustering silhouette score: 0.731
- Illustrative two-vehicle route distance: 30.61 units

Visualizations:

The project includes charts for:

1. Monthly late-delivery rate.
2. Late-delivery rate by customer state.
3. Average freight cost for late versus on-time orders.

Methodology:

1. Data cleaning and preparation.
2. Exploratory data analysis and KPI calculation.
3. Customer-state and freight-cost analysis.
4. Feature engineering and baseline classification.
5. Geographic clustering using K-Means.
6. Illustrative vehicle routing optimization using Google OR-Tools.

Limitations:

The machine learning models are exploratory and are not production-ready. Their precision and F1-scores indicate that further improvement and validation are required. The route optimization example uses illustrative coordinates and Euclidean distances, not actual road distances or live traffic. The clustering results also require further validation before operational use.

Dataset:

Brazilian E-Commerce Public Dataset by Olist:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

Future Improvements:

- Improve model performance and evaluate precision-recall trade-offs.
- Validate geographic clusters using demand and realistic distance measures.
- Incorporate actual road distances, vehicle capacities, and delivery time windows.
- Develop an interactive logistics dashboard.
