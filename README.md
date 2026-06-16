#  Country Clustering using K-Means (International Aid Allocation)

##  Project Overview
This project applies *Unsupervised Machine Learning* using the *K-Means Clustering* algorithm to categorize countries based on various socio-economic and health factors (such as child mortality, income, and GDP). The goal is to identify the clusters of countries that are in the most dire need of financial aid and international development support.

---

##  Machine Learning Workflow
1. *Data Preprocessing:* Handled features and handled scaling using StandardScaler to normalize the data.
2. *Finding Optimal Clusters:* Applied the *Elbow Method* by plotting the Within-Cluster Sum of Squares (WCSS) to find the best $K$ value (Optimal $K = 3$).
3. *Model Training:* Trained the KMeans model with 3 clusters.
4. *Insights & Profiling:* Used Pandas groupby() to analyze the mean characteristics of each cluster and identified the targeted group.

---

##  Key Insights & Results
* *Cluster 0 (Developing/Emerging Countries):* Moderate income and stable development indicators.
* *Cluster 1 (Developed Countries):* High GDP, high net income, and exceptionally low child mortality rates.
* *Cluster 2 (Underdeveloped Countries - High Priority):* Very low GDP/Income and critical child mortality rates. These countries require immediate aid.

---

##  Tech Stack
* *Language:* Python
* *Libraries:* Pandas, NumPy, Scikit-Learn (KMeans, StandardScaler), Matplotlib
