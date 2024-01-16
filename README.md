# Problem_set_2

This problem set is designed to test your skills at cleaning up data that is messy. This means there are issues with the data that need to be addressed. The slides from this week cover all the commands you may need. You do not, however, need to use those exact commands. 

This week, we will be using a Star Wars dataset that I have edited. 

May the force be with you

## Step 1 - Import data

There are two files that contain our data 
- star_wars_data.1.tsv
- star_wars_data.2.txt

Import these into R and visually inspect them to make sure they make sense! 

_Hint_ the delimiter is different between the two files

# Step 2 - Clean up the data

The author of the first dataset (star_wars_data.1.tsv) did a bad job recording instances where there was no data

Sometimes they used the proper _NA_ and other times they used "unknown" or the string "NA"

Change the instances of unknown to _NA_

## Question 1

How many _NA_s are in the cleaned dataset 

# Step 3 - Clean up the last column

The author of this dataset also decided to combine the `homeworld` and `species` columns into a single column. This makes it difficult to analyze 

Split the `homeworld_species` column into 2 columns. 

## Question 2 

How many species are either a Droid or an Ewok

# Step 4 - Edit the mass column

By using "unknown" instead of _NA_, the author introduced problems into the mass column. You will need to identify and fix this problem before answering the next question. 

# Question 3

What is the median mass of all the characters?

