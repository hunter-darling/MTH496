Context
-------

This dataset provides a list of building units sold in New York City within one year.

Features
--------
BOROUGH: A digit code for the borough the property is located in; in order these are Manhattan (1), Bronx (2), Brooklyn (3), Queens (4), and Staten Island (5).

BLOCK; LOT: The combination of borough, block, and lot forms a unique key for property in New York City. Commonly called a BBL.

BUILDING CLASS AT PRESENT and BUILDING CLASS AT TIME OF SALE: The type of building at various points in time. See the glossary linked to below.

Gloosary temrs: http://www1.nyc.gov/assets/finance/downloads/pdf/07pdf/glossary_rsf071607.pdf
Building Classifications: http://www1.nyc.gov/assets/finance/jump/hlpbldgcode.html

Labels
-----
SALE PRICE

Note
----
SALE PRICE labels are continuous values. So use https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html

