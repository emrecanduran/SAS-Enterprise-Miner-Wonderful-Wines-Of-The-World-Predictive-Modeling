# SAS-Enterprise-Miner-Predictive-Modeling 

# Wonderful Wines Of The World 

Wonderful Wines of the World (WWW) is a ten-year-old enterprise that seeks out small, unique wineries worldwide and brings its wines to its customers. Its mission is to delight its customers with well-made, unique, and exciting wines that would never travel far beyond their points of origin.
WWW sells wines through catalogs (electronic and physical), websites, mobile apps, and ten small stores in major cities around the USA. Customers can purchase at the stores, by telephone (after looking at the catalog), or through the website/mobile app.

Through aggressive promotion in wine and food magazines, WWW now has 350,000 customers in its database. Most customers are highly involved in wine, entertain frequently, and have sufficient money to indulge their passion for wine. WWW sometimes offers wine accessories as well – wine racks, cork extractors, etc.

WWW is trying to make use of the database it started about five years ago. So far, it has simply mass-marketed everything. Now, WWW wants to "get smart" about its database, and start differentiating customers. 
WWW has provided one random sample of its customers from its active database. These customers have purchased something from WWW in the past 24 months (after 24 months with no purchase, a person is eliminated from the active database).

## Dataset

The dataset used for this project contains the following variables:

- `Custid`: Customer ID, unique
- `Dayswus`: Number of days as a customer
- `Age`: Age of the customer
- `Education`: Highest academic degree earned
- `Income`: Household net income
- `Kidhome`: 1=has child under [0y-12y] living at home
- `Teenhome`: 1=has teen [13y-19y] living at home
- `Freq`: Number of purchases in past 24m
- `Recency`: Number of days since last purchase
- `Monetary`: Total sales to this person in 24m
- `LTV`: Customer lifetime value (derived variable)
- `Perdeal`: % Purchases bought on discount
- `Dryred`: % Of wines that were dry red wines
- `Sweetred`: % Sweet or semi-dry reds
- `Drywh`: % Dry white wines
- `Sweetwh`: % Sweet or semi-dry white wines
- `Dessert`: % Dessert wines (port, sherry, etc.)
- `Exotic`: % Very unusual wines
- `WebPurchase`: % Of purchases made on website/app
- `WebVisit`: Average visits to website/app per month
- `ExpressedPreference`: Explicitly preferred line of business (LOB)
- `NPS`: Net promoter score
- `Humid`: Target variable, binary

Note: DRYRED + SWEETRED + DRYWH + SWEETWH + DESSERT = 100%

## Model Building

The prediction task was performed using two machine learning algorithms: Neural networks and Decision trees. Various features were utilized to train the models and predict the "Humid" target column.

## Predicting Unseen Data

Using the best-performing model, I applied it to unseen data to predict. The results of the predicted unseen data are used to calculate Return On Investment for the marketing campaigns. 

## Dependencies

The following dependencies are required to run the code:

- SAS Enterprise Miner 15.2 version

## Results 

Neural Network, Number of Hidden Units 10, is selected as the best model. 
