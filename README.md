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

df = pd.read_csv('nba.csv')
print(df.head())
print(df.tail())
print("Column",len(df.axes[0]))
print("Rows",len(df.axes[1]))
```

## OUTPUT:

![Screenshot (113) (2)](https://user-images.githubusercontent.com/120620842/214818716-5b93cffa-454c-4732-bc88-68d31050f411.png)


## RESULT:
A python program for reading content from a CSV file is written.
