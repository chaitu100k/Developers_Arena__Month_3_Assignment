# Developers_Arena__Month_3_Assignment
It includes Developers Arena Internship month 3 assignment files

## Overview
This repository contains all materials for Week 9 to Week 11 of the Advanced Data Science curriculum. It includes Hands-On exercises, Client Projects, datasets, scripts, and reports.

## Directory Structure
```
Week9_Advanced_Supervised_Learning/
├── HandsOn/
│   ├── week9_randomforest_xgboost.py
│   ├── customer_churn_sample.csv
│   ├── hands_on_report.pdf
│   └── README.md
├── ClientProject/
│   ├── week9_clientproject_churn_xgboost.py
│   ├── customer_churn_full.csv
│   ├── model_evaluation_report.pdf
│   └── README.md
└── Week9_Summary.pdf

Week10_Clustering_Unsupervised_Learning/
├── HandsOn/
│   ├── week10_kmeans_pca.py
│   ├── Retail_Customers_Sample.csv
│   ├── hands_on_report.pdf
│   └── README.md
├── ClientProject/
│   ├── week10_customer_segmentation.py
│   ├── Retail_Customers_Full.csv
│   ├── CustomerClusters.csv
│   ├── cluster_visualization.png
│   ├── model_evaluation_report.pdf
│   └── README.md
└── Week10_Summary.pdf

Week11_Deep_Learning/
├── HandsOn/
│   ├── week11_hands_on_nn.py
│   ├── hands_on_report.pdf
│   └── README.md
├── ClientProject/
│   ├── week11_mnist_classification.py
│   ├── mnist_model.h5 (generated after running script)
│   ├── client_project_report.pdf
│   └── README.md
└── Week11_Summary.pdf
```

## Setup Instructions
1. Clone this repository:
```bash
git clone <repository_url>
```

2. Navigate to each week folder and install requirements:
```bash
pip install -r requirements.txt
```

3. Run scripts as instructed in the respective README.md files for Hands-On and Client Projects.

## Week-wise Details

### Week 9 - Advanced Supervised Learning
- Hands-On: Random Forest vs XGBoost classification
- Client Project: Customer churn prediction using XGBoost
- Reports: Hands-On and Client Project reports in PDF

### Week 10 - Clustering and Unsupervised Learning
- Hands-On: K-Means clustering and PCA on sample dataset
- Client Project: Customer segmentation using full dataset (~7k rows)
- Reports and visualizations included

### Week 11 - Introduction to Deep Learning
- Hands-On: Simple feedforward neural network on synthetic data
- Client Project: MNIST image classification using Keras/TensorFlow
- Reports and model saved after training

## Notes
- All scripts are in Python 3
- Ensure all required packages are installed via `requirements.txt`
- For large datasets (Week 10 and 11), some scripts download or generate data as needed

## License
This repository is intended for educational purposes and internal use in the curriculum.

