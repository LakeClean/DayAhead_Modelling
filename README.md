# DayAhead_Modelling

This repository is meant as a tutorial myself for figuring out Day ahead trading in the European market.
objectives:
	- Import and visualize data from entsoe.
	- Figure out what parameters are relevant in modelling.
	- Create naive models.
	- Test models.

# Data
Data is requested from the entsoe "transparancy" website.
For some reason half the links to this webpage are out of date.
To get the data you need an API key. That you then can use later for requesting data with the entsoe-py module.
To get the API key you need to:
	- Create an account on the data transparency website
	- Send an email to "transparency@entsoe.eu" with the subject: "Restful API access" and body: "Email address of registration: <your@email.com>"
	- When they respond you will then have access to creating an API key. Go to entsoe transparancy platform. 
	- click my account settings
	- click generate API security token
	- Copy the token and store it safely
Now you can use the entsoe-py module to import data.

#Packages
- entsoe-py
- pandas
- numpy
- astropy.time
- matplotlib.pyplot
- glob
