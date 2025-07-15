Feature Impact Analysis: Turning Data into Product Insights

This project explores how a newly launched product feature influenced user revenue — using Python for data processing and Tableau for clear, actionable visual insights.

Why This Project?

A product was shipped. The team wanted answers:
- Who actually used the feature?
- Did it change user behavior or revenue?
- Which segments responded the most?

This project bridges that gap — blending product curiosity with analytical rigor.

🛠️ Tools Used

Python (Pandas) – Data wrangling & feature engineering  
Google Colab – Code environment  
Tableau – Insightful, interactive dashboards  
CSV files – Realistic mock datasets for users & usage  

---

📁 Dataset

Two CSVs:
1. `expanded_feature_users_dataset.csv` – User info, signup date, plan type, revenue before/after
2. `expanded_feature_usage_dataset.csv` – User IDs and when they used the feature

---
What I Did

- Flagged which users adopted the feature (`used_feature`)
- Calculated revenue growth: `revenue_after - revenue_before`
- Merged everything into one clean dataset
- Built a dashboard to tell the story visually

➡️ Final file used: `final_users_with_used_feature.csv`  
📊 Dashboard: `feature_impact_dashboard.twbx`


💡 Key Takeaways

- Feature adopters saw clear revenue lifts
- Premium plan users adopted more — strong upsell signal
- Newer users were more likely to try the feature

🎯 Why It Matters

From a product lens:
- Quantifies the value of a feature launch
- Reveals which segments to double down on
- Supports smarter rollout and targeting

From a data lens:
- Clean ETL pipeline in Python  
- Effective use of Tableau for insight delivery  
- Tells a story that drives decisions  

