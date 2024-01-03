# Read-from-CSV
program to read contents from a csv file
## AIM:
create a csv file named nba.csv
## ALGORITHM:
### Step 1:
create a csv file named nba.csv
### Step 2:
now open the file using open()
### Step 3:
now open the file using open()
### Step 4:
now the information in the file is been read
### Step 5:
readed text been displayed

## PROGRAM:
```
#Program to read contents from a csv file
#Developed by : Allen Joveth P
#Register Number : 23009582

import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("number of columns:",len(df.axes[1]))

```
## OUTPUT:

![Screenshot 2024-01-03 214840](https://github.com/allenjoveth/Read-from-CSV/assets/139422287/629aeb6a-24cc-4886-9381-63b56251a361)

## RESULT:
