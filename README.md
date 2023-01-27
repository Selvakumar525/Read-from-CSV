# Read-from-CSV

## AIM:
To develop a python program to read a file rom csv.
## ALGORITHM:
### Step 1:
Import the pandas function as pd.
### Step 2:
Read the file and store it in the variable f.
### Step 3:
Print the head and tail.
### Step 4:
Print the number of rows using the length function(len).
### Step 5:
Print the number of coloumns using the same length function(len).
## PROGRAM:
```
import pandas as pd
f=pd.read_csv('cars.csv')
print(f.head(10))
print(f.tail())
print("Row:",len(f.axes[0]))
print("Col:",len(f.axes[1]))
```
## OUTPUT:
![Screenshot_20230127_210355](https://user-images.githubusercontent.com/120643262/215125101-4ccb81fe-1615-470f-8b41-b19b3346c0b2.png)


## RESULT:
Thus the program is successfully executed.
