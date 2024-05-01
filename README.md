### UK Food Standards Agency Data Analysis

#### Instructions
The UK Food Standards Agency evaluates various establishments across the United Kingdom and assigns them food hygiene ratings. You've been contracted by the editors of a food magazine, Eat Safe, Love, to analyze some of the ratings data to help their journalists and food critics decide where to focus future articles.

#### Part 1: Database and Jupyter Notebook Setup

- **Import the data provided in the establishments.json file from your Terminal.**
  - Name the database `uk_food` and the collection `establishments`.
  - Copy the text you used to import your data from your Terminal to a markdown cell in your notebook.

- **Import the libraries you need:**
  - PyMongo and Pretty Print (pprint).
  - Create an instance of the Mongo Client.

- **Confirm database and data loading:**
  - List the databases you have in MongoDB. Confirm that `uk_food` is listed.
  - List the collection(s) in the database to ensure that `establishments` is there.
  - Find and display one document in the `establishments` collection using `find_one` and display with `pprint`.
  - Assign the `establishments` collection to a variable to prepare the collection for use.

#### Part 2: Update the Database

- **Add a new halal restaurant, "Penang Flavours," to the database.**
- **Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.**
- **Update the new restaurant with the BusinessTypeID found.**
- **Remove any establishments within the Dover Local Authority from the database.**
- **Convert latitude, longitude, and RatingValue to appropriate data types.**

#### Part 3: Exploratory Analysis

- **Answer specific questions using the dataset:**
  - Which establishments have a hygiene score equal to 20?
  - Which establishments in London have a RatingValue greater than or equal to 4?
  - What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
  - How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest and print out the top ten local authority areas.

#### Resources
