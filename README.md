## Udacity : Invistigate a Dataset: TMDB Dataset



### Introduction: 
In this project I am going to analyze a dataset provided by TMDB through Udacity's Data Analyst Nano Degree. I am going to be asking the questions below and communicating the findings visually. 

    1. Are movies with higher budget more profitable?
    2. What movie genres are the most profitable?
    3. Does the release month affect the movie's profitablity?
    4. Is there a coreclation between the popular movies and their profitability?
    
    
### Installation : 

In order to analyze the dataset, we will need to have numpy, pandas, matplotlib and seaborn libraries installed. We also need to have the (tmdb-movies.csv) file in the same folder as the Ipython file. 


### Limitations:
    - The budget_adj, and revenue_adj columns have rows with 0 values in them. In order to find accurate answers for my research questions, I choose to drop those rows.

    - The values in the budget_adj and revenue_adj columns do not have a specific currency. For the sake of this analysis, I would assume that the currency is US dollars.
    -In order to consider the inflation, I would be using the Adjusted Budget and Adjusted Revenue Columns