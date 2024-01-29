# Customer Personality Analysis

In this repository we devote a simple exploratory and clustering analysis of real data from customers of an online and physical store (that can be found [here](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)). The sequence of steps performed in each notebook is decribed as follows:

- **``exploring_preprocessing.ipynb``**

The topics worked in this repository can be summarized as:

1. Understand the data
2. Summarize the data with statistical estimators
3. Visualize the data with visualization tools

After exploring the data we will:

4. Preprocess the data (mainly with data cleaning) to use it in clustering and other analyses

- **``clustering_analysis.ipynb``**

It was applied the k-means algorithm after mixed dataset preprocessing, where customer classes were obtained.


Following the [repository description](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis) of each feature of the dataset:

- Attributes

```plaintext
ID: Customer's unique identifier
Year_Birth: Customer's birth year
Education: Customer's education level
Marital_Status: Customer's marital status
Income: Customer's yearly household income
Kidhome: Number of children in customer's household
Teenhome: Number of teenagers in customer's household
Dt_Customer: Date of customer's enrollment with the company
Recency: Number of days since customer's last purchase
Complain: 1 if the customer complained in the last 2 years, 0 otherwise
```

- Products

```plaintext
MntWines: Amount spent on wine in last 2 years
MntFruits: Amount spent on fruits in last 2 years
MntMeatProducts: Amount spent on meat in last 2 years
MntFishProducts: Amount spent on fish in last 2 years
MntSweetProducts: Amount spent on sweets in last 2 years
MntGoldProds: Amount spent on gold in last 2 years
```

- Promotion

```plaintext
NumDealsPurchases: Number of purchases made with a discount
AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
Response: 1 if customer accepted the offer in the last campaign, 0 otherwise
```

- Place

```plaintext
NumWebPurchases: Number of purchases made through the company’s website
NumCatalogPurchases: Number of purchases made using a catalogue
NumStorePurchases: Number of purchases made directly in stores
NumWebVisitsMonth: Number of visits to company’s website in the last month
```