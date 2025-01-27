# Customer-Insights-and-Analysis
# Overview

This project performs comprehensive customer data analysis, segmentation, and modeling to extract valuable business insights. It consists of three primary tasks:

Exploratory Data Analysis (EDA): Insights into customer, product, and transaction data.

Lookalike Model: Recommends similar customers based on profiles and transaction history.

Customer Segmentation: Clustering customers based on profile and transaction behavior.

# Project Structure

The repository contains the following files and directories:

1. Data Files

Customers.csv: Contains customer profile information.

Fields: CustomerID, CustomerName, Region, SignupDate

Products.csv: Contains product details.

Fields: ProductID, ProductName, Category, Price

Transactions.csv: Contains transaction history.

Fields: TransactionID, CustomerID, ProductID, TransactionDate, Quantity, TotalValue, Price

2. Notebooks/Scripts

EDA_and_Business_Insights.ipynb: Contains code for Task 1 (EDA) and business insights generation.

Lookalike_Model.ipynb: Contains code for Task 2, implementing a recommendation model for similar customers.

Customer_Segmentation.ipynb: Contains code for Task 3, performing customer segmentation with clustering techniques.

3. Outputs

EDA_Report.pdf: A detailed report summarizing business insights from the EDA.

Lookalike.csv: A file containing customer lookalike recommendations and similarity scores for the first 20 customers.

Format: CustomerID, [List of Similar Customers with Scores]

Customer_Clusters.csv: Contains cluster labels for each customer after segmentation.

Format: CustomerID, Cluster

4. Additional Files

README.md: This file, describing the project, file structure, and instructions for use.

requirements.txt: Contains Python package dependencies required to run the project.

Getting Started

Setup Instructions

# Clone the repository:

git clone <repository_url>
cd <repository_name>

Install dependencies:

pip install -r requirements.txt

Ensure the data files (Customers.csv, Products.csv, Transactions.csv) are in the root directory.

Running the Scripts

# EDA and Business Insights

Open EDA_and_Business_Insights.ipynb in Jupyter Notebook.

Execute the cells step-by-step to perform EDA and generate business insights.

# Lookalike Model

Open Lookalike_Model.ipynb in Jupyter Notebook.

Execute the cells to train the lookalike model and generate Lookalike.csv.

# Customer Segmentation

Open Customer_Segmentation.ipynb in Jupyter Notebook.

Execute the cells to perform clustering and generate Customer_Clusters.csv.

# Project Highlights

EDA and Insights: Extract actionable insights on customer and product performance.

Lookalike Model: Recommends similar customers using profile and transaction data.

Customer Segmentation: Groups customers into clusters for targeted marketing strategies.

# Metrics:

Davies-Bouldin Index for cluster evaluation.

Similarity scores for lookalike recommendations.

Dependencies

# The project uses the following libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn
