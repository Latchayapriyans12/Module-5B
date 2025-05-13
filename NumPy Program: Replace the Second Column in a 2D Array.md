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

a = np.array(eval(input())
new_col = np.array(eval(input()

a = np.delete(a, 1, axis=1)
a = np.insert(a, 1, new_col, axis=1)

print(a)
```

## Output
![image](https://github.com/user-attachments/assets/f0a45e07-b887-4591-afbf-fb6fc6a3dcc5)


## Result
Thus, the program has been successfully executed.
