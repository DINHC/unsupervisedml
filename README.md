# unsupervisedml

Purpose:

To read cryptocurrency csv and create an unsupervised machine learning code that applies StandardScaler and Dimension Reduction to produce graphs that would indicate whether the cryptocurrencies can be clustered together. 


Steps:
  1. Imported all neccessary components
  2. Imported and Read CSV 
  3. Examined the CSV 
  4. Altered the df to include parts of the data where Trading occured 
  5. Removed all rows with NA
  6. Dropped IsTrading Column
  7. Dropped CoinName column
  8. Altered df once more to include only data where Total Coins Mined > 0
  9. Created dummy data for Algorithm and Prooftype columns
  10. Used StandardScaler on df 
  11. Used PCA to reduce data to 90% (n_components =0.90)
  12. Created new df based on PCA
  13. Applied TSNE and transform new df
  14. Created scatter graph and line graph to examine amount of clusters shown 


Conclusion:
- Based on the scatter graph along with the elbow chart, we can safely say that there are 4 clusters visible. We can reccommend to the client that the cryptocurrencies can be clusted together
