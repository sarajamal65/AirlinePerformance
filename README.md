# Airline_performance

aim: Ranking airline based on their performance
- per month
- sum of the flight
- average delay
- percentage on time status
- ...

It is mainly regarding the data sourcing 
---

In the carrier notebook, we directly get data about carrier from the internet, clean data, combine it with the data extracted from our database, and then upload a table in the datase. and also writing our sql_functions module. thus using a web browser , we read our csv directory from the web into python, and inserting carrier dta into the database in python.we added finally an external data source to our PostgreSQL database.

----

In the flight dataset, we're going to add data flight data. Also, instead of importing the data directly from the web, we're going to save it to our local file storage since the files are stored in a zip file. This means we will be unpacking the zip file first, then bring the data into the right shape and format through subsetting, merging and cleaning and ultimately insert it into our PostgreSQL database.
