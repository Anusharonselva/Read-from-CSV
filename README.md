# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file
## ALGORITHM:
### Step 1:Import pandas as pd.
### Step 2:Read the CSV file using read_csv method.
### Step 3:Use head and tail method to get the required contents from the file.
### Step 4:Use len() method to get the number of rows and columns
### Step 5:Print the output

## PROGRAM:

Developed by: S.ANUSHARON

Register number:212222240010

import pandas as pd

f = pd.read_csv('nba.csv')

print(f.head(10))

print(f.tail())

print("Number of rows:",len(f.axes[0]))

print("Number of columns:",len(f.axes[1]))

## OUTPUT:
![Uploading Screenshot (273).png…]()


## RESULT:
Thus a python program is written to read the contents of a CSV file.
