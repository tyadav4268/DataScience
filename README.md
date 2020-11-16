# DataScience - Let's Upgrade Course
## Day 1 Assignment
Questions 1:<br>
  Given the following jumbled word, OBANWRI guess the correct English word.
  A. RANIBOW
  B. RAINBOW
  C. BOWRANI
  D. ROBWANI
  
Questions 2:<br>
  Write a program which prints “LETS UPGRADE”.
  
Questions 3:<br>
  Write a program that takes cost price and selling price as input and displays whether the transaction is a
  Profit or a Loss or Neither.
  
Questions 4:<br>
  Write a program that takes an amount in Euros as input. You need to find its equivalent in
  Rupees and display it. Assume 1 Euro equals Rs. 80.
  
  
## Day 2 Assignment
Questions 1:<br>
  Create an empty list. Accept 10 numbers from the user and append to it the list if it is an even number.
  
Questions 2:<br>
  LIST COMPREHENSION.
  
Questions 3:<br>
  In this assignment, given a number n, you have to write a program that generates a dictionary d which
  contains (i, i*i), where i is from 1 to n (both included).
  Then you have to just print this dictionary d.
  
Questions 4:<br>
  There is a robot which wants to go the charging point to charge itself.
  The robot moves in a 2-D plane from the original point (0,0). The robot can
  move toward UP, DOWN, LEFT and RIGHT with given steps.<br>
  The trace of robot movement is shown as the following:<br>
  UP 5<br>
  DOWN 3<br>
  LEFT 3<br>
  RIGHT 2<br>
  Then, the output of the program should be:<br>
  2<br>
  The numbers after the direction are steps.<br>
  Write a program to compute the distance between the current position after
  a sequence of movement and original point. If the distance is a float, then
  just print the nearest integer (use round() function for that and then convert
  it into an integer).
  
## Day 3 Assignment
Questions 1:<br>
  Create a numpy array starting from 2 till 50 with a stepsize of 3.
  
Questions 2:<br>
  Accept two lists of 5 elements each from the user.
  Convert them to numpy arrays. Concatenate these arrays and print it. Also sort these arrays and print it.
  
Questions 3:<br>
  Write a code snippet to find the dimensions of a ndarray and its size.
  
Questions 4:<br>
  How to convert a 1D array into a 2D array? Demonstrate with the help of a code snippet
  Using: np.newaxis, np.expand_dims
  
Questions 5:<br>
  Consider two square numpy arrays. Stack them vertically and horizontally.
  Using: Use vstack(), hstack()
  
Questions 6:<br>
  How to get unique items and counts of unique items?
  
## Day 4 Assignment
Questions 1:<br>
  How to import pandas and check the version?
  
Questions 2:<br>
  How to create a series from a numpy array?
  
Questions 3:<br>
  How to convert the index of a series into a column of a dataframe?
  
Questions 4:<br>
  Write the code to list all the datasets available in seaborn library.
  Load the 'mpg' dataset.
  
Questions 5:<br>
  Which country origin cars are a part of this dataset?
  
Questions 6:<br>
  Extract the part of the dataframe which contains cars belonging to 'usa'
  
## Project PUBG
Tasks to be performed:
  1. Read the dataset.
  2. Check the datatype of all the columns.
  3. Find the summary of all the numerical columns and write your findings about it.
  4. The average person kills how many players?
  5. 99% of people have how many kills?
  6. The most kills ever recorded are how much?
  7. Print all the columns of the dataframe.
  8. Comment on distribution of the match's duration. Use seaborn.
  9. Comment on distribution of the walk distance. Use seaborn.
  10. Plot distribution of the match's duration vs walk distance one below the other.
  11. Plot distribution of the match's duration vs walk distance side by side.
  12. Pairplot the dataframe. Comment on kills vs damage dealt, Comment on maxPlace vs numGroups.
  13. How many unique values are there in 'matchType' and what are their counts?
  14. Plot a barplot of ‘matchType’ vs 'killPoints'. Write your inferences.
  15. Plot a barplot of ‘matchType’ vs ‘weaponsAcquired’. Write your inferences.
  16. Find the Categorical columns.
  17. Plot a boxplot of ‘matchType’ vs ‘winPlacePerc’. Write your inferences.
  18. Plot a boxplot of ‘matchType’ vs ‘matchDuration’. Write your inferences.
  19. Change the orientation of the above plot to horizontal.
  20. Add a new column called ‘KILL’ which contains the sum of following columns viz. headshotKills,
  teamKills, roadKills.
  21. Round off column ‘winPlacePerc’ to 2 decimals.
  22. Take a sample of size 50 from the column damageDealt for 100 times and calculate its mean. Plot
  it on a histogram and comment on its distribution.
