# Eat Safe, Love 
## Food hygiene rating analysis for establishments across the United Kingdom
 
As a part of this project we are going to evaluate some of the ratings data of various establishments in order to help Eat Safe, Love magazine's journalists and food critics decide where to focus future articles.

The project is divided into two major steps :
1. Setup and Database update (NoSQL_setup_starter.ipynb)
      1. In this notebook, database connection is made and a new restaurant "Penang Flavours" has been added to the Database.
      2. Database is updated to add BusinessTypeID for the newly added restaurant
      3. Records from Dover Local Authority were deleted from the database
      4. Datatype is updated for few fields : latitude and longitude to decimal numbers; RatingValue to integer
        
2. Exploratory Analysis (NoSQL_analysis_starter.ipynb)
   In this notebook, based on the fields : RatingValue, Hygiene scores following questions are answered :
     1. Which establishments have a hygiene score equal to 20
     2. Which establishments in London have a RatingValue greater than or equal to 4
     3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"
     4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
  
