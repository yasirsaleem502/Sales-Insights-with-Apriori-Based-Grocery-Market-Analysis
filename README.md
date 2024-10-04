# Driving Sales Insights with Apriori-Based Grocery Market Analysis

### Project Overview
The Driving Sales Insights with Apriori-Based Grocery Market Analysis project aims to leverage the power of the Apriori algorithm to analyze grocery store transaction data and uncover actionable insights. These insights will help retailers understand customer purchasing behavior, identify frequently bought-together products, and generate association rules to enhance cross-selling strategies, improve product placement, and ultimately drive sales growth.

### Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Apriori Algorithm](#apriori-algorithm)
- [Model Evaluation Metrics](#model-evaluation-metrics)
- [Reasult](#reasult)
- [Contact](#contact)
  

## Introduction
Market Basket Analysis is a powerful tool used in the retail industry to study the purchasing patterns of customers and discover associations between different products. This project applies the Apriori Algorithm to grocery market transaction data to identify frequent itemsets and generate association rules. These insights can be leveraged to improve store layout, drive cross-selling, and optimize inventory management, which can all lead to increased sales.

The goals of this project are:
- To analyze grocery store transaction data and discover product combinations that are frequently purchased together.
  
- To generate association rules that can help retailers make data-driven decisions about product placement and promotions.
  
- To provide an actionable framework for driving sales insights from transaction data.

## Dataset
The dataset for this project contains grocery transaction data, with each transaction including a unique ID and a list of purchased items. It represents the purchasing behavior of customers in a typical grocery store, making it ideal for market basket analysis.

Dataset Description:

TransactionID: 
A unique identifier for each transaction.
Items: 
A comma-separated list of items purchased in a single transaction.

dataset link: https://www.kaggle.com/datasets/muhammadyasirsaleem/grocery-market-basket-transactions

## Apriori Algorithm
The Apriori Algorithm is used to mine frequent itemsets and generate association rules based on transaction data. It works on the principle that subsets of frequent itemsets must also be frequent, which helps efficiently find patterns in large datasets.

Key Concepts:

1- Frequent Itemsets: Groups of items that appear together in transactions with a frequency higher than a specified threshold (support).

2- Association Rules: Rules of the form A → B, which indicate that if item A is purchased, item B is likely to be purchased as well. These rules are evaluated based on:

**Support**: The proportion of transactions that contain a particular itemset.

**Confidence**: The likelihood that item B is purchased when item A is purchased.

**Lift**: The ratio of the observed support to the expected support if A and B were independent.

## Model Evaluation Metrics:

**Support**: Frequency of an itemset appearing in transactions.

**Confidence**: Likelihood of one product being bought when another product is bought.

**Lift**: Measure of the strength of the rule in comparison to random chance.

## Reasult

## Frequent Itemsets
![aprori algo 1](https://github.com/user-attachments/assets/264801fb-1b10-4380-a141-85b6d9924e51)

## Comparison of Support, Confidence, and Lift
![aprori algo 2](https://github.com/user-attachments/assets/4d4d301e-4bda-4ed7-954e-f702dbed9f3e)

![aprori algo 4](https://github.com/user-attachments/assets/97367983-54f9-44a9-a13b-9b73c65fe7d6)



## Plotting network graph
![aprori algo 3](https://github.com/user-attachments/assets/9dbf6aff-7035-4f6e-895a-6de1c3f5282a)


## Contact
- Author: Muhammad Yasir Saleem
- Email: myasirsaleem94@gmail.com
- LinkedIn:https://www.linkedin.com/in/muhammad-yasir-saleem/


Feel free to reach out if you have any questions or need further information.

