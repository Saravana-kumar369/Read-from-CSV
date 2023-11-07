# Read-from-CSV

## AIM:
To write the python program for reading the content of CSV file

## ALGORITHM:
### Step 1:
start the program

### Step 2:
import pandas

### Step 3:
mention the csv file to be read

### Step 4:
read the content of the file using df.read function

### Step 5:
End the program

## PROGRAM:
```
import pandas as pd
f=pd.read_csv('/content/nba.csv')
print(f.head(10))
print(f.tail())
print('Row :',len(f.axes[0]))
print('Column :',len(f.axes[1]))
print(f.head())
```

## OUTPUT:
![image](https://github.com/Saravana-kumar369/Read-from-CSV/assets/117925254/fe8d8cc9-4083-4875-a9ee-25688642d094)

## RESULT:
Thus the program to read content of csv file executed successfully.
