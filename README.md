# Data Intelligence with Databricks on GCP Google Cloud

### Build an end-to-end solution with the Lakehouse. Analyse and predict customer churn, we need information coming from different external systems
- Customer profiles coming from our website,
-  order details from our ERP system
-  mobile application clickstream to analyse our customers activity.
![The solution](solution.png)



### Using this steps
1. Ingest and create our Customer 360 database, with tables easy to query in SQL- We are implementing a *medaillon / multi-hop* architecture, but we could also build a star schema, a data vault or follow any other modeling approach

![Medallion](Medallion.png)
3. Secure data and grant read access to the Data Analyst and Data Science teams.
4. Run BI queries to analyse existing churn -Ingesting, transforming and cleaning data to create clean SQL tables for our downstream user 
5. Build ML model to predict which customer is going to churn and why
