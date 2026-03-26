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

original_array = np.array([[30, 10, 20],
                           [5,  45, 15],
                           [25, 5,  35]])
                           
sorted_array = np.sort(original_array, axis=0)

print("Original Array:")
print(original_array)

print("\nColumn-wise Sorted Array (Ascending):")
print(sorted_array)
```
## Output

<img width="561" height="289" alt="image" src="https://github.com/user-attachments/assets/d6fb2834-833c-4c39-9de1-2fe9b7d9cef9" />

## Result
Thus,the program has been executed successfully.
