# Arvato-Udacity-project
Capstone project of the Data Scientist Nanodegree

**1. Project Overview**<br>
This project is about solving a customer segmentation analysis and developing a predictive model for the company Arvato. The company's client, who are we solving this problem for, is running a mail-order business. The company has provided extensive datasets containing detailed information about their past customers as well as the general population, who are not their customers. This is mostly demographic data about the German population. The goal of this project is to help Arvato identify the key differences and factors that determine whether someone is a customer or not. Gaining these insights can lead to a more targeted and efficient mailout campaign, attracting new customers and potentially generating significant revenue for the company.This project involves complex analysis, combining both unsupervised and supervised data science techniques. It begins with segmentation analysis to better understand the data, followed by the development of a predictive model capable of classifying potential customers.

`Read about this project on Kaggle, please see it below, as it offers some extra visualizations.`<br>
ARTICLE LINK PLACEHOLDER HERE<br>

--------------------------
**2. Technical Overview**<br>
The solution begins with Exploratory Data Analysis (EDA) to familiarize the reader with the dataset, identify the most problematic data issues, and outline appropriate countermeasures.<br>
After preprocessing the data using insights gained from the EDA, the analysis proceeds in two main parts:<br>

1.Customer Segmentation:<br>
- PCA and KMeans clustering are employed for dimensionality reduction and segmentation of the data.
- The objective is to uncover differences between clusters of customer and non-customer data.

2.Customer Classification:
- A classifier is trained on the customer data to predict customer status.<br>
- Multiple strategies and models are tested to determine the best possible predictive performance.<br>
- Feature importances and SHAP is utilized to explore the results.<br>

--------------------------

**3. The Data**<br>
- Datasets for this project fall under a restrictive license of their owner, Arvato, who does not allow them to be shared publicly.<br>
- For that reason the actual datasets or trained models using these data can not be made a part of this repository.

---------------------------

**4. Requirements**<br>
- The project is written in Python 3.10. Please refer to the attached `requirements.txt` file for detailed requirements.
