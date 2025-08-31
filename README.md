# patient_visits_pred
🧠 Patient Clustering Report (Age ≤ 50)

This project performs clustering analysis on patient records using KMeans and generates a visual PDF report for patients aged 50 years and below.

📊 Features Used for Clustering:

Total Paid Amount

Average Paid Amount

Visit Count

Number of Unique ICD10 Codes

Average Age

Gender (encoded)

🧾 What It Does

Connects to a PostgreSQL database to read patient records

Filters patients aged ≤ 50

Preprocesses and aggregates visit data per patient

Applies KMeans clustering with automatic k selection via silhouette score

Generates visualizations (PCA, boxplots)

Saves a well-formatted PDF report in the reports/ folder

📁 Output Files

All outputs are saved in the reports/ folder:

clustering_report.pdf – Final report

pca_plot.png – PCA-based cluster visualization

boxplot_*.png – Cluster-wise feature distributions