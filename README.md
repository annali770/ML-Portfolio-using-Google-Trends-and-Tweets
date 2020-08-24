# MLaF
Project Description:

We attempted to form an optimal MV portfolio using Google Trends search volumes and Twitter Sentiment. The pipeline is as follows:
1. Scrape news headlines to identify financially relevant words
2. Use relevant finance words to scrape Tweets and Google Trends data
3. Conduct ENET regression using this data and to predict returns, risks, and covariances of 5 ETFs
4. Form portfolio using four strategies

    a. GMV
  
    b. Equal-weight
  
    c. Risk-parity
  
    d. Max Sharpe ratio
 
 All the scraped data has been cleaned and pre-processed in final.csv. The code for scraping can be found in each respective folder. The code to run everything is in "Running Regressions"
 
 To do:
 1. Better tune the ENET models using a more exhaustive list of search parameters
 2. Rebalance portfolio monthly (the current code forms a portfolio at the beginning of the test period and does not rebalance)
 3. Incorporate predicted covariances into portfolio formation
 4. Find a better way to replace NA values (we forward filled)
 5. Create more informative visualizations
 
 Please contact hlian@andrew.cmu.edu if you have any questions.
