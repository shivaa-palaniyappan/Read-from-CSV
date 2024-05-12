# EXP-12 Read-from-CSV
## AIM:
To write a python program for reading the csv file content
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
#Developed by: SHIVAA PALANIYAPPAN V
#Register Number: 212223110050

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![329831963-e25906fa-4d4b-4a3b-9c66-f7f590d7cacc](https://github.com/shivaa-palaniyappan/Read-from-CSV/assets/146915611/722214f7-2fd8-44a0-964d-8751f8af052b)

## RESULT:
Thus the program is written to read the csv file.
