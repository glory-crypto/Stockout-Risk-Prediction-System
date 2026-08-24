# Stockout-Risk-Prediction-System

# *Overview*

The Stockout Risk Prediction System is a machine learning project designed to predict the risk of inventory stockouts for retail stores.

The system analyzes historical sales, inventory, supplier, demand, product, store, and event-related data to classify products into three stockout-risk categories:

Safe
Imminent
At-Risk

The objective is to help businesses identify potential stock shortages early and make better inventory replenishment decisions.

# *Problem Statement*

Retail businesses can face stockouts due to unexpected demand, insufficient inventory, supplier delays, seasonal events, and inaccurate demand estimation.

Traditional inventory monitoring systems often identify stockout problems only after inventory levels become critical. This project uses machine learning to predict stockout risk in advance.

# *Objectives*
Predict stockout risk for individual inventory records.
Identify products that require immediate attention.
Analyze factors influencing stockout risk.
Support proactive inventory management.
Reduce potential revenue loss caused by stockouts.

# *Dataset*

The dataset contains information related to:

Store and SKU details
Opening and closing stock
Units demanded and sold
Reorder points
Reorder status
Expected and actual supplier lead time
Sales velocity
Days of inventory cover
Supplier reliability
Product category and price
Store size and tier
Seasonal and festival information
Demand multipliers
Stockout risk

The final dataset contains approximately 21,600 inventory records.

# *Target Variable*

The stockout_risk variable contains three classes:

Risk Level	Description
Safe	Sufficient inventory and low stockout risk
Imminent	Stockout may occur soon
At-Risk	High probability of stockout
Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook
Excel/CSV datasets
Machine Learning Workflow
Data collection
Data cleaning
Data preprocessing
Feature engineering
Exploratory data analysis
Feature selection
Model training
Model evaluation
Stockout risk prediction
Prediction analysis and visualization

# *Key Features*
Inventory Risk Prediction

Predicts whether an inventory item is Safe, Imminent, or At-Risk.

Demand Analysis

Uses sales velocity, units demanded, and units sold to understand inventory consumption.

Supplier Analysis

Considers supplier reliability and actual versus expected lead time.

Store and Product Analysis

Uses store characteristics, product category, price, popularity, and shelf life.

Seasonal Demand Analysis

Considers festivals and demand multipliers that can increase product demand.

Risk Distribution Analysis

Provides an overview of the number and percentage of records belonging to each risk category.

Prediction Performance Analysis

Compares actual stockout risk with predicted risk using classification metrics and confusion matrices.
