# Conditions in Python

Because computers must make decisions.

Just like humans.

# 🚦 Simple Story

Imagine you are standing at a traffic signal.

You think:

```text
If green light → go

Else → stop
```

This is called:

# Decision Making

Python also makes decisions like this.

This is done using:

```python
if
elif
else
```

---

# ☔ Real-Life Example

You look outside.

You think:

```text
If raining → take umbrella

Else → go normally
```

That is exactly how conditions work in Python.

---

# 📌 Basic Syntax

```python
age = 18

if age >= 18:
    print("You can vote")
```

Read it like:

> If age is greater than or equal to 18, print this

---

# ⚠️ Very Important Rule

Notice this:

```python
:
```

Colon is required.

And also:

# Indentation

This space matters:

```python
if age >= 18:
    print("Allowed")
```

The space before `print()` is very important.

Python uses indentation to understand blocks.

No proper space = error.

Very important.

---

# 1️⃣ if Statement

Used when we check one condition.

### Example

```python
marks = 90

if marks >= 50:
    print("Pass")
```

---

# 2️⃣ if else Statement

Used when there are two choices.

### Example

```python
age = 15

if age >= 18:
    print("Adult")
else:
    print("Minor")
```

Python chooses one path.

---

# 3️⃣ if elif else Statement

Used when there are multiple choices.

### Example

```python
marks = 75

if marks >= 90:
    print("Grade A")

elif marks >= 75:
    print("Grade B")

else:
    print("Grade C")
```

This is used a lot in real programs.

---

# 📚 Comparison Operators Used Here

Conditions usually use:

| Operator | Meaning |
|---|---|
| == | equal to |
| != | not equal |
| > | greater than |
| < | less than |
| >= | greater than or equal |
| <= | less than or equal |

These are very important.

---

# 💡 Example — Even or Odd

```python
num = int(input("Enter number: "))

if num % 2 == 0:
    print("Even")
else:
    print("Odd")
```

Very famous beginner problem.

Why?

Because:

```python
% 2
```

checks remainder.

If remainder is 0 → even

else → odd

---

# 🔗 Logical Operators with Conditions

We can also use:

```python
and
or
not
```

### Example

```python
age = 20
has_id = True

if age >= 18 and has_id:
    print("Entry allowed")
```

Both conditions must be true.

---

# 🧠 Memory Trick

```text
if → first check

elif → another check

else → if nothing matches
```

Simple.

---

# 📖 Summary

Conditions help programs:

- make decisions
- check rules
- control actions

Without conditions,

programs cannot think.

This is one of the most important topics in Python.

Master it well.

---

# 🧩 Practice Problem — Level 2

## Problem Statement

Ask the user for age.

Check:

- if age is 18 or more → print  
  **"You are eligible to vote"**

- else → print  
  **"You are not eligible to vote"**

---

# 🖥 Example Input / Output

```text
Enter your age: 21
```

### Output

```text
You are eligible to vote
```

---

### Example

```text
Enter your age: 15
```

### Output

```text
You are not eligible to vote
```

---

# 💡 Small Hint (Not Full Solution)

Use:

```python
age = int(input("Enter your age: "))
```

Then:

```python
if
else
```

and

```python
>=
```

---

# ⚡ Mini Challenge

Upgrade the program:

Also check:

if age is exactly 18

then print:

```text
You just became eligible to vote!
```

Now your logic becomes stronger.
