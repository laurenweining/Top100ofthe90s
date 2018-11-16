Lauren Weining
Code Louisville Python for Data

Overall Goal of Project:
Determining the artist with the most billboard hits from the 90’s.  (1990-1999)

Source:
The database that I used originated from https://singleschronology.wordpress.com which is a listing of all top 100 singles, but was paired down to only include results from the 90’s and annotated by https://raywoodcockslatest.wordpress.com.  I used this csv file to perform my own personalized analysis of top 90’s hits.  The csv file is included in my github.

Analysis:
From my csv database I filtered out the irrelevant data and kept the Date, Year, Chart_Position, Artist and Title columns.  I ran an SQL command to make a new column that contained a calculated frequency for each artist, and then sorted them in descending order.  I did this to figure out how many hits each artist had from the 90’s.

Visualization:
For my project I chose to use matplotlib to create a bar graph representing the results that I found.  I used matplotlib over other alternatives because of its straightforward application and great documentation

Conclusion:
From this analysis I was able to determine that Madonna had the most overall hits, with a total of 24 total hits.  Additionally notable from graph, Mariah Carey and Whitney Houston.

Requirements to Run Project:
BillboardHot100Singles.csv (dataset included in github)
Anaconda
Jupyter Notebook
Matplotlib
Numpy
Pandas
Python
SQLite3




