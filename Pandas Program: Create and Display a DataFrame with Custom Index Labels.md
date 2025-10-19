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
<img width="1133" height="749" alt="Screenshot 2025-10-19 130944" src="https://github.com/user-attachments/assets/e0721ed3-bbf8-429e-8dc8-ab4e3dcb81be" />

## Result
Thus, the program to join two Pandas DataFrames along rows was executed successfully.
