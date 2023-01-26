# Read-from-CSV

## AIM:

## ALGORITHM:
## Step 1:

Import pandas as pd.
## Step 2:

Read the CSV file using read_csv method.
## Step 3:

Use head and tail method to get the required contents from the file.
## Step 4:

Use len() method to get the number of rows and columns.
## Step 5:

Print the output.

## PROGRAM:
```
#Developed by: JEEVAGOWTHAM S
#Reference No: 22008760
import pandas as pd 
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT:

Thus a python program is written to read the contents of a CSV file.
![Screenshot from 2023-01-26 17-00-18](https://user-images.githubusercontent.com/118042624/214825130-dd64c0ef-c4f5-4fc8-9bc6-ef0d3b1ce809.png)


## RESULT:


Thus a python program is written to read the contents of a CSV file.
