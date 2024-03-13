
https://github.com/Harbringe/BCG/assets/99803292/75996e70-6a24-4d2a-8887-806a4e382904
# PowerCo Customer Churn Analysis Repository

This repository is dedicated to analyzing the customer churn trends of PowerCo, a utility company. Customer churn refers to the phenomenon where customers discontinue their services with a company over a certain period. Understanding and mitigating churn is crucial for businesses like PowerCo to maintain a stable customer base and sustain growth.

## Overview
PowerCo serves as a case study for exploring various aspects of customer churn, including:

- **Data Preprocessing:** Cleaning and organizing the provided data to make it suitable for analysis. This may involve handling missing values, encoding categorical variables, and scaling numerical features.
  
- **Exploratory Data Analysis (EDA):** Investigating the data to identify patterns, correlations, and potential factors contributing to churn. Visualization techniques are employed to gain insights into customer behavior.
  
- **Model Development:** Building predictive models to forecast churn based on historical data. This involves selecting appropriate algorithms, training the models, and evaluating their performance using metrics like accuracy, precision, recall, and F1-score.
  
- **Feature Importance Analysis:** Determining the key features that influence churn prediction. This helps in understanding the drivers behind customer attrition and devising strategies to retain valuable customers.
  
- **Recommendation and Action Planning:** Formulating actionable recommendations based on the analysis findings to reduce churn rates. These recommendations may involve targeted marketing campaigns, personalized offers, or service improvements.

## Repository Structure

The repository is structured into four distinct tasks, each contributing progressively towards the completion of the assignment.

### Task 1: Business Understanding and Hypothesis Framing:

#### Background Information:

PowerCo is a major gas and electricity utility that supplies to corporate, SME
(Small & Medium Enterprise), and residential customers. The power-liberalisation
of the energy market in Europe has led to significant customer churn, especially in
the SME segment. They have partnered with BCG to help diagnose the source of
churning SME customers.

A fair hypothesis is that price changes affect customer churn. Therefore, it is
helpful to know which customers are more (or less) likely to churn at their current
price, for which a good predictive model could be useful.

Moreover, for those customers that are at risk of churning, a discount might
incentivize them to stay with our client. The head of the SME division is considering
a 20% discount that is considered large enough to dissuade almost anyone from
churning (especially those for whom price is the primary concern).

The Associate Director (AD) held an initial team meeting to discuss various
hypotheses, including churn due to price sensitivity. After discussion with your
team, you have been asked to go deeper on the hypothesis that the churn is
driven by the customers’ price sensitivities.

Your AD wants an email with your thoughts on how the team should go about
testing this hypothesis.

The client plans to use the predictive model on the 1st working day of every month
to indicate to which customers the 20% discount should be offered.

#### Task Brief:

Your first task today is to understand what is going on with the client and to think
about how you would approach this problem and test the specific hypothesis.

You must formulate the hypothesis as a data science problem and lay out the
major steps needed to test this hypothesis. Communicate your thoughts and
findings in an email to your AD, focusing on the data that you would need from the
client and the analytical models you would use to test such a hypothesis.

We would suggest spending no more than one hour on this task.

Please note, there are multiple ways to approach the task and that the model
answer is just one way to do it.

**If you are stuck:**

1. Remember what the key factors are for a customer deciding to stay with or
switch providers

2. Think of data sources and fields that could be used to explore the
contribution of various factors to a customer’s possible action

3. Ideally, what would a data frame of your choice look like – what should
each column and row represent?

4. What kind of exploratory analyses on the relevant fields can give more
insights about the customer's churn behaviour?

**Estimated time for task completion: 1 hour depending on your learning style.**


#### Task 2: Exploratory Data Analysis

**Background Information:**
The BCG project team thinks that building a churn model to understand whether price sensitivity is the largest driver of churn has potential. The client has sent over some data and the AD wants you to perform some exploratory data analysis.

**The data that was sent over includes:**

- **Historical customer data:** Customer data such as usage, sign up date, forecasted usage etc.
- **Historical pricing data:** variable and fixed pricing data etc.
- **Churn indicator:** whether each customer has churned or not

**Please submit analysis in a code script, notebook, or PDF format.**

**Task brief:**

**Sub-Task 1:**

Perform some exploratory data analysis. Look into the data types, data statistics,
specific parameters, and variable distributions. This first subtask is for you to gain
a holistic understanding of the dataset. You should spend around 1 hour on this.

**Sub-Task 2:**

Verify the hypothesis of price sensitivity being to some extent correlated with
churn. It is up to you to define price sensitivity and calculate it. You should spend
around 30 minutes on this.

**Sub-Task 3:**

Prepare a half-page summary or slide of key findings and add some suggestions
for data augmentation – which other sources of data should the client provide you
with and which open source datasets might be useful? You should spend 10-15
minutes on this.

For your final deliverable, please submit your analysis (in the form of a
jupyter notebook, code script or PDF) as well as your half-page summary
document.

Note: Use the 2 datasets within the additional resources for this task and if you’re
unsure on where to start with visualising data, use the accompanying links. Be sure
to also use the data description document to understand what the columns
represent. The task description document outlines the higher-level motivation of
the project. Finally, use the eda_starter.ipynb file to get started with some helper
functions and methods.

**If you are stuck:** Think about ways you can define price sensitivity. Make sure to
think of all possible ways and investigate them.

**Estimated time for task completion: 1.75 hours depending on your learning style.**

**Making graphs in Python:**
**1. Matplotlib : Visualization and Python - ** [https://matplotlib.org/](https://matplotlib.org/)
**2. Seaborn : Statistical Data Visualization -** [https://seaborn.pydata.org/index.html](https://seaborn.pydata.org/index.html)

**Making graphs in R:**
**1. Ggplot 2-** [https://ggplot2.tidyverse.org/](https://ggplot2.tidyverse.org/)
**2. Plotly R Open Source Graphing Library -** [https://plotly.com/r/](https://plotly.com/r/)

#### Task 3: Feature Engineering and Model Training

Task 3 encompasses feature engineering and model training. Participants are expected to engineer additional features that demonstrate predictive power in identifying customer churn. Subsequently, they are required to train a Random Forest Classifier model to predict customer churn. As a bonus, participants should explore the potential profitability of offering a 20% discount to customers at risk of churning. 
(The ML solutions for this task will be linked soon)

#### Task 4: (Yet to be uploaded)

By structuring the repository in this manner, participants can systematically progress through each task, incrementally building upon their analysis and modeling efforts. 
  
### Usage
Researchers, data scientists, and business analysts can leverage this repository to gain insights into customer churn dynamics and develop strategies to mitigate churn effectively. By understanding the underlying factors driving churn, PowerCo can proactively address customer needs and enhance customer retention efforts.

### Disclaimer
This repository is created for educational and research purposes.

**This repository is still incomplete; more tasks will be completed and added soon.**
