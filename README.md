# Python List Duplicate Removal

A simple Python program that removes repeated elements from a list while maintaining the order of their first occurrence.

## Overview

This project demonstrates how to work with Python lists to identify and remove duplicate values without using additional libraries or built-in shortcuts such as `set()`.

The program iterates through the original list, checks whether each element is already present in a new list, and appends only those elements that have not been added before.

## Features

- Removes duplicate elements from a list.
- Preserves the original order of elements.
- Retains the first occurrence of each value.
- Uses basic Python list operations and conditional logic.
- Implements the solution without external libraries.

## Python Concepts Covered

- Lists
- For Loops
- Conditional Statements
- Membership Operators (`in`, `not in`)
- List Traversal
- `append()` Method
- Basic Data Handling

## Code

```python
# ---------- B1: remove the repeats ----------

items = [3, 1, 3, 2, 1, 5, 2]
unique = []

for i in items:
    if i not in unique:
        unique.append(i)

print(unique)
```

## Sample Output

```text
[3, 1, 2, 5]
```

## How It Works

1. An original list is created containing repeated values.
2. An empty list named `unique` is initialized to store distinct elements.
3. A `for` loop traverses each element in the original list.
4. The `not in` operator checks whether the current element already exists in `unique`.
5. If the element is not present, it is appended to the new list.
6. The final list is printed without repeated elements.

## Complexity Analysis

| Complexity | Explanation |
|---|---|
| Time | O(n²) in the worst case |
| Space | O(n) for the additional list |

The membership check may scan the new list for each element, resulting in quadratic worst-case time complexity.

## Key Takeaway

This exercise demonstrates a straightforward approach to removing duplicates from a Python list while preserving insertion order, using fundamental programming concepts.

## Project Information

**Project:** Python List Duplicate Removal  
**Language:** Python 3  
**Level:** Beginner  
**Category:** List Operations  
**Status:** Completed

---

*Part of a collection of Python programming exercises focused on developing problem-solving skills and understanding core programming concepts.*

## About me

**Rammal Ahmed**

**AI & Data Science Enthusiast** | **Microsoft Dynamics 365 CRM Developer** | **Power Platform** | **UI/UX Designer** | **Graphic Designer & Illustrator**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/rammal-ahmed-58184b325)
[![GitHub](https://img.shields.io/badge/GitHub-Rammal--Ahmed-181717?style=flat&logo=github)](https://github.com/Rammal-Ahmed)

<div align="center">

If you found this useful, consider giving it a star ⭐

**I truly value your feedback and welcome any suggestions for improvement**

**Always open to fresh perspectives, constructive feedback, and new ideas**


## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details

---

*Developed as part of my Python programming practice*

---

**Project Status:** Completed

</div>
