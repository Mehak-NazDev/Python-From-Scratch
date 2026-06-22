# My Python Learning Journey - Research Notes

## Day 1: Foundations

* **F-strings:** The f strings  (`f"..."`) must have the `f` character attached directly to the opening quote. Adding a space causes a syntax error.
    ```Why: The `f` is a modifier/prefix, not a separate word.
       Observation: F-strings are great for string interpolation. They automatically handle both integers and strings inside the `{}`.```

* **Case Sensitivity:** Python treats `name` and `Name` as two completely different buckets. Never confuse them.

* **Overwriting:** If you assign a new value to an old variable name (e.g., x = 5 then x = 10), the old value (5) is gone forever.

* **Type Mismatch:** You cannot "add" a word (string) to a number (integer) using +.
  
    ```The Fix: Either convert the number to text using str(age) or use an f-string to display them together.```

* **Git Commitment:** A "commit" is just a save-point for your project. A good commit message describes exactly what you did so you don't have to guess later
---

## Day 2 

* **The Scope Isolation Rule:** Variables created inside a function are "trapped" in that function (local); they cannot change or overwrite the original variables outside (global) unless you explicitly use the `global` keyword.
  
* **Definition vs. Execution:** Defining a function (`def my_func():`) only prepares the instruction set in memory; you must "call" the function (`my_func()`) to actually execute the code.
  
* **The Print Dependency:** A function does not automatically display its results; if there is no `print()` statement *inside* the function, you must capture or print the function's outcome *after* it has been called to see any output.
---

## Day 3

Atomic vs. Container Types: Distinguish between Atomic Data Types (int, float, str, bool, None) which represent a single value, and Data Structures (list, tuple, dict, set) which are containers designed to organize multiple atoms.

The Power of Methods: Python objects have built-in "superpowers." Instead of doing everything manually (like hand-counting string indices), use built-in methods like .split(), .append(), or .add() to perform complex tasks cleanly.

The "Everything is an Object" Secret: Every data type in Python is an object. Using dir() reveals that even simple numbers have hidden methods (like __add__), confirming that math in Python is actually the execution of object-based commands. 
