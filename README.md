🎯 Customer Segmentation using K-Means Clustering
Project Overview
This project identifies distinct groups within a mall's customer base using Unsupervised Learning. By applying K-Means Clustering, we segment customers based on their annual income and spending behavior, providing actionable insights for targeted marketing.

🚀 Key Features
Data Preprocessing: Handled demographics and performed Feature Scaling for clustering accuracy.

Optimal Cluster Selection: * The Elbow Method: Analyzed WCSS to determine the optimal number of clusters.

Silhouette Analysis: Validated cluster separation with a high silhouette score.

Dimensionality Reduction: Used PCA (Principal Component Analysis) to visualize high-dimensional data in 2D/3D space.

Advanced Visualization: Created detailed scatter plots using Seaborn to map the 5 customer segments.

Centroid Mapping: Plotted cluster centers to represent the "ideal" customer profile for each segment.

📊 Dataset Description
The Mall_Customers.csv dataset includes:

Annual Income (k$): Yearly earnings of the customer.

Spending Score (1-100): Score assigned based on customer behavior.

Age & Gender: Demographic data for further profiling.

📈 Identified Segments
Target: High Income, High Spending.

Sensible: High Income, Low Spending.

Average: Medium Income, Medium Spending.

Careless: Low Income, High Spending.

Frugal: Low Income, Low Spending.

🛠️ Installation & Setup
Clone the repo:

Bash
git clone [https://github.com/AyeshaArshad-22/Customer-Segmentation-KMeans.git](https://github.com/AyeshaArshad-22/Customer-Segmentation-KMeans.git)
Install dependencies:

Bash
pip install -r requirements.txt
Run the Notebook:

Bash
jupyter notebook "Customer Segmentation.ipynb"
📂 Project Structure
Plaintext
├── Mall_Customers.csv          # Raw customer data
├── Customer Segmentation.ipynb  # Full ML pipeline
├── requirements.txt            # Library dependencies
└── LICENSE                     # MIT License
