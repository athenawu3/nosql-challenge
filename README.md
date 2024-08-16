# NoSQL Challenge

## Overview:
In this challenge, I analyzed data on various food establishments across the UK. You can find the database in Resources/establishments.json.

### Part 1 and 2:
1. In Part 1, I set up the database to prepare for analysis. I imported the database from my Terminal using mongoimport. I then used PyMongo to load the database and its establishments collection.
2. In Part 2, I made some updates to the database. I added information for a new restaurant called "Penang Flavours". And I updated the data types for latitude, longitude, and RatingValue to numeric values.

### Part 3:
Through my analysis in Part 3, I determined the following:
1. 82 establishments have a hygiene score equal to 20.
2. 33 establishments in London have a RatingValue greater than or equal to 4.
3. The top 5 establishments near Penang Flavours with a RatingValue of 5 are Lucky Food & Wine, Everest Stores Ltd, Premier Express, Fineway Cash & Carry, and TIWA N TIWA, sorted by lowest hygiene score.
4. The Local Authority areas with the greatest number of establishments with a hygiene score of 0 are Thanet, Greenwich, Maidstone, Newham, Swale, Chelmsford, Medway, Bexley, Southend-on-Sea, and Tendering.
