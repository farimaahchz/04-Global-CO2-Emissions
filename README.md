# 04-Global-CO2-Emissions
# Data Visualization

For this assignment you're going to make several graphs based on a single dataset.


Reading in the table as-is will produce a "MultiIndex" dataframe. By renaming all columns you can convert it into a non-MultiIndex dataframe.

Use slicing and/or boolean masks to filter out the rows in this table that aren't countries.

Graph 1: CO2 of the bigger countries

Make a graph of the CO2 emissions of the 5 biggest CO2 producers in the world (based on the latest measurement). The x-axis should be the years of 1990, 2005 and 2017. If newer datapoints are added in the future please include them as well. The y-axis should represent the fossil CO2 emissions in Mt CO2 for the given years. 

Graph 2: worst and best changers

Because of climate change it's important that we curb our carbon dioxide emissions. So some countries will have lowered their emissions while others may have increased their emissions. Some countries will have better results in doing this than others. If we calculate the relative change and sort by that change we'll get a list with countries that are changing for the better at one end and countries that are changing less well on the other end.

Find the top three and bottom three countries with regards to lowering these emissions and plot their results.


# Skills
Data Reading and DataFrame Handling:
Reading CSV data using pandas.
Working with pandas DataFrames.
Indexing and selecting data from DataFrames.

Data Filtering and Slicing:
Using boolean masks to filter rows based on conditions.
Slicing DataFrames to select specific rows and columns.

Data Visualization:
Creating line plots using matplotlib.
Customizing plot appearance, labels, and titles.
Using subplots (plt.subplots()).
Adding legends to plots.
Annotating data points on plots.

Data Calculation and Manipulation:
Performing calculations on DataFrame columns.
Creating new columns in DataFrames.
Applying calculations across rows or columns using functions like mean().
Using loops for iterating over sequences.

Data Analysis and Sorting:
Sorting DataFrames using sort_values().
Calculating top and bottom values based on specific criteria.
Selecting top or bottom rows from DataFrames.

Data Transformation and Aggregation:
Aggregating data using functions like mean().

Understanding DataFrame Structure:
Working with row and column indices.
Accessing data using index-based and label-based methods (iloc, loc).

Conditional Operations:
Applying conditions to filter data.
Performing operations based on conditions.

Flattening Data:
Flattening 2D arrays to 1D using flatten().

NumPy Array Manipulation:
Using NumPy arrays for calculations and operations.
Flattening arrays.

Understanding and Applying Library Documentation:
Understanding the usage of pandas and matplotlib functions from their official documentation.

Code Organization:
Structuring code using functions and loops for readability and reusability.
