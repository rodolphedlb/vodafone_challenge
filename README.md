# V by Vodafone Data Challenge 2018
### Profiles Customers Interested in IoT Products
![](https://logo.clearbit.com/vodafone.nl)

The Vodafone Challenge was a team project in the context of our machine learning course. 
The goal was to create customer clusters for a recent Vodafone product line (V by Vodafone) using a customer dataset with anonymized information. 
The output was used to develop the best marketing strategy for the Italian market.


### Original Challenge Description
#### Scope: 
The overall goal of the challenge is to profile customers interested in 4 determined products by means of unsupervised learning (clustering). 

#### Data Source: 
The dataset describes the profiles of around 2,600 Vodafone customers who have shown interest in one of the V by Vodafone products. The variables provided are: 
1. The spetific V by Vodafone product that the customer has shown interest in. 
2. 15 personal and general customer variables such as 
    - ‘Age’
    - ‘Monthly Calls in Minutes’
    - ‘ARPU’ (average revenue per user) in the same month 
3. 13 data traffic categories (e.g. ‘Games’, ‘Streaming Applications’) and their shares in each customer’s traffic over a one month time window.
    - All numerical variables are scaled between 0.0 and 1.0 
    - No identification features like phone numbers will be included. 
    - In the categorical variables there may be null values, which means that for the partitular instance the data is not available. 

#### Evaluation: 
The general evaluation criteria are: 
- How many of the clusters resemble customers interested in a specific product? 
- How closely does each cluster enclose those customers?
- The novelty and explainability of the solution.

#### Dataset Sample
![Dataset Sample](https://raw.githubusercontent.com/rodolphedlb/vodafone_challenge_data_science/master/Dataset_Sample.jpg)
