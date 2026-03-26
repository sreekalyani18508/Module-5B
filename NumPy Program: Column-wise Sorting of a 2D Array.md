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
arr = np.array(eval(input()))
print("Given array")
print("",arr)
sorted_arr = np.sort(arr, axis=0)
print("")
print(sorted_arr)
```


## Output


<img width="873" height="537" alt="530464995-c2489602-6fb7-4b21-a925-922f5bcd9027" src="https://github.com/user-attachments/assets/1bab76b6-a41f-4fd8-b63e-1fc0daf280f8" />


## Result
Thus the python program for sorting each column in numpy has been implemented and executed successfully.
