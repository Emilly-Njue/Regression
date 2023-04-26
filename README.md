# Regression

Description

Analysis of ‘Housing Dataset’ provided by Analyst-2 (analyst-2.ai), based on source dataset retrieved from https://www.kaggle.com/peterkmutua/housing-dataset on 21 November 2021.

--- Dataset description provided by original source is as follows ---

The melbourne_housing.csv dataset contains information about real estate properties in Melbourne, Australia. The dataset has 21 columns, each of which represents a different attribute of the properties. Here's a brief overview of each column:

`Suburb`: the name of the suburb where the property is located.
Address: the street address of the property.
Rooms: the number of rooms in the property (e.g., 1 bedroom, 2 bedrooms, etc.).
Type: the type of property (e.g., house, townhouse, unit, etc.).
Price: the price of the property in Australian dollars.
Method: the method of sale (e.g., S - property sold; SP - property sold prior; PI - property passed in; PN - sold prior not disclosed; SN - sold not disclosed; NB - no bid; VB - vendor bid; W - withdrawn prior to auction; SA - sold after auction; SS - sold after auction price not disclosed).
SellerG: the name of the real estate agency or agent selling the property.
Date: the date of sale of the property.
Distance: the distance of the property from the Melbourne CBD (central business district) in kilometers.
Postcode: the postal code of the suburb where the property is located.
Bedroom2: the number of bedrooms in the property according to the real estate agency's records.
Bathroom: the number of bathrooms in the property.
Car: the number of car spaces in the property.
Landsize: the size of the land on which the property is located in square meters.
BuildingArea: the size of the building on the property in square meters.
YearBuilt: the year the property was built.
CouncilArea: the name of the local government area in which the property is located.
Lattitude: the latitude of the property's location.
Longtitude: the longitude of the property's location.
Regionname: the name of the region in which the property is located (e.g., Western Metropolitan, Eastern Metropolitan, etc.).
Propertycount: the number of properties in the suburb where the property is located.
These columns provide a wide range of information about each property, including its location, size, age, and price. This information can be used to analyze real estate trends in Melbourne and to build predictive models that can estimate the price of a property based on its attributes.


Context
There's a story behind every dataset and here's your opportunity to share yours.

ACTIVITIES

Follow the process below to develop a model that can be used by real estate companies and real estate agents to predict the price of a house.

Business Understanding -Conduct a literature review to understand the factors that determine the price of houses globally and locally. -Based on the dataset provided, formulate a business question to be answered through the analysis.

Data Understanding -The data in the dataset provided was collected through webs scrapping. Conduct further reading to understand the process of web scrapping, how it is conducted (methods and tools) and any ethical challenges related to it.

Data Preparation -Conduct a detailed exploratory analysis on the dataset. -Prepare the dataset for modeling -Identify the technique relevant for answering the business question stated above. -Ensure that the dataset meets all the assumptions of the technique identified. -Conduct preliminary feature selection by identifying the set of features that are likely to provide a model with good performance.

Modeling -Split the dataset into two; training set and validation set. With justifications, decide on the ratio of the training set to the validation set. -Generate the required model

Evaluation -Interpret the model in terms of its goodness of fit in predicting the price of houses. -Assume that the model is not good enough and then conduct further feature engineering or use any other model tuning strategies at your disposal to generate additional two instances of the model. -Settle on the best model instance and then re-interpret.

Implementation -Think of how the model can be implemented and used by real estate firms and agents. -Identify possible challenges of applying the model. -Recommendations on how the model can be improved in future

--- Original source retains full ownership of the source dataset ---
