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
