# Student-Performance-Clustering

##  Project Overview
This project leverages machine learning (Unsupervised Learning) to analyze student behavior using the **xAPI-Edu-Data** dataset. The goal is to identify distinct student segments based on their engagement and academic performance to provide actionable recommendations for educators.

##  Technologies Used
- **Python**: Core language.
- **Pandas**: Data manipulation.
- **Seaborn & Matplotlib**: Data visualization.
- **Scikit-Learn**:
    - Data Preprocessing (StandardScaler, One-Hot Encoding).
    - Dimensionality Reduction (PCA).
    - Clustering (K-Means & Hierarchical Clustering).

##  Key Findings (Clusters Identified)
Using K-Means clustering (k=3), we identified three distinct student profiles:

| Cluster | Profile Name | Characteristics | Recommendation |
| :--- | :--- | :--- | :--- |
| **0** | **Moderately Engaged** | Average participation, high parental satisfaction. | Needs challenging projects to boost potential. |
| **1** | **High-Achievers** | High participation, low absence, strong performance. | Assign leadership roles and mentorship opportunities. |
| **2** | **At-Risk Students** | Low engagement, high absence, low parental involvement. | Requires immediate individualized support & parental outreach. |
