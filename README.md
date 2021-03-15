# Stout Global Investments' Case Studies


# Introduction
This repository is based on Stout Global Investments' Case Studies. These case studies will have two projects that will include analyses and visualizations of the data. 


# Abstract
The following areas of this repository will discuss and explain the objectives of these case studies. More details will be discussed in each section of the case studies guidelines. The general idea of these case studies are to find useful insights based on anonymous financial data from two different data sources.


## Case Study One Guidelines
The dataset contains synthetic transactions and some transactions are marked as fraudulent. We would like you to perform the following using the language of your choice:

• Describe the dataset and any issues with it.\
• Generate 3 visualizations using the data and write a brief description of your observations.\
• Create a feature set and perform prediction of fraudulent transactions using at least 2 algorithms. Describe any data cleansing that must be performed.\
• Visualize the test results and propose what could be done to improve results. Also describe assumptions you made and your approach.



## Case Study Two Guidelines
The dataset has 3 years worth of customer orders. There are 4 columns in the dataset: index, customer_email, net_revenue, and year.

For this dataset we need the following:

• Cleanse any data.\
• Total customer revenue for each year.\
• New customer revenue for each year.\
• Existing customer revenue growth for each year.\
• Existing customer revenue for each year.\
• Existing customer revenue for each prior year.\
• Revenue lost from customer attrition for each year.\
• Total customers for each year.\
• New customers for each year.\
• Lost customers for each year.

Additionally, we need 3 visualizations for the data which tell a story about the data. We would like to see the below visualizations:

• Breakdown of order ranges between years (e.g. pie chart of year 1 with orders showing percentages of orders <10$). Groupings should be meaningful.\
• Bar chart or another visualization showing revenue lost/gained for existing customers and new customers.\
• Bar chart or another visualization showing patterns of new vs existing customers purchase patterns based on groupings from the first visualization.



# Summary of Skills

## Case Study One 
I used the python environment to perform my exploratory data analysis. I also used the Pandas, Seaborn, Matplotlib, xgboost, scikit-learn, lightgbm, Numpy packages for this case study.


## Case Study Two 
Coming Soon


# Preview

## Case Study One 
![Preview of the Bar Plot created from this project.](https://github.com/micgonzalez/Stout-Global-Investments-Case-Studies/blob/main/case_study_one/bar_plot_of_diff_transactions.png)

This bar plot was created from this project to show the different types of payments found in this dataset to the public.


## Case Study Two 
Coming Soon


# Findings
Each of these projects are based on the guidelines given to me by Sout Global Investments. The datasets were given to me through the Kaggle webiste and dropbox. I was given the task to clean, analyze and create visualitons from the dataset then give a brief description of my findings. I have included my findings in each folder of the case studies. I have also included the code book for case study one's dataset in the folder for case study one.

## Case Study One
I did notice when I plotted the count of fraud and non-fraud data that it was imbalanced. When I looked at the different types of payments, combined with fraud and flagged as fraud data. The results made it better to understand the data.

## Case Study Two
Coming Soon


# Challenges

## Case Study One
The dataset being imbalanced was the challenge for this project. It changed the scope of this project by having the alogrithms look for the count of false positive and false negative results. It was not only detecting for transactions that were flagged as fraud, but detecting the ratio of the false positive and negative results.   

## Case Study Two
Coming Soon


# Conclusion

## Case Study One
When I selected my two algorithms, it opened my eyes to the fact that the dataset was imbalanced. Starting with my first algorithm, XGBoost gave me many options with different class weights. The second algorithm, Random Forest was the best algorithm for testing this dataset. It was hard for me to improve the results. I had no assumptions for this project, and I would attempted to add another algorithm to my approach. 

## Case Study Two
Coming Soon
