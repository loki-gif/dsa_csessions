### For Loops
A `for` loop is ideal for iterating over a sequence (like a range or a string).

* **`range(start, stop, step)`**: Generates a sequence of numbers.
    * `range(n)`: 0 to n-1.
    * `range(start, stop, step)`: Specifies start, end, and increment.
* **Loop Control Statements:**
    * `break`: Exits the loop entirely.
    * `continue`: Skips the current iteration and moves to the next.
    * `pass`: Does nothing; used as a placeholder.

[Image of Python loop control flow break and continue]

## 2. Functions

Functions allow you to organize code into reusable blocks.

* **Defining a Function:**
    ```python
    def function_name(parameters):
        # code
        return value
    ```
* **Key Concepts:**
    * **Arguments & Return:** Functions can accept input values (parameters) and return a computed result using `return`.
    * **No Argument/Return:** Functions can also simply perform actions (like printing) without taking inputs or returning values.
    * **Reusability:** Once defined, functions can be called multiple times throughout a program.

## 3. Practical Usage
* **Calculations:** Functions are often used to encapsulate mathematical logic, such as performing arithmetic (`sum`, `sub`, `mul`, `div`) or complex operations like squaring the result of a sum.
* **User Input:** Functions can incorporate `input()` to allow dynamic interaction, making them highly flexible for different use cases.