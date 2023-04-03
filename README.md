# NoSQL Challenge

The goal of this challenge was to setup a Mongo Database and export a json file to fill the database. Then the challenge was broken into two parts:
1. *Part One* - Setup and Update
    
    In this part, we setup the mongo database and then update the database by adding another document. We then fill in some missing information for this document. For the next step, we delete all documents in the "Dover" local authority. Finally, we change the datatype for latitude and longitude values from string to decimal.

2. *Part Two* - Analysis
    
    This part focused on analysis on the database. We answered four questions during this part:
    1. Which establishments have a hygiene score equal to 20?
    2. Which establishments in London have a RatingValue greater than or equal to 4?
    3. What are the top 5 establishments with a rating value of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
    4. How many establishments in each Local Authority area have a hygiene score of 0?
    
    These queries were performed on the database using functions such as "find", "aggregate" and "count documents". The results were then converted into a pandas dataframe.
