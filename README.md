# Read-from-CSV

## AIM:
To write a python program for reading the csv file content.

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of rows returned is defined in Pandas option settings.

### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.


## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by : Pradeep Kumar.G
#Register Number: 212223230150
```
```
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:

![Screenshot 2024-05-14 163651](https://github.com/pradeep23014186/Read-from-CSV/assets/152294642/8a4c0cf5-fb99-44d9-b58e-e5f7b0ef2366)

![329157586-79637654-8062-4049-9ea8-4518f5b9fec6](https://github.com/KrishnaPrasad148/Read-from-CSV/assets/147332763/a624c2e7-e942-4430-a65c-f59e8997a36c)


## RESULT:
Thus the program is written to read the csv file.
