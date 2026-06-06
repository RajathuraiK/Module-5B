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
