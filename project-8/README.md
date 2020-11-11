# Finding the best place for a new oil well

#### Libraries used: Pandas, Numpy, Sklearn

Data on oil samples from three regions will be used to create a model that will help pick the region with the highest profit margin. The Bootstrapping technique will be used to analyze potential profit and risks.

Conditions:

- Only linear regression is suitable for model training (the rest are not sufficiently predictable).
- When exploring the region, a study of 500 points is carried with picking the best 200 points for the profit calculation.
- The budget for development of 200 oil wells is 100 USD million.
- One barrel of raw materials brings 4.5 USD of revenue The revenue from one unit of product is 4,500 dollars (volume of reserves is in thousand barrels).
- After the risk evaluation, only the regions with the risk of losses lower than 2.5% will be kept. From the ones that fit the criteria, the region with the highest average profit should be selected.

