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
