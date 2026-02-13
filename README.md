🛍️ Customer Segmentation using K-Means Clustering
📌 Project Overview
The goal of this project is to divide shopping mall customers into different groups (clusters) based on their Annual Income and Spending Score. This helps the business develop tailored marketing strategies for each customer segment.

🛠️ Tech Stack
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

ML Algorithm: K-Means Clustering

Preprocessing: StandardScaler

📊 Exploratory Data Analysis (EDA)
During the analysis, we observed the following:

Age Factor: Customers aged 18–35 have the highest spending scores, while individuals aged 36–55 tend to have the highest annual incomes.

Correlation: No strong correlation was found between Income and Age, indicating that wealth and spending habits are not strictly tied to age.

![Confusion Matrix](download%20(4).png)



⚙️ Methodology
Feature Selection: We selected 'Annual Income' and 'Spending Score' for clustering.

Feature Scaling: StandardScaler was applied to ensure both features contributed equally to the model.

Elbow Method: To determine the optimal number of clusters, we plotted WCSS (Inertia) and found that k = 5 is the best choice.
