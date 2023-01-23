# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:

Import pandas as pd.

### Step 2:

Read the CSV file using read_csv method

### Step 3:

Use head and tail method to get the required contents from the file.

### Step 4:

Use len() method to get the number of rows and columns

### Step 5:

Print the output.

## PROGRAM:
```
developed by:S.Prema latha

reference number:22009393

import pandas as pd

df = pd.read_csv('data.csv')

print(df.head(10))

print(df.tail())

print(df.loc[[78,79,80,81],:])

print(len(df.axes[0]))

print(len(df.axes[1]))

## OUTPUT:
![Screenshot (49)](https://user-images.githubusercontent.com/120620842/214131567-63aee967-06d1-4379-9672-8a9dc441b7b6.png)


## RESULT:
A python program for reading content from a CSV file is written.
