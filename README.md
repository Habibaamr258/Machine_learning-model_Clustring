1️⃣ Data Cleaning & Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling

Removing unnecessary or non-informative columns

The data cleaning and preprocessing steps are performed once and reused across all clustering models to ensure consistency.

2️⃣ Feature Preparation

The cleaned and scaled dataset is stored in a single feature matrix.

This unified feature matrix is used as the input for all clustering techniques.

3️ K-Means Clustering

Applied to segment the data into a predefined number of clusters.

Used to identify general customer group patterns.

Cluster labels are generated for further analysis and comparison.

4️⃣ DBSCAN Clustering

Applied using the same preprocessed data (no re-cleaning or re-scaling).

Used to detect dense regions in the data and identify noise/outliers.

Provides an alternative clustering approach compared to K-Means.

5️⃣ Dimensionality Reduction with PCA

PCA (95% variance) is used to reduce dimensionality while preserving most of the information, supporting clustering performance.

PCA (2D) is used for visualization purposes to display clusters in two dimensions.

6️⃣ Visualization & Analysis

Visual representation of clusters using 2D PCA.

Comparison between K-Means and DBSCAN clustering results.

Analysis of cluster distribution and behavio
