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

import pandas as pd
data1 = {
    'student_id': ['S1', 'S2', 'S3', 'S4', 'S5'],
    'name': ['Danniella Fenton', 'Ryder Storey', 'Bryce Jensen', 'Ed Bernal', 'Kwame Morin'],
    'marks': [200, 210, 190, 222, 199]
}
df1 = pd.DataFrame(data1)
data2 = {
    'student_id': ['S4', 'S5', 'S6', 'S7', 'S8'],
    'name': ['Scarlette Fisher', 'Carla Williamson', 'Dante Morse', 'Kaiser William', 'Madeeha Preston'],
    'marks': [201, 200, 198, 219, 201]
}
df2 = pd.DataFrame(data2)
print("Original DataFrames:")
print(df1)
print(df2)
merged_df = pd.merge(df1, df2, on='student_id', how='inner')
print("Merged data (inner join):")
print(merged_df)
## Output

<img width="1133" height="490" alt="530466191-8a407a0c-062a-461a-821a-29abc7ffa5bd" src="https://github.com/user-attachments/assets/d1f65c17-f7f9-47b6-a5bf-dd157aa5a318" />



<img width="517" height="502" alt="530466228-7dd5d93b-308d-49b6-89ef-3e1925551480" src="https://github.com/user-attachments/assets/2f2e0107-0ede-4fc5-9427-5d097c224ea8" />



<img width="1151" height="531" alt="530466253-20b45738-2fb1-4820-8f89-6a9f0c3caa6a" src="https://github.com/user-attachments/assets/04a569ea-972c-4c2d-b00a-a0f4072ca33e" />



##Result
Thus, the Python program has been successfully created and executed successfully to join the two DataFrames row-wise using pd.concat() and all records from both DataFrames were included in the final output .
