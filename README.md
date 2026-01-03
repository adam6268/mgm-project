Enterprise-Wide Customer Lifetime Value (LTV) Optimization
📧 Project Overview
This project redefines enterprise marketing strategy for a North American resort portfolio by creating actionable customer segments and predicting Net Profit LTV. By moving beyond traditional demographics and into behavioral machine learning, this model informs personalized offer campaigns to maximize resort-wide profitability.
________________________________________
🛠️ Technical Stack
•	Language: Python
•	Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
•	Models: K-Means Clustering, Random Forest Regressor
•	Techniques: RFM Analysis, Feature Engineering, A/B Test Simulation
________________________________________
📊 Methodology
1. Segmentation & Feature Engineering
Using a dataset of 3,590 active customers, I developed a K-Means clustering model (K=4). The features were engineered to capture "Value Velocity" rather than just static snapshots:
•	RFM: Recency, Frequency, and Monetary values.
•	Avg. Visit Velocity: Rate of return to the property.
•	Gaming Affinity: Behavioral preference metrics for specific resort amenities.
2. Predictive Modeling
To move from historical data to future projections, I built a Random Forest Regressor to predict Net Profit LTV.
•	Performance: Achieved an $R^2$ of 0.9430.
•	Key Insight: Customer Frequency was identified as the primary driver (78% feature importance), suggesting that reducing the "visit gap" is more profitable than increasing spend per visit.
________________________________________
💰 Business Impact & ROI Simulation
The core of this project is a segment-specific simulation designed to optimize marketing incentive spend.
Segment	Strategy	Offer Cost	Projected ROI	Net Gain / Cust
Cluster 2 (Whales)	Retention	$750	+2,482%	+$18,612
Cluster 3 (Seasonal)	Reactivation	$125	+3,330%	+$4,162
________________________________________
🚀 Key Findings
•	Personalization over Mass Marketing: Targeted spending on high-affinity segments yielded 10x the efficiency of legacy broad-spend strategies.
•	Actionable Narrative: Translated complex model outputs into an executive-ready strategy for resort-wide deployment.

