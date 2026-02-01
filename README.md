# Credit Card Customer Behavior Segmentation & Analysis

Customer segmentation using 6-month credit card usage features (Data Cleaning and Processing → EDA → PCA → K-Means → Cluster Profiling) to derive actionable customer groups.

## Skills (Techniques Applied)
- Data cleaning & validation (missing values, duplicates, consistency checks)
- EDA: distribution analysis, skew/outliers, log1p visualization
- Correlation: Spearman vs Pearson; feature-family redundancy
- Scaling: StandardScaler / RobustScaler
- PCA: variance explained + 2D/3D projections
- Clustering: K-Means (`random_state`, `n_init`)
- Evaluation: inertia, silhouette score
- Cluster profiling: mean/median + **z-delta** (standardized difference vs overall)
- Insight delivery: segment personas and recommendations

## Goals
- Segment customers based on behavioral patterns.
- Identify key drivers that differentiate each segment.
- Deliver business-readable personas for targeting and strategy.

## Workflow
1. Data cleaning and basic checks  
2. Distribution analysis (skew, outliers; log-scale views)  
3. Correlation analysis (Spearman heatmap + top pairs)  
4. PCA (variance explained, 2D/3D visualization)  
5. K-Means clustering (K=4)  
6. Cluster evaluation (inertia, silhouette)  
7. Cluster profiling (z-delta heatmap + per-cluster drivers)  
8. Segment personas + actionable insights  
