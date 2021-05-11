# A-B-Testing-Marketing-Promotions
## Table of Content
  - [Project Overview](#projectoverview)
  - [Data Description](#datadescription)
  - [Technical Overview](#technicaloverview)
  - [Results](#results)
  
***

<a id='projectoverview'></a>
## Project Overview

In this project, A fast food chain plans to add a new item to its menu. However, they are still undecided between three possible marketing campaigns for promoting the new product.
In order to determine which promotion has the greatest effect on sales, the new item is introduced at locations in several randomly selected markets. A different promotion is used at each location, and the weekly sales of the new item are recorded for the first four weeks. This project aims to compare the three promotions by statistical metrics in order to decide which promotion has the best effect, then the marketing team can start to launch this promotion on a large scale. 


This project is mainly divided into five steps as below:

1. `Performing Sanity Check for the Dataset` in this part, statistics description was examined for the numerical data as well as the value and counts was calculated for the categorical data. Moreover, the dataset was examined if it contains any missing values.

2. `EDA and Visualisations` in this part, focusing on some key featurs "Promotion" "MarketSize" "AgeOfStore" and "Sales", various charts were plotted in order to check "Sales distribution in three promotions", "Market sizes across different promotions", and " Distribution of Store Age".

3. `Performing A/B Testing` in this part, sales value was chosen as the metric to compare among three promotions. Next, the mean, standard diviation, and number of promotions were calculated for each promotion.

4. `Comparing Promotion 1 and 2` in this part, by using scipy stats, t-value and p-values were calculated and the result came out as promotion 1 and 2 are significantly different and promotion 1 outperformed promotion 2.

5. `Comparing Promotion 1 and 3` in this part, as the last step, t-value and p-value were calculated and the result told no significant difference between promotion 1 and 3. Therefore, the final result is that promotion 1 is the best. 

<a id='datadescription'></a>
## Data Description

 The dataset consists of 548 entries including:

MarketId: an inhouse tag used to describe market types, we won't be using it
AgeOfStores: Age of store in years (1–28). The mean age of a store is 8.5 years.
LocationID: Unique identifier for store location. Each location is identified by a number. The total number of stores is 137.
Promotion: One of three promotions that were tested (1, 2, 3). We don’t really know the specifics of each promotion.
Sales in Thousands: Sales amount for a specific LocationID, Promotion and week. The mean amount of sales are 53.5 thousand dollars.
Market size: there are three types of market size: small, medium and large.
Week: One of four weeks when the promotions were run (1–4).

<a id='technicaloverview'></a>
## Technical Overview

The main technical skills included in this project are: 

* EDA and Visualization
* Statistical metrics
* Scipy Stats

<a id='results'></a>
## Results

The results have been clearly documented in the Jupyter Notebook. Please refer to [A_B_Testing_Marketing_Promotions_Workbook.ipynb](A_B_Testing_Marketing_Promotions_Workbook.ipynb). 
