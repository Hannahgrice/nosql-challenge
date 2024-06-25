Part 1: Database and Jupyter Notebook Set Up
Data Import:

Import establishments.json into the uk_food database with the establishments collection using your terminal. Copy the terminal command to a markdown cell.
Library Imports:

Import PyMongo and Pretty Print (pprint).
Database Confirmation:

Create a MongoDB client instance.
Confirm the uk_food database and establishments collection exist by listing databases and collections.
Display one document from establishments using find_one and pprint.
Assign the establishments collection to a variable.
Part 2: Update the Database
Modify Establishments Collection:
Find and note the BusinessTypeID for "Restaurant/Cafe/Canteen".
Update the new restaurant with the found BusinessTypeID.
Remove all establishments in Dover and confirm deletion by checking document count.
Convert latitude and longitude to decimal numbers using update_many.
Convert RatingValue to integer numbers using update_many.
Part 3: Exploratory Analysis
Analysis Setup:
These steps will set up the database, make necessary updates, and prepare the data for analysis.





