### Python Basics Glossary

#### Terms and Concepts

- **AI (Artificial Intelligence)**: Ability of digital systems to perform tasks commonly associated with intelligent beings.
- **Application Development**: Process of planning, designing, creating, testing, and deploying software applications.
- **Arithmetic Operations**: Basic calculations like addition, subtraction, multiplication, and division.
- **Array of Numbers**: Ordered set of numbers or objects.
- **Assignment Operator in Python**: `=` used to assign values to variables.
- **Asterisk `*`**: Symbol for multiplication in Python.
- **Backslash `\`**: Used to introduce escape sequences in strings.
- **Boolean**: A data type that can be either `True` or `False`.
- **Colon `:`**: Used to represent an indented block or slicing in Python.
- **Concatenate**: Link things together in a chain or series.
- **Data Engineering**: Process of turning raw data into useful information.
- **Data Science**: Field focused on extracting knowledge from data using scientific methods.
- **Data Type**: Defines the type of value a variable can hold, e.g., integer, float, string.
- **Double Quote `"`**: Used to represent strings in Python.
- **Escape Sequence**: Combination of characters starting with `\` to represent special characters.
- **Expression**: Combination of values and operators that evaluates to a single value.
- **Float**: Data type for floating-point numbers.
- **Floor Division `//`**: Division that returns the largest integer less than or equal to the division result.
- **Immutable**: Objects whose state cannot be modified after creation.
- **Indexing**: Accessing elements of a sequence using their position.
- **Integer**: Whole numbers without decimal points.
- **Manipulate**: Modifying a string or creating a new string by combining strings.
- **Mathematical Conventions**: Standard rules for performing mathematical operations.
- **Negative Indexing**: Accessing elements from the end of a sequence.
- **Operands**: Values on which an operation is performed.
- **Operators in Python**: Symbols used for performing operations on variables and values.
- **Parentheses `()`**: Used to call a function or define a tuple.
- **Replicate**: Duplicate a string multiple times.
- **Sequence**: Ordered collection of items.
- **Single Quote `'`**: Used to represent strings in Python.
- **Slicing in Python**: Extracting a portion of a sequence.
- **Special Characters**: Characters with special meanings, e.g., `\n` for a new line.
- **Stride**: Step value for slicing sequences.
- **Strings**: Sequence of characters enclosed in quotes.
- **Substring**: Portion of a string.
- **Type Casting**: Converting a value from one data type to another.
- **Variables in Python**: Containers for storing data values.

#### Python Code Examples

- **Comments**:
  ```python
  # This is a comment
  ```

- **Concatenation**:
  ```python
  result = "Hello" + " John"
  ```

- **Data Types**:
  ```python
  x = 7       # Integer
  y = 3.14    # Float
  is_valid = True  # Boolean
  name = "John"    # String
  ```

- **Indexing**:
  ```python
  my_string = "Hello"
  char = my_string[0]  # Access first character
  ```

- **len()**:
  ```python
  length = len(my_string)  # Returns the length of a string
  ```

- **lower()**:
  ```python
  lowercase_text = my_string.lower()  # Converts string to lowercase
  ```

- **print()**:
  ```python
  print("Hello, World!")
  ```

- **Python Operators**:
  ```python
  x = 9 + 4      # Addition
  result_sub = x - y  # Subtraction
  result_mul = x * y  # Multiplication
  result_div = x / y  # Division (float)
  result_fdiv = x // y  # Floor Division
  result_mod = x % y  # Modulus
  ```

- **replace()**:
  ```python
  new_text = my_string.replace("Hello", "Hi")  # Replaces substring
  ```

- **Slicing**:
  ```python
  substring = my_string[0:5]  # Extracts a portion of the string
  ```

- **split()**:
  ```python
  split_text = my_string.split(",")  # Splits string into a list based on a delimiter
  ```

- **strip()**:
  ```python
  trimmed = my_string.strip()  # Removes leading/trailing whitespace
  ```

- **upper()**:
  ```python
  uppercase_text = my_string.upper()  # Converts string to uppercase
  ```

- **Variable Assignment**:
  ```python
  name = "John"
  x = 5
  ```

### Lists and Tuples

- **List**: Ordered, mutable collection of items.
  ```python
  L = ["Michael Jackson", 10.1, 1982]
  ```

- **Tuple**: Ordered, immutable collection of items.
  ```python
  T = ("Michael Jackson", 10.1, 1982)
  ```

- **Indexing in Lists and Tuples**:
  ```python
  first_element = L[0]
  last_element = T[-1]
  ```

- **List Operations**:
  ```python
  L.extend(['pop', 10])  # Adds elements to the list
  L.append(['a', 'b'])   # Appends a list as an element
  L[0] = 'hard rock'     # Modifies an element
  del(L[0])              # Deletes an element
  ```

- **Slicing in Lists and Tuples**:
  ```python
  sublist = L[3:5]  # Extracts a portion of the list
  ```

- **List Methods**:
  ```python
  L = ["Michael Jackson", 10.2]
  L.extend(['pop', 10])  # Extends list
  L.append(['a', 'b'])   # Appends to list
  ```

- **Cloning Lists**:
  ```python
  B = A[:]  # Creates a clone of list A
  ```

### Additional Concepts

- **Data Manipulation**: Creating or modifying data using lists and tuples.
- **Immutable Objects**: Objects that cannot be changed after creation.
- **Nested Structures**: Lists or tuples containing other lists or tuples.
- **Escape Sequences**: Special characters for formatting strings, e.g., `\n` for new line, `\t` for tab.
- **Aliasing**: Multiple variables referencing the same object.

This complete glossary covers the foundational concepts, terms, and necessary Python code examples to help you understand and implement the material effectively.