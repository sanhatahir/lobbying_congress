Sequence of scripts: 

1. scraping_data_collection.ipynb
    * Gets data from ZIP file downloaded from ProPublica 
    * Scrapes OpenSecrets.org for relavant bills and gets relevant information
    * Scrapes OpenSecrets.org for funding data separately 

2. Merging: 
    * Merges the files created from (1) 

Note: Final output used is complete_bills_info2.csv 

3. Network: 
    * Used for network analysis 
    * Also creates CSV for adjancency matrix 

4. Embedding: 
    * Word embedding clusters from issues cited 

5. Cluster Analysis and PCA 