# Variables — The First Building Block of Python

Before writing big programs, we must understand the smallest building block:

## Variables

And we’ll learn it like a story.

---

# 🎒 Imagine This

You are going to school.

You carry:

- a school bag for books
- a water bottle for water
- a lunch box for food

Each thing has its own place.

Why?

Because if everything is mixed, life becomes confusing.

Programming works the same way.

We need places to store information.

Those places are called:

# Variables

---

# 🧠 What is a Variable?

A variable is like a named storage box.

It stores data so we can use it later.

### Example

You have a box labeled:

```text
AGE
```

Inside it:

```text
21
```

In Python:

```python
age = 21
```

This means:

> Create a box called `age` and store `21` inside it.

---

# 📦 Real-Life Example

```python
name = "Sundhar"
age = 21
dream_job = "AI Engineer"
```

Here:

- `name` stores text
- `age` stores a number
- `dream_job` stores text

Simple.

---

# ⚠️ Super Important Rule

This symbol:

```python
=
```

does **NOT** mean:

```text
equal to
```

here.

It means:

```text
assign
```

or

```text
put inside
```

### Example

```python
x = 10
```

This means:

> Put `10` inside `x`

NOT

> x is mathematically equal to 10

This is one of the biggest beginner mistakes.

Remember this forever.

---

# 🤖 Python Automatically Understands Data Types

This is called:

# Dynamic Typing

This means:

You do **NOT** need to write:

```c
int age = 21;
```

like in C or Java.

Python is smart.

It understands automatically.

### Example

```python
age = 21
name = "Sundhar"
height = 5.8
is_student = True
```

Python automatically knows:

- `21` → integer
- `"Sundhar"` → string
- `5.8` → float
- `True` → boolean

This is why Python is beginner-friendly.

---

# 🔄 Example from C vs Python

## In C

```c
int age = 21;
```

You must tell the type.

## In Python

```python
age = 21
```

Python understands by itself.

Less stress.

More focus on logic.

---

# 📛 Variable Naming Rules

There are important rules.

---

## Rule 1 — Cannot Start with Number

### Wrong ❌

```python
2name = "Rahul"
```

### Correct ✅

```python
name2 = "Rahul"
```

---

## Rule 2 — No Spaces Allowed

### Wrong ❌

```python
student name = "Sam"
```

### Correct ✅

```python
student_name = "Sam"
```

Use underscore `_`

---

## Rule 3 — Avoid Special Symbols

### Wrong ❌

```python
name@ = "Sam"
```

### Correct ✅

```python
name = "Sam"
```

Only:

- letters
- numbers
- underscore `_`

are safe.

---

## Rule 4 — Variable Names Should Be Meaningful

### Good ✅

```python
student_name
total_marks
phone_number
```

### Bad ❌

```python
a
x
abc123xyz
```

Good names make code easier to understand.

Even for future-you.

---

# 🔠 Python is Case Sensitive

This means:

```python
name
```

and

```python
Name
```

are **NOT** the same.

Python treats them as different variables.

### Example

```python
name = "Sundhar"
Name = "Rahul"
```

These are two different boxes.

Be careful.

---

# 🔁 Variables Can Change

That is why they are called **variables**

because values can vary.

### Example

```python
score = 50
score = 90
```

Now:

```python
score = 90
```

The old value is replaced.

Latest value wins.

---

# 🔢 Multiple Assignment

Python allows this:

```python
a, b, c = 10, 20, 30
```

This means:

```python
a = 10
b = 20
c = 30
```

Very useful.

---

# 📌 Same Value to Multiple Variables

```python
x = y = z = 100
```

Now all three contain:

```text
100
```

---

# 🗑 Deleting a Variable

You can remove a variable using:

```python
del age
```

Now Python forgets that variable.

(Not used much now, but good to know.)

---

# 🧠 Think Like This

Variables are like:

# labeled containers

Without labels → confusion

With labels → clarity

That is programming.

---

# 💡 Quick Example

```python
fruit = "Apple"
price = 50
quantity = 3
```

Now Python knows:

- what fruit
- what price
- how many

Very useful.

---

# 📚 Summary

Variables help us:

- store information
- reuse information
- update information
- make programs smarter

Without variables, programming becomes almost impossible.

They are the foundation of everything.

---

# ⭐ One-Line Memory Trick

# Variable = Named Box That Stores Data

Remember this forever.
