# Gas consumption of my car

This is my repository to keep track of my car's gas mileage. 
I keep records of my gas consumption on a [MongoDB](https://www.mongodb.com/) database.
I have saved records from my gas receipts since August 2013:

* date
* ppg (Price per gallon)
* total money spent (I fill the gallon at 1/4 empty)
* miles traveled (I get this from my odometer)

The database located at *~/db/gas_repeipts.json* is called **'corolla_2010'** and it
contains a collection called **'gas_receipts'**.

I use [pymongo](https://api.mongodb.com/python/current/) to connect to my database
and [pandas](https://pandas.pydata.org/) + [matplotlib](https://matplotlib.org/) to explore the data. 
The *gas_consumption.ipynb* notebook contains the exploration

