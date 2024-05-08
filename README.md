# Read-from-CSV

## AIM:
To write a python program for reading the csv file content

## ALGORITHM:

## Step 1:
Load the CSV into a DataFrame.

## Step 2:
Print the number of contents to be displayed using df.head().

## Step 3:
The number of rows returned is defined in Pandas option settings.

## Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

## Step 5:
Increase the maximum number of rows to display the entire DataFrame.
## PROGRAM:
~~~
To write a python program for reading content from a CSV file.
Developed by: SANJAI L
Register Number: 212223230184
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
~~~

## OUTPUT:
![image](https://github.com/SanjaiOfficial/Read-from-CSV/assets/151763180/826fb998-c09c-40de-9826-70ee1ab2ca64)

![image](https://github.com/Mario-Viofer-J/Read-from-CSV/assets/144979232/1f2a4669-d79f-4c67-847b-7f3cae6193a2)


## RESULT:
Thus the program is written to read the csv file.
