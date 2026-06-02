# Python Programming Fundamentals: Notes

Python programming relies on several core concepts for handling data, strings, and logical flow. Understanding how to manage variables and perform type casting is essential, as the `input()` function captures data as a string by default, requiring conversion using functions like `float()` or `int()` before performing any mathematical operations.

## String Manipulation
Strings in Python are immutable, meaning they cannot be modified once they are created, and any manipulation results in a new string. 

- **Length:** Use `len()` to get the number of characters.
- **Indexing:** Access characters using index `0` (first) to `-1` (last).
- **Slicing:** Use `text[start:stop]` to extract specific portions.
- **Methods:**
  - `.split()`: Converts text into a list of words.
  - `.upper()` / `.lower()`: Adjusts character casing.
  - `.center()`: Adds padding to align strings.
  - `.strip()`: Removes whitespace from ends.
  - `.join()`: Concatenates list elements into a single string.
- **Membership:** Verify substring existence using `in` or `not in`.

## Lists (Mutable Sequences)
Lists store collections of data and can be modified after creation.

| Method | Description |
| :--- | :--- |
| `.append(item)` | Adds item to the end. |
| `.extend(list)` | Merges another list into the current list. |
| `.insert(i, item)` | Adds item at index `i`. |
| `.pop()` | Removes and returns the last item. |
| `.clear()` | Empties the list. |
| `.copy()` | Creates a shallow copy. |
| `.index(item)` | Returns the position of an item. |

## Logic and Control Flow
Logical control flow is implemented through `if-else` statements, allowing code to execute based on conditions. These are often combined with mathematical calculations (e.g., comparing a calculated cost against a budget).