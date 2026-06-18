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
