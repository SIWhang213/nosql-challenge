# nosql-challenge 
## This is Module 12 Challenge. 

### Part 1: Database and Jupyter Notebook Set Up (NoSQL_setup.ipynb)
* Import the data provided in the establishments.json file from your Terminal. Name the database uk_food and the collection establishments . 
* Within notebook, import the libraries that is need.
* Create an instance of the Mongo Client.
* Confirm that the database was created and the data was loaded  properly.
* Assign the establishments collection to a variable to prepare the collection for use.

### Part 2: Update the Database (NoSQL_setup.ipynb)
* An exciting new halal restaurant just opened in Greenwich, but hasn't been rated yet. The magazine has asked you to include it the analysis.
* Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields
* Update the new restaurant with the BusinessTypeID.
* The magazine is not interested in any establishments in Dover, so check how many documents contain the Dover Local Authority. Then, remove any
establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted.
* Some of the number values are stored as strings, when they should be stored as numbers.

### Part 3: Exploratory Analysis (NoSQL_analysis.ipynb)
* Question 1: Which establishments have a hygiene score equal to 20?
* Question 2: Which establishments in London have a RatingValue greater than or equal to 4?
* Question 3: What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
* Question 4: How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten
local authority areas.

### Attached folder and files :
* Two jyputer notebook files(NoSQL_setup.ipynb, NoSQL_analysis.ipynb)
* One REDME file
