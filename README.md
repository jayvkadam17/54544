Q1. What is a set in Python?
- A set in Python is an unordered collection of unique elements. It is a built-in data type that is used to store multiple items in a single variable. Sets are mutable, meaning you can add or remove elements from them.

Q2. How do you create a set in Python?
- There are multiple ways to create a set in Python:
  1. Using curly braces `{}`:
     ```python
     my_set = {1, 2, 3}
     ```

  2. Using the `set()` constructor:
     ```python
     my_set = set([1, 2, 3])
     ```

Q3. How do you add elements to a set in Python?
- You can add elements to a set in Python using the `add()` method. The `add()` method takes a single element as an argument and adds it to the set.
  ```python
  my_set = {1, 2, 3}
  my_set.add(4)
  ```

Q4. How do you remove elements from a set in Python?
- There are multiple methods to remove elements from a set in Python:
  - Using the `remove()` method: The `remove()` method removes a specified element from the set. If the element is not present in the set, it raises a `KeyError`.
    ```python
    my_set = {1, 2, 3}
    my_set.remove(2)
    ```

  - Using the `discard()` method: The `discard()` method removes a specified element from the set. If the element is not present in the set, it does nothing.
    ```python
    my_set = {1, 2, 3}
    my_set.discard(2)
    ```

Q5. How do you get the length of a set in Python?
- You can get the length (number of elements) of a set in Python using the `len()` function. The `len()` function returns the number of elements present in the set.
  ```python
  my_set = {1, 2, 3}
  length = len(my_set)
  ```
