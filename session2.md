Tuples, Dictionaries, and Control Flow: Notes

This guide covers advanced data structures like tuples and dictionaries, along with conditional logic in Python, based on the provided practice problems.

## 1. Tuples
Tuples are **immutable** sequences. Once created, their elements cannot be changed directly.

* **Conversion:** To modify a tuple, convert it to a list using `list()`, modify the list, and then convert it back using `tuple()`.
* **Operations:** You can concatenate tuples using `+` and check for membership using the `in` operator.

## 2. Dictionaries
Dictionaries store data in `key:value` pairs. They are mutable and highly versatile.

* **Accessing Data:** Use `movie['key']` to access values or `.get('key')` to retrieve a value safely (returns `None` if the key is missing).
* **Adding/Updating:** Use `movie['key'] = 'value'` or `.update({'key':'value'})` to add or modify items.
* **Removing Data:**
    * `.pop('key')`: Removes a specific key.
    * `.popitem()`: Removes the last inserted item.
* **Views:**
    * `.keys()`: Returns all keys.
    * `.values()`: Returns all values.
    * `.items()`: Returns key-value pairs as tuples.
* **Nested Dictionaries:** Dictionaries can contain other dictionaries (e.g., `prime_movies["Avengers"]["cast"]`).

## 3. Conditional Statements
Conditionals allow the program to make decisions based on defined logic.

* **Syntax:**
    ```python
    if condition:
        # code
    elif condition:
        # code
    else:
        # code
    ```
* **Nested Conditionals:** You can place `if-else` statements inside other `if-else` blocks to handle complex scenarios (e.g., grading logic based on both marks and CGPA).

## 4. Shorthand Conditionals (Ternary Operators)
Python allows for concise conditional assignments:

* **Simple:** `value = "A" if condition else "B"`
* **Chained:** `result = "A" if cond1 else "B" if cond2 else "C"`

[Image of Python dictionary data structure]