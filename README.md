# Customer-segmentation-ml

##An unsupervised learning project that groups data points into clusters based on feature similarity.


## Project Overview:
Customer segmentation is a critical task for businesses to understand different types of customers and design targeted strategies.
In many real-world scenarios, customer labels are not available, making unsupervised learning the appropriate approach.
This project applies clustering techniques to segment customers based on their demographic and behavioral attributes, enabling meaningful business insights without relying on predefined labels.

##Objectives:
Build a real-world applicable customer segmentation system;
Explore customer behavior using Exploratory Data Analysis (EDA);
Apply and compare multiple unsupervised clustering algorithms;
Interpret clusters in a business-oriented manner;

##Dataset Description:
The dataset is synthetically generated to simulate realistic e-commerce customer behavior,
A fixed random seed ensures reproducibility,
No labels are used for training, maintaining the unsupervised nature of the project,

| Feature                   | Description                                  |
| ------------------------- | -------------------------------------------- |
| Age                       | Customer age                                 |
| Gender                    | Male / Female                                |
| Annual_Income             | Annual income of the customer                |
| Spending_Score            | Score (1–100) representing spending behavior |
| Purchase_Frequency        | Average number of purchases per month        |
| Average_Transaction_Value | Average spend per transaction                |
| Membership_Level          | Basic / Silver / Gold / Platinum             |
(identifiers such as CustomerID and Name are excluded from modeling)

Customer-Segmentation/
│
├── data/
│   └── customer_segmentation_data.csv
│
├── notebooks/
│   ├── 01_data_generation.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_preprocessing.ipynb
│   ├── 04_kmeans_clustering.ipynb
│   ├── 05_hierarchical_clustering.ipynb
│
├── README.md
└── requirements.txt

Key Takeaways:
Successfully implemented end-to-end unsupervised learning workflow;
Compared multiple clustering algorithms;
Translated model output into meaningful business insights;
Built a reusable foundation for future extensions;

Future Work:
Refactor the project using scikit-learn Pipelines for end-to-end inference;
Apply clustering to new incoming customer data;
Extend the project with supervised learning (e.g., churn prediction)
