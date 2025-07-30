Here is a **brief but complete syllabus** covering:

* **Module 1: Python Syntax and Structure**
* **Module 2: Variables and Data Types**
* **Module 3: Operators**

It is structured **topic by topic (A-Z)**, with concise explanations to serve as a solid reference for learning or teaching.

---

# 🧩 Python Basics - Module 1 to Module 3

---

## 🔹 1 Python Syntax and Structure

### 1.1 Indentation
- Python uses **indentation instead of braces** `{}` to define blocks.
- Standard is **4 spaces** per indent level.
- Indentation is **mandatory** and defines **code structure** (functions, loops, conditionals).

### 1.2 Comments
- **Single-line comment**: starts with `#`
- **Multi-line comment**: enclosed in triple quotes `''' ... '''` or `""" ... """` (used mainly for docstrings)

### 1.3 Python Statements
- **Simple Statement**: `x = 5`
- **Multi-line Statement**: Use `\` or parentheses
  ```python
  total = (1 +
           2 +
           3)
```
* **Compound Statement**: `if`, `for`, `while`, etc., with a colon `:` and indented block

---

## 🔹 Module 2: Variables and Data Types

### 2.1 Variables

#### 2.1.1 Declaring Variables

* No keyword required. Assign directly:

  ```python
  name = "Alice"
  age = 25
  ```

#### 2.1.2 Naming Rules

* Must start with a **letter** or `_`
* Can include letters, numbers, underscores
* **Case-sensitive**
* Avoid keywords like `if`, `for`, `class`, etc.

#### 2.1.3 Dynamic Typing

* Variable types are **automatically inferred**:

  ```python
  x = 10        # int
  x = "hello"   # now str
  ```

### 2.2 Data Types

#### 2.2.1 Numbers

* **int**: Integer values (`42`)
* **float**: Decimal values (`3.14`)
* **complex**: Complex numbers (`3 + 4j`)

#### 2.2.2 Strings

* Defined with `'`, `"`, `'''`, or `"""`
* Immutable sequences of characters
* String operations: indexing, slicing, concatenation, formatting

#### 2.2.3 Booleans

* `True` and `False`
* Used in conditionals and comparisons

#### 2.2.4 NoneType

* `None` is a special type representing **no value**

#### 2.2.5 Type Conversion (Casting)

* Convert types using `int()`, `float()`, `str()`, `bool()`

  ```python
  int("5") → 5
  float(3) → 3.0
  ```

#### 2.2.6 `type()` and `isinstance()`

* `type(x)` returns type of variable
* `isinstance(x, type)` checks if x is an instance of the type

---

## 🔹 Module 3: Operators

### 3.1 Arithmetic Operators

* `+`, `-`, `*`, `/`, `//` (floor division), `%` (modulo), `**` (exponent)

### 3.2 Comparison Operators

* `==`, `!=`, `>`, `<`, `>=`, `<=`
* Used to compare values, returns `True` or `False`

### 3.3 Logical Operators

* `and`: True if both are true
* `or`: True if at least one is true
* `not`: Inverts the boolean value

### 3.4 Assignment Operators

* `=`, `+=`, `-=`, `*=`, `/=`, `//=`, `%=`, `**=`

### 3.5 Bitwise Operators

* `&` (AND), `|` (OR), `^` (XOR), `~` (NOT), `<<` (left shift), `>>` (right shift)
* Operate on binary values of integers

### 3.6 Membership Operators

* `in`, `not in`

  ```python
  'a' in 'apple' → True
  ```

### 3.7 Identity Operators

* `is`, `is not`
* Checks if two variables point to the **same object in memory**

  ```python
  a = [1, 2]
  b = a
  a is b → True
  ```

---