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
import numpy as np
arr = np.array(eval(input()))
new_col = np.array(eval(input()))
print("Printing Original array")
print(arr)
arr_deleted = np.delete(arr, 1, axis=1)
print("Array after deleting column 2 on axis 1")
print(arr_deleted)
arr_modified = np.insert(arr_deleted, 1, new_col, axis=1)
print("Array after inserting column 2 on axis 1")
print(arr_modified)


## Output

<img width="1137" height="690" alt="530465619-13c37e59-60fc-4d8c-b46f-786f5bf4f558" src="https://github.com/user-attachments/assets/9f95cbce-b5af-42a3-bbf2-fb92593e2225" />


## Result
Thus the python program for replacing column in numpy has been implemented and executed successfully.
