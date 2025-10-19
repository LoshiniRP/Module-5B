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
student_data1 = pd.DataFrame(eval(input()))
student_data2 = pd.DataFrame(eval(input()))
print("Original DataFrames:")
print(student_data1)
print("-------------------------------------")
print(student_data2)
print()
result_data = pd.concat([student_data1,student_data2], axis=0)
print("Join the said two dataframes along rows:")
print(result_data)
```

## Output
<img width="1133" height="749" alt="Screenshot 2025-10-19 130944" src="https://github.com/user-attachments/assets/028f467e-5fb8-4368-b6b0-63d0e1271bdb" />

## Result
Thus, the program to join two Pandas DataFrames along rows was executed successfully.
