# Marketing Classifier Comparison

This project compares the performance of four supervised learning classifiers:

- K-Nearest Neighbors
- Logistic Regression
- Decision Trees
- Support Vector Machines

The dataset comes from a bank’s telephone marketing campaign.
The primary goal is to **evaluate model performance** and determine which classifier performs best under different conditions.

The secondary goal is to answer the business question:

**Which customers should we target in our marketing campaign to maximize term‑deposit subscriptions?**

Answering this allows us to predict which customers are most likely to say “Yes” to a term‑deposit subscription.

## Model Performance
Here's the summary of model performance (including the baseline model with tuned parameters):

![Model Comparison](images/all_models_comp_tuned.png)

## Model Chosen - the Decision Tree

Given the business objective and the priority placed on maximizing Recall for the “Yes” class, 
the Decision Tree emerged as the model that best answers the business question. 
Because it identifies the largest share of true subscribers, it provides the 
strongest foundation for actionable targeting.

Accordingly, the following marketing guide is derived directly from 
the Decision Tree’s structure and highlights the customer segments 
most likely to convert.

![Model Comparison](images/marketing_recommendations.png)

## Repository Structure

- [notebooks/](notebooks/) — Jupyter notebook containing the project  
- [data/](data/) — dataset (CSV, Excel file storage)  
- [images/](images/) — image storage  
