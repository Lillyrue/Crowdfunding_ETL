# Crowdfunding_ETL

Show us the money! We're back to one of our original datasets for our second mini-project. This time around, we're building an ETL pipeline from .xlsx documents. 

### Extractions
We started with two documents- one with crowdfunding data and one with contacts. Once those files were added to the repo, we moved them into our IDEs for the transformations. 

### Transformations
The bulk of the project focused on tranforming data. Using Python, Pandas and various Py Dictionaries, we created separate files that would later become our DB tables. 

### Loads
Once the tables were properly formatted, we created a schema for the DB using QuickDBD and used the SQL export to create a DB in PostgreSQL. After a couple of tries (due to some column formatting and data type oversights), we were able to import the data into the newly created DB. A quick check revealed that all of the information loaded correctly. 

### Takeaways
This was a fun project. It was great being able to work with a partner and we combined learnings from the past few weeks to complete the assignment efficiently. It was a rewarding exercise because it demonstrated various stages of the ETL process are developed. 