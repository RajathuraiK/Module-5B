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
