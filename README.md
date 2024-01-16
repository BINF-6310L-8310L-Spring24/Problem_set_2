# Problem_set_2

This problem set is designed to test your skills at cleaning up data that is messy. This means there are issues with the data that need to be addressed. The slides from this week cover all the commands you may need. You do not, however, need to use those exact commands. 

This week, we will be using a Star Wars dataset that I have edited. 

May the force be with you

# Step 1 - Import data

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

## Question 3

How many different home worlds are there? Do not include missing data.

_Hint!_ We replaced NAs _before_ the columns were split. Check on that again.

# Step 4 - Edit the mass column

By using "unknown" instead of _NA_, the author introduced problems into the mass column. You will need to identify and fix this problem before answering the next question. 

## Question 4

What is the median mass of all the characters?

# Step 5 - Edit star_wars_data.2.txt

The person who recorded the films did a _terrible_ job. All of the films are in release order for 7 of the films. The first film listed is the first released film the character was in. 

Split this column to identify the **second** movie a character was in

## Question 5 

How many character's 2nd film was "Return of the Jedi"?

## Question 6 

How many characters were only in 1 film? _As of the force awakens_

# Step 6 - Merge the datasets

Combine the two datasets to answer the questions below

## Question 7

Which group has a greater mean height - characters in 1 movie or characters in more than 1 movie?

## Question 8

How many Human characters had their 2nd movie "The Empire Strikes Back"?

## Question 9 

You hypothesize that the ratio of mass/height is smaller in characters from the earlier movies. Which group has a smaller **median** mass/height ratio - characters whose second movie was in the original trilogy ("The Empire Strikes Back," "Return of the Jedi," "A New Hope") or those who had a second movie from the later series?



