# Lambda Functions and Object-Oriented Programming (OOP): Notes

This guide covers Lambda functions, advanced functional programming tools, and OOP concepts in Python based on the provided practice problems.

## 1. Lambda Functions
Lambda functions are small, anonymous, one-line functions defined without the `def` keyword.

* **Syntax:** `lambda arguments : expression`
* **Use Cases:**
    * **Mapping:** Transforming items in a list (e.g., `map(lambda x: x*x, numbers)`).
    * **Filtering:** Extracting items based on a condition (e.g., `filter(lambda x: x%2 == 0, numbers)`).
    * **Concise Logic:** Inline calculations or conditional returns.

## 2. Advanced Functional Tools
* **`map(function, iterable)`:** Applies a function to all items in an input list.
* **`filter(function, iterable)`:** Filters the list based on a function that returns `True` or `False`.
* **`zip(list1, list2)`:** Combines two lists into a list of tuples (pairs).
* **List Comprehensions:** A shorthand for creating lists based on existing lists (e.g., `[num * num for num in numbers]`).

## 3. Object-Oriented Programming (OOP)
OOP organizes code into reusable structures called classes.

* **Class & Objects:** A class is a blueprint; an object is an instance of that class.
* **`__init__` (Constructor):** A special method used to initialize an object's attributes when it is created.
* **`self`:** Represents the current instance of the class, allowing access to attributes and methods.
* **Inheritance:** Allows a class (child) to derive attributes and methods from another class (parent).
    * **`super()`:** Used to call methods from the parent class (e.g., calling the parent's `__init__` or `withdraw` methods).
* **Encapsulation & Logic:** Methods within a class can handle complex internal logic (e.g., checking for insufficient balance in a `BankAccount` class before performing a withdrawal).

## 4. Key OOP Concepts Demonstrated
* **Modularity:** Using methods like `deposit` and `withdraw` to manage object state.
* **Extensibility:** `SavingsAccount` inheriting from `BankAccount` to add specific features like `interest_rate` and `min_balance` requirements while reusing existing deposit/withdraw logic.