Machine learning solutions for Allianz Benelux SA: customer segmentation using K-Means and PCA; predictive modeling with supervised learning, feature engineering, data preprocessing, model evaluation, and visualization.

# Allianz Insurance Analytics: Customer Segmentation & Predictive Modeling

Welcome to the Allianz Insurance Analytics repository—a showcase of advanced machine learning applications in the insurance industry. Developed as a case study for Allianz Benelux SA, this project demonstrates how data-driven techniques can deliver actionable insights for risk management, customer segmentation, and claim risk prediction.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Model 1: Customer Segmentation (Clustering)](#model-1-customer-segmentation-clustering)
- [Model 2: Predictive Modeling (Supervised Learning)](#model-2-predictive-modeling-supervised-learning)
- [How to Use](#how-to-use)
- [Intended Audience](#intended-audience)
- [Contact](#contact)

---

## Project Overview

The insurance industry faces unprecedented competition and complex risks. Harnessing data science allows insurers like Allianz Benelux SA to:

- Optimize pricing and product design
- Enhance customer targeting and retention
- Flag high-risk claims early for proactive management
- Make informed, strategic decisions based on actionable analytics

This repository brings together two robust machine learning solutions:

---

## Model 1: Customer Segmentation (Clustering)

### Objective
Segment insurance customers into distinct groups based on risk and claim characteristics, enabling tailored business strategies and optimized resource allocation.

### Techniques Used
- Data preprocessing: Handling missing values, encoding, scaling
- Correlation-based feature selection
- Dimensionality reduction with PCA
- K-Means clustering
- Cluster evaluation with silhouette score
- Cluster profiling for actionable business insights

### Key Results & Visualizations

#### 1. Customer Segmentation Visualization

![Customer Segmentation (PCA + KMeans Clustering)](https://github.com/SoorajParkash/allianz-claim-risk-models/blob/main/download%20(1).png?raw=true)
*Scatter plot of customer clusters in PCA-reduced space, showing distinct groups for targeted action.*

#### 2. Cluster Profile Summary Table

![Cluster Profiles Table](https://github.com/SoorajParkash/allianz-claim-risk-models/blob/main/Table%20(1).png?raw=true)
*Table comparing segment size, mean claim duration, annuity, and payout—essential for business strategy.*

#### 3. Claim Duration by Cluster

![Claim Duration Distribution by Cluster](https://github.com/SoorajParkash/allianz-claim-risk-models/blob/main/Claim_Duration_By_Cluster_Colored.png?raw=true)
*Boxplot analysis of claim durations across segments, revealing risk differences.*

#### 4. Annuity vs. Duration by Cluster

![Annuity vs. Duration by Cluster](https://github.com/SoorajParkash/allianz-claim-risk-models/blob/main/Annuity_vs_Duration_by_Cluster_with_Centroids%20(1).png?raw=true)
*Scatter plot mapping annuity against claim duration, colored by cluster with centroids highlighted.*

#### 5. Cluster Risk Profile: Mean Duration and Annuity

![Cluster Risk Profile](https://github.com/SoorajParkash/allianz-claim-risk-models/blob/main/Cluster_Risk_Profile_Dual_Axis_OneLegend.png?raw=true)
*Bar chart for average claim duration and annuity by segment.*

#### 6. Mean Payout per Claim by Cluster

![Mean Payout per Claim by Cluster](https://github.com/SoorajParkash/allianz-claim-risk-models/blob/main/Cluster_Mean_Payout_per_Claim_Dynamic.png?raw=true)
*Mean payout per claim by cluster, highlighting which segments drive costs.*

---

## Model 2: Predictive Modeling (Supervised Learning)

### Objective
Predict insurance claim risk at the individual level, empowering Allianz to proactively identify and manage high-risk claims.

### Techniques Used
- Data preprocessing and feature engineering
- Model selection (Logistic Regression, Random Forest, etc.)
- Hyperparameter tuning
- Model evaluation (accuracy, F1-score, confusion matrix)
- Visualization of results and feature importance

### (Add Visuals Here)
> _Add confusion matrix, ROC curve, or feature importance plots for your predictive model as you complete them, following the same style as above._

---

## How to Use

1. **Clone the repository and install dependencies:**
   ```bash
   git clone https://github.com/yourusername/allianz-insurance-analytics.git
   cd allianz-insurance-analytics
   pip install pandas numpy scikit-learn matplotlib seaborn

