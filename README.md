# Business-Sales-Analysis
Small data science project using Python.

Library used is Pandas and Matplotlib to analyze and answer some business questions related to sales. The data contains hundreds of thousands of electronic store purchases broken down by month, product type, cost, purchase address etc.

Started by cleaning data as follows:
1) Drop NaN values from Dataframe
2) Removing rows based on condition that was creating issues
3) Change the type of columns (to_numeric, to_datetime, _astype)

After cleaning data move to exploration part.

The questions answered in the project are:
1) What was the best month for sales? How much was earned that month?
2) What city sold the most product?
3) What time should we display advertisemens to maximize the likelihood of customer’s buying product?
4) What products are most often sold together?
5) What product sold the most? Why do you think it sold the most?

What stuffs we did here ?

1> Concatenating multiple csvs together to create a new DataFrame (pd.concat)

2> Adding columns

3> Parsing cells as strings to make new columns (.str)

4> Using the .apply() method

5> Using groupby to perform aggregate analysis

6> Plotting bar charts and lines graphs to visualize our results

7> Labeling our graphs
