# dinamoDBdatamodelling
Context
Typically e-commerce datasets are proprietary and consequently hard to find among publicly available data. However, The UCI Machine Learning Repository has made this dataset containing actual transactions from 2010 and 2011. The dataset is maintained on their site, where it can be found by the title "Online Retail".

Content
"This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers."

Acknowledgements
Per the UCI Machine Learning Repository, this data was made available by Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK.

Image from stocksnap.io.

Inspiration
Analyses for this dataset could include time series, clustering, classification and more.

https://www.kaggle.com/carrie1/ecommerce-data?select=data.csv

Data Modelling : Convert from csv file using Amazon Lambda to NoSQL Amazon DinamoDB
Based on API Access Patern
1. Get Items by CustomerID
2. Get Items by InvoiceDate
3. Get Monthly Items by Country
4. Get Monthly Items by (Sort: Highest ItemsQuantity vs UnitPrice)
5. Get Items by Lowest Quantity on Hand (for warehouse purchasing)
