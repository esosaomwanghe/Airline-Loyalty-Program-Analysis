# Airline Loyalty Program Analysis (Group Project) 
### Evaluating the Effectiveness of Marketing Campaigns on Customer Engagement & Flight Bookings Across Canadian Demographics

---

### Project Objective
Analyze how marketing campaigns influence **loyalty program engagement** and **flight bookings** using real Canadian airline customer data (2018), with a focus on demographic segmentation (income, gender, province, education).

Deliver actionable insights to help airlines:
- Identify high-response customer segments
- Optimize marketing spend and personalization
- Increase loyalty program ROI and long-term retention

---

### Key Findings
| Insight | Details |
|-------|--------|
| Highest engagement provinces | Yukon, New Brunswick, Prince Edward Island |
| Top demographic responders | High-income females in Ontario & British Columbia |
| Strongest driver of engagement | Total Flights (r ≈ 0.90 with Engagement Score) |
| Income impact | Highly significant (ANOVA p < 0.001) |
| Gender impact | No significant difference overall (t-test p = 0.12) |
| Customer segments (K-Means) | 3 clear clusters: High-Value Flyers, Mid-Tier, Low-Engagement |

---

### Methodology & Tools
| Phase                  | Techniques & Tools                                      |
|-----------------------|----------------------------------------------------------|
| Data Cleaning         | Missing values, outliers, one-hot encoding               |
| Feature Engineering   | Created `Engagement_Score` = Points + (Flights × 100)    |
| EDA & Visualization   | Seaborn, Matplotlib, correlation heatmaps                |
| Predictive Modeling   | Logistic Regression, Decision Tree Regressor             |
| Clustering            | K-Means (k=3) on standardized features                  |
| Statistical Testing   | ANOVA (Income/Education), Independent t-test (Gender)   |
| Evaluation            | Confusion Matrix, ROC-AUC = 1.0, Accuracy ≈ 99.99%       |

**Libraries Used:** pandas, numpy, scikit-learn, matplotlib, seaborn, scipy, statsmodels

---

### Key Visualizations
- Customer Clusters (Total Flights vs Engagement Score)  
- Correlation Heatmap (Flights ↔ Engagement)  
- Engagement by Province & Gender (bar charts)  
- Decision Tree Structure (annotated)  
- Confusion Matrix & ROC Curve (Logistic Regression)  
- Engagement Distribution by Education Level

All included in the notebook and PDF report.

---

### Business Recommendations
1. **Target high-income customers** in Ontario, BC, and Atlantic Canada with premium offers  
2. **Reward flight frequency aggressively** — strongest predictor of engagement  
3. **Avoid gender-based targeting** — focus on behavior and income instead  
4. **Reactivation campaigns** for low-flight, low-income cluster  
5. **Deploy predictive models in CRM** for real-time personalized marketing  

---




[← Back to Main Portfolio](https://github.com/esosaomwanghe)

---
