# Level 1 - Task 2: Customer Segmentation Analysis

##  Project Objective
Apply clustering algorithms to segment an e-commerce company's customer base into distinct groups based on purchasing behaviour, enabling targeted marketing strategies.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** Pandas, NumPy, Scikit-learn (KMeans, StandardScaler), Matplotlib, Seaborn

---

## 📋 Key Steps & Feature Implementation

1. **Data Preprocessing & Cleaning:**
   - Handled missing values (e.g., CustomerID) and inconsistent records.
   - Cleaned negative/cancelled transactions and validated numerical columns.

2. **RFM Feature Engineering:**
   - **Recency (R):** Days since the customer's last purchase.
   - **Frequency (F):** Total number of transactions made.
   - **Monetary (M):** Total monetary spend by the customer.

3. **Data Scaling:**
   - Normalized and standardized RFM features using `StandardScaler` to ensure equal feature weighting for distance-based clustering.

4. **K-Means Clustering & Optimal K Selection:**
   - Used the **Elbow Method** (Inertia vs. Number of Clusters) to identify the optimal number of clusters ($K$).
   - Fitted the `KMeans` algorithm with optimal cluster centroids.

5. **Cluster Visualisation & Profiling:**
   - Visualized customer segments using 2D scatter plots across RFM feature combinations.
   - Calculated mean feature values for each segment to profile behavioral groups (e.g., High-Value/Champions, Loyal, At-Risk, Occasional).

---

## 💡 Business Recommendations & Targeted Actions
- **Champions / High-Value Customers:** Exclusive loyalty rewards, early access to new product drops, and personalized VIP service.
- **Loyal Customers:** Upselling/cross-selling recommendations and periodic engagement incentives.
- **At-Risk Customers:** Win-back email campaigns, targeted discounts, and feedback surveys.
- **Occasional / New Customers:** Welcome onboarding offers, free shipping thresholds, and product discovery guides.
-
