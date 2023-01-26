# AIM:
To write a python program for reading content from a CSV file.

# ALGORITHM:
# Step 1:
Import pandas as pd.

# Step 2:
Read the CSV file using read_csv method.

# Step 3:
Use head and tail method to get the required contents from the file.

# Step 4:
Use len() method to get the number of rows and columns.

# Step 5:
Print the output.

# PROGRAM:
```
# Developed by: Rajesh A
# Register Number: 22008551
```
```
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
# OUTPUT:
![1da00344-fac4-40d4-953e-35181c954fba](https://user-images.githubusercontent.com/118924713/214759530-cf3213e3-6d8a-4e03-bade-72f92bcf383d.jpg)

# RESULT:
Thus a python program is written to read the contents of a CSV file.
