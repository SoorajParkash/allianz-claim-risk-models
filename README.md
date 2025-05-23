![image](https://github.com/user-attachments/assets/958b0c48-3698-4b0b-8974-25c2b20d4030)# allianz-claim-risk-models
Machine learning solutions for Allianz Benelux SA: customer segmentation using K-Means and PCA; predictive modeling with supervised learning, feature engineering, data preprocessing, model evaluation, and visualization.
# Allianz Insurance Analytics: Customer Segmentation & Predictive Modeling

Welcome to the Allianz Insurance Analytics repository—a showcase of advanced machine learning applications in the insurance industry. This project was developed as a case study for Allianz Benelux SA and demonstrates how data-driven approaches can unlock actionable insights for risk management, customer segmentation, and operational excellence.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Business Value](#business-value)
- [Methodology](#methodology)
- [Key Results & Visualizations](#key-results--visualizations)
- [How to Use](#how-to-use)
- [Intended Audience](#intended-audience)
- [Contact](#contact)

---

## Project Overview

Insurers today face intense competition and rapidly evolving risks. Making sense of vast customer and claim data is essential to optimize profitability, enhance customer satisfaction, and maintain regulatory compliance.  
This repository brings together two robust machine learning solutions:

1. **Customer Segmentation (Clustering Model):**  
   Unsupervised learning is used to divide insurance customers into distinct segments based on claim behavior and risk attributes. These segments empower the business to personalize products, target interventions, and refine pricing strategies.

2. **Predictive Modeling (Supervised Learning):**  
   Supervised machine learning algorithms predict the risk associated with incoming claims at an individual level. This enables Allianz to proactively identify high-risk cases, improve underwriting, and reduce losses through timely interventions.

---

## Business Value

By combining customer segmentation with predictive modeling, Allianz can:
- **Optimize Pricing:** Price products more competitively by understanding the true risk profile of each segment.
- **Target Retention Strategies:** Focus retention efforts on profitable and at-risk customer groups.
- **Enhance Risk Management:** Flag and investigate high-risk claims early, reducing losses and improving claims management efficiency.
- **Improve Operational Decision-Making:** Use actionable analytics to inform business strategy and resource allocation.

---

## Methodology

### Customer Segmentation (Clustering Model)
- **Data Preprocessing:** Addressed missing values, encoded categorical variables, and standardized features.
- **Feature Selection:** Used correlation analysis to drop redundant variables and retain the most informative predictors.
- **Dimensionality Reduction:** Employed Principal Component Analysis (PCA) for visualization and to capture key variance in the data.
- **K-Means Clustering:** Segmented customers into groups with similar claim and financial behavior.
- **Cluster Evaluation:** Utilized silhouette scores and visual inspection to assess clustering quality.
- **Cluster Profiling:** Analyzed financial and risk characteristics of each segment to guide business strategy.

---

## Key Results & Visualizations

Here are the principal findings and insights from the clustering model, with each visual accompanied by a clear business interpretation.

---

### 1. Customer Segmentation Visualization

![Customer Segmentation (PCA + KMeans Clustering)](https://github.com/SoorajParkash/allianz-claim-risk-models/blob/main/download%20(1).png?raw=true)

*This scatter plot shows customer groups identified by K-Means clustering in two principal components derived from PCA. Each color-coded cluster represents customers with similar claim behavior and risk characteristics, enabling targeted business actions.*

---

### 2. Cluster Profile Summary Table

![Cluster Profiles Table](https://github.com/SoorajParkash/allianz-claim-risk-models/blob/main/Table%20(1).png?raw=true)

*This table summarizes each cluster's size, average claim duration, average annuity, and mean payout per claim. These metrics allow Allianz to compare segments, assess profitability, and tailor product offerings.*

---

### 3. Claim Duration by Cluster

![Claim Duration Distribution by Cluster](https://github.com/SoorajParkash/allianz-claim-risk-models/blob/main/Claim_Duration_By_Cluster_Colored.png?raw=true)

*Boxplot analysis reveals the distribution of claim durations for each cluster. Significant differences between clusters indicate that claim duration is a key differentiator for risk profiling.*

---

### 4. Annuity vs. Duration by Cluster

![Annuity vs. Duration by Cluster](https://github.com/SoorajParkash/allianz-claim-risk-models/blob/main/Annuity_vs_Duration_by_Cluster_with_Centroids%20(1).png?raw=true)

*This scatter plot maps annual annuity against claim duration for each customer, colored by cluster, with cluster centroids highlighted. It uncovers the financial and risk dynamics of each group, supporting targeted risk and pricing strategies.*

---

### 5. Cluster Risk Profile: Mean Duration and Annuity

![Cluster Risk Profile](https://github.com/SoorajParkash/allianz-claim-risk-models/blob/main/Cluster_Risk_Profile_Dual_Axis_OneLegend.png?raw=true)

*The dual-axis bar chart compares the average claim duration and mean annuity of each cluster. This comprehensive risk profile helps Allianz to understand the trade-offs between risk (duration) and revenue (annuity) across segments.*

---

### 6. Mean Payout per Claim by Cluster

![Mean Payout per Claim by Cluster](https://github.com/SoorajParkash/allianz-claim-risk-models/blob/main/Cluster_Mean_Payout_per_Claim_Dynamic.png?raw=true)

*Bar chart showing the average payout per claim for each cluster. This visualization makes it easy to spot which segments drive the most claim costs, helping to focus loss mitigation efforts.*

---

## How to Use

To reproduce or build upon this analysis:

1. **Clone the repository and install dependencies:**
   ```bash
   git clone https://github.com/yourusername/allianz-insurance-analytics.git
   cd allianz-insurance-analytics
   pip install pandas numpy scikit-learn matplotlib seaborn
