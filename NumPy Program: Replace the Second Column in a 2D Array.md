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

original_array = np.array([[10, 20, 30], 
                           [40, 50, 60], 
                           [70, 80, 90]])

new_column = np.array([100, 200, 300])

temp_array = np.delete(original_array, 1, axis=1)

final_array = np.insert(temp_array, 1, new_column, axis=1)

print("Original Array:")
print(original_array)

print("\nNew Column to Insert:")
print(new_column)

print("\nUpdated Array (Second Column Replaced):")
print(final_array)
```

## Output

<img width="732" height="367" alt="image" src="https://github.com/user-attachments/assets/69f4c589-263f-407c-b5cd-06b4f87dac91" />


## Result
Thus,the program has been executed successfully.
