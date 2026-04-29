# Input and Output in Python

# 🎤 Simple Story

Imagine this:

You ask your friend:

```text
What is your name?
```

Your friend replies:

```text
Rahul
```

You gave:

# Input

Your friend gave:

# Output

Python works the same way.

---

# 🖥 What is Output?

Output means:

> Showing something to the user

Python uses:

```python
print()
```

### Example

```python
print("Hello World")
```

### Output

```text
Hello World
```

This is Python speaking.

---

# ⌨️ What is Input?

Input means:

> Taking something from the user

Python uses:

```python
input()
```

### Example

```python
name = input("Enter your name: ")
print(name)
```

If user types:

```text
Sundhar
```

### Output

```text
Sundhar
```

This is Python listening.

---

# ⚠️ Very Important Rule

```python
input()
```

always gives:

# String (`str`)

Always.

Even if user enters:

```text
21
```

Python treats it like:

```python
"21"
```

which is text.

Not number.

This is VERY important.

---

# 🧪 Example Problem

```python
age = input("Enter age: ")
print(type(age))
```

### Output

```python
<class 'str'>
```

See?

Even `age` becomes string.

---

# 🔄 How to Convert Input into Number

Use:

# Type Conversion

### Example

```python
age = int(input("Enter age: "))
```

Now Python converts text into integer.

Very important for math problems.

---

# 📏 Example with Float

```python
height = float(input("Enter height: "))
```

Now it becomes decimal.

---

# 💻 Example Program

```python
name = input("Enter your name: ")
age = int(input("Enter your age: "))

print("Name:", name)
print("Age:", age)
```

Simple and powerful.

---

# 🤔 Why Input Matters

Without input,

programs are boring.

With input,

programs become interactive.

Apps, websites, games—

all use input.

---

# 🧠 Memory Trick

```text
input() → Python listens
print() → Python speaks
```

Remember this forever.

---

# 📚 Summary

| Function | Purpose |
|---|---|
| print() | Show output |
| input() | Take input |
| int() | Convert to integer |
| float() | Convert to decimal |

These are super important.

Master them.

---

# 🧩 Practice Problem — Level 1

## Problem Statement

Ask the user for:

- name
- age
- dream job

Then print:

```text
Hello <name>
You are <age> years old
Your dream job is <dream job>
```

---

# 🖥 Example Input / Output

### Example

```text
Enter your name: Sundhar
Enter your age: 21
Enter your dream job: AI Engineer
```

### Output

```text
Hello Sundhar
You are 21 years old
Your dream job is AI Engineer
```

---

# 💡 Small Hint (Not Full Solution)

Use:

```python
name = input("Enter your name: ")
print(name)
```

You will need:

- `input()`
- `print()`
- variables

That’s it.

---

# ⚡ Mini Challenge

Add one more input:

# favorite programming language

and print it too.

Small upgrade.

Better learning.
