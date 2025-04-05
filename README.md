** How to Crawl the data **

First Create a S3 Bucket -aws-glue-demo221 .
Inside this Create a Retaildb folder.
Inside this Retaildb folder Create a order folder.
After that add file (Order_data2.csv) and upload inside the orders folder.
Create a Crawler.
Add a Data source in the Crawler.
Give the S3 path of the Orders folder and brwoser it.
Now Create IAM role New (aws-glue-service-01) and select Create Crawler.
After this once the Crwaler. 
Run the Crawler.
Created go to the Data Catelog and go for Actions.
In Action choose Preview View Data
This will show your Crwalered data.
