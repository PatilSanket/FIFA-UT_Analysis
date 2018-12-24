# FIFA-UT_Analysis
Data Analysis & Visualization using Python

So, the dataset is FIFA18 Ultimate team, consisting all the information of all the players in football history(probably the notable ones).
It has some 80 odd columns which basically are the attributes of football players. i.e.Name,Club,Country,Rating etc.

It have tried to go through the data & understand what it is. Visualizing the data is the best way to analyse the data, because data is too large to grasp the patterns in it manually. So, I have used Matplotlib & Seaborn to visualize those patterns.

Now, lets go through the fun part of it, the actual code.
Firstly one need to import data. I have imported it using read_csv function from Pandas library from my local storage. To understand the data, info() & describe() can be used while using head() or tail() we can peek through the data. Next, some chopping & slicing of needs to done to filter out unwanted entries & columns. Now, we have the data we are interested in.
At this stage, we can get those patterns by visualizing them. For Example, by comparing two or more players based on their ability we can use any appropriate way to visualize. I have used line plots to compare players on the attributes. Some more visualization of data is done to get more insights.
Then I have used groupby() function to group the players by their teams. I then compared their best players on particular position with the skill. For Example comparing strikers of both teams on shooting abilities etc.
I then written a function to form best possible lineup of eleven players with best players occupying every position. This function takes a series as input which consist of the positions on football field. It returns the best lineup of eleven players.
