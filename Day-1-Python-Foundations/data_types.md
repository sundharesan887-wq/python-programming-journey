# Data Type in Python

Think like this:

If a box contains water, books, or food…

we should know what is inside.

Same in Python.

Python needs to know:

- Is it a number?
- Is it text?
- Is it `True` or `False`?
- Is it decimal?

That is called a **data type**.

---

# 🎒 Simple Story

Imagine 4 boxes:

---

## Box 1 → Age

```python
age = 21
```

This stores a whole number

→ called:

# Integer (`int`)

---

## Box 2 → Height

```python
height = 5.8
```

This stores a decimal number

→ called:

# Float (`float`)

---

## Box 3 → Name

```python
name = "Sundhar"
```

This stores text

→ called:

# String (`str`)

---

## Box 4 → Student Status

```python
is_student = True
```

This stores True or False

→ called:

# Boolean (`bool`)

---

# 📚 The 4 Main Basic Data Types

| Data Type | Meaning | Example |
|---|---|---|
| int | Whole number | 10 |
| float | Decimal number | 5.5 |
| str | Text | "Hello" |
| bool | True or False | True |

These are the most important beginner data types.

---

# 🤖 Python Detects Automatically

You do **NOT** write:

```c
int age = 21;
```

Python automatically understands:

```python
age = 21
```

This is called:

# Dynamic Typing

Python is smart.

That’s why beginners love Python.

---

# ⚠️ Strings Need Quotes

Very important rule.

## Correct ✅

```python
name = "Sundhar"
```

## Wrong ❌

```python
name = Sundhar
```

Why?

Because without quotes, Python thinks it is a variable.

Not text.

Always use:

```python
" "
```

or

```python
' '
```

for strings.

---

# ✅ Boolean Means Yes or No

Example:

```python
is_raining = True
is_logged_in = False
```

This helps Python make decisions later using `if` conditions.

Like:

> If raining → take umbrella

Very useful.

---

# 🔍 How to Check Data Type

Use:

```python
type()
```

### Example

```python
age = 21
print(type(age))
```

### Output

```python
<class 'int'>
```

This tells us:

`age` is an integer.

---

# 💻 Example Program

```python
name = "Sundhar"
age = 21
height = 5.8
is_student = True

print(name)
print(age)
print(height)
print(is_student)
```

Simple and powerful.

---

# 🔄 Type Conversion (Changing Type)

Sometimes we change one type into another.

### Example

```python
age = "21"
```

This is text.

To make it a number:

```python
age = int(age)
```

Now it becomes integer.

Useful later for input.

---

# 📌 Common Type Conversion Functions

```python
int()
float()
str()
bool()
```

These are important.

Remember them.

---

# 🧠 Memory Trick

```text
int   → integer → whole number
float → decimal number
str   → string → text
bool  → boolean → True / False
```

---

# 📖 Summary

Data types help Python understand:

> What kind of information is stored

Without this,

Python gets confused.

With this,

Python works correctly.

---

# ⭐ One-Line Memory Trick

# Variable = Box  
# Data Type = What is inside the box

Remember this forever.

---

# 🧩 Practice Problem

## Problem Statement

Create 4 variables:

- your name (string)
- your age (integer)
- your height (float)
- are you a student? (boolean)

Then:

- Print all values
- Print the data type of each variable using `type()`

---

# 🖥 Example Input / Output

Example:

```python
Name: Sundhar
Age: 21
Height: 5.8
Student: True
```

And:

```python
<class 'str'>
<class 'int'>
<class 'float'>
<class 'bool'>
```

---

# 💡 Small Hint (Not Full Solution)

Use:

```python
name = "Sundhar"
print(type(name))
```

You will need:

- variables
- `print()`
- `type()`

That’s it.

---

# 🧠 Think Before Coding

Ask yourself:

- Which variable should use quotes?
- Which variable should NOT use quotes?
- Where should I use `True` or `False`?
- How do I check the type?

Think first.

Then code.

That is real programming.

---

# ⚠️ Tiny Reminder

This is correct:

```python
is_student = True
```

This is wrong:

```python
is_student = "True"
```

Because `"True"` is text (string)

but

`True` is boolean.

Very important difference.
