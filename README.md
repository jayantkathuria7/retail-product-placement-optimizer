# 🛒 Retail Product Placement Optimizer

An end-to-end machine learning project to analyze retail transaction data, uncover customer segments, discover product affinities, and generate actionable in-store product placement strategies.

---

## 📌 Project Overview

**Goal:**  
Optimize product placement and boost retail sales by:

- Segmenting customers using RFM + clustering
- Identifying product co-purchase patterns using the Apriori algorithm
- Recommending shelf placements for cross-sell opportunities
- Delivering business-ready insights and visualizations

**Dataset:**  
[Online Retail Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/Online+Retail)

---

## 🔍 Features Implemented

| Module | Description |
|--------|-------------|
| 🧹 Data Cleaning | Removed cancelled transactions and negative values |
| 📊 EDA | Monthly sales trend, top-selling products, country-wise insights |
| 👥 Customer Segmentation | KMeans clustering on RFM scores + PCA visualization |
| 📦 Product Clustering | Co-occurrence matrix to group similar items |
| 🧠 Association Rules | Apriori algorithm with lift/confidence filtering |
| 🧾 Recommendations | Placement logic derived from clusters and rules |
| 📈 Visualizations | 10+ business visuals including heatmaps, pie charts, and lift distributions |
| 📤 Exports | CSVs ready for PowerBI / dashboard integration |

---

## 📁 Project Structure

- `retail-product-placement-optimizer/`
  - `notebooks/`
    - `Retail_Product_Optimizer.ipynb`  *(Jupyter notebook for analysis and model building)*
  - `outputs/`
    - `rfm_clustered.csv`  *(Customer segmentation results: RFM + clusters)*
    - `cleaned_transactions.csv`  *(Cleaned transaction data)*
    - `apriori_rules.csv`  *(Association rules from the Apriori algorithm)*
    - `plots/`  *(All charts and visualizations, e.g., sales trends, product affinities)*
  - `summary_report.md`  *(Business report summarizing insights and recommendations)*
  - `README.md`  *(Project documentation)*
  - `requirements.txt`  *(Python dependencies)*



---

## 💡 Key Insights

- **Best customers** spend frequently and recently (Cluster 2)
- **Nearly 50% of revenue** comes from low-frequency buyers (Cluster 0)
- **High lift rules** reveal strong product bundling opportunities
- **Placement strategy** can significantly boost cross-selling

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/retail-product-placement-optimizer.git
   cd retail-product-placement-optimizer
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   Open `Retail_Product_Optimizer.ipynb` in Jupyter and follow section by section.

---

## 🧠 Future Scope

* Add hierarchical or GMM-based customer segmentation
* Integrate with PowerBI or build a Streamlit dashboard
* Extend to product recommendation systems or time-series forecasting

---

## 📬 Contact

Built by **\[Jayant Kathuria]**
Reach out via [LinkedIn](https://www.linkedin.com/in/jayantkathuria7/) or [Email](jayantkathuria7@gmail.com)

---

> ⚠️ This project was developed as part of an ML Developer Intern assignment for DevifyX.
