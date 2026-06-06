# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program

```
import numpy as np
arr=np.array(eval(input()))
new_arr=np.sort(arr, axis=0)
print("Original:")
print(arr)
print("Sorted:")
print(new_arr)
```

## Output

<img width="909" height="492" alt="image" src="https://github.com/user-attachments/assets/560cfe3b-6279-4285-98af-726e1d2856cb" />

## Result

The **NumPy** program that sorts the elements in each column of a given 2D array in ascending order is successfully developed and executed.

# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program

```
import numpy as np
x=np.array([1,2,3,4,56,89,78,43,56])
y=np.array([3,2,4,1,6,87,87,43,24])
print(x>y)
print(x==y)
indices=np.where(x>=y)
print(indices)
```

## Output

<img width="914" height="308" alt="image" src="https://github.com/user-attachments/assets/bcd3e2d9-6873-47c7-9586-96f9b2054c8f" />


## Result

The Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y` is successfully developed and executed.

# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program

```
import numpy as np
arr=np.array(eval(input()))
col=np.array(eval(input()))
arr_del=np.delete(arr, 1, axis=1)
arr_ins=np.insert(arr_del, 1, col, axis=1)
print("Original Array:")
print(arr, end="\n")
print("Column to insert:")
print(col, end="\n")
print("Deleted:")
print(arr_del, end="\n")
print("Inserted:")
print(arr_ins)
```

## Output

<img width="908" height="709" alt="image" src="https://github.com/user-attachments/assets/ca56d16b-92e8-43f9-8b83-72cbd6a84662" />


## Result

 The **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position is developed and executed successfully.

 # Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program

```
import pandas as pd
import numpy as np
exam_data={'name':['Rahul','Kalyan','Prabhu','Vishnu'],'score':[89,78,90,68],'attempts':[1,1,1,2],'qualify':['pass', 'pass', 'pass','pass']}
labels=[1,2,3,4]
df=pd.DataFrame(exam_data,index=labels)
print(df)
```

## Output

<img width="908" height="400" alt="image" src="https://github.com/user-attachments/assets/7ec2d316-155c-4949-b0d4-62b18aaa6401" />

## Result

The **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows is created and displayed successfully.

# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program

```
import pandas as pd
student_data1={'name':['Payal','Pankaj','Piyush'], 'Score': [100,100,99], 'Rank': [2,1,4]}
df1=pd.DataFrame(student_data1)
student_data2={'name':['Pawan','Pavithra', 'Pathra'], 'Score':[98,97,99], 'Rank':[8,13,5]}
df2=pd.DataFrame(student_data2)
res=pd.concat([df1,df2],axis=0)
print(res)
```

## Output

<img width="910" height="477" alt="image" src="https://github.com/user-attachments/assets/e43c0f0f-0179-42b2-abcc-c0df79fd29a1" />

## Result

The Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame is successfully developed and executed.
