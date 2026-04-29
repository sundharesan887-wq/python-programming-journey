# Python Loop Practice — Multiplication Tables & Reverse Counting

This section helps strengthen your understanding of:

- `for` loop
- `while` loop
- reverse counting
- step values in `range()`
- `+=` and `-=`

These are very important beginner concepts.

---

# 1️⃣ Multiplication Table Using for Loop

## Goal

Print output like:

```text
2 * 1 = 2
2 * 2 = 4
2 * 3 = 6
...
2 * 10 = 20
```

---

# 💻 Code

```python
num = 2

for i in range(1, 11):
    print(num, "*", i, "=", num * i)
```

---

# 🧠 Main Logic

```python
range(1, 11)
```

gives:

```text
1 to 10
```

Then:

```python
num * i
```

calculates multiplication.

The loop repeats automatically.

Very powerful.

---

# 2️⃣ Multiplication Table Using while Loop

## Goal

Same output using `while`

---

# 💻 Code

```python
num = int(input("Enter number: "))

i = 1

while i <= 10:
    print(num, "*", i, "=", num * i)
    i += 1
```

---

# 🧠 Main Logic

Start from:

```python
i = 1
```

Repeat until:

```python
i <= 10
```

Increase `i` every time using:

```python
i += 1
```

---

# ⚠️ Important

```python
i += 1
```

must be there.

Otherwise:

# Infinite Loop

happens.

Very important.

---

# 3️⃣ Reverse Counting Using while Loop

## Goal

Print:

```text
10
9
8
7
6
5
4
3
2
1
```

---

# 💻 Code

```python
i = 10

while i >= 1:
    print(i)
    i -= 1
```

---

# 🧠 Main Logic

Start from:

```python
10
```

Go backward

Decrease using:

```python
i -= 1
```

Simple.

---

# 4️⃣ Reverse Counting Using for Loop

## Goal

Same reverse counting using `for`

---

# 💻 Code

```python
for i in range(10, 0, -1):
    print(i)
```

---

# 🧠 Main Logic

```python
range(10, 0, -1)
```

means:

```text
start from 10
stop before 0
move by -1
```

This creates reverse counting.

Very useful pattern.

---

# 5️⃣ Even Reverse Counting Using for

## Goal

Print:

```text
10
8
6
4
2
```

---

# 💻 Code

```python
for i in range(10, 0, -2):
    print(i)
```

---

# 🧠 Main Logic

```python
-2
```

means:

> move backward by 2

which gives only even numbers.

Very smart shortcut.

---

# 📚 Important Concepts Learned

---

# `range(start, stop, step)`

### Example

```python
range(10, 0, -1)
```

means:

```text
Start → 10
Stop  → before 0
Step  → -1
```

---

# `+=`

```python
i += 1
```

means:

```python
i = i + 1
```

Shortcut for increasing.

---

# `-=`

```python
i -= 1
```

means:

```python
i = i - 1
```

Shortcut for decreasing.

---

# 🧠 One-Line Memory Trick

```text
for → known repeats

while → condition-based repeats

-1 → reverse

-2 → reverse even numbers
```

Remember this forever.

---

# 📖 Summary

You learned:

- multiplication table using `for`
- multiplication table using `while`
- reverse counting
- reverse even counting
- how `range()` works
- loop control using `+=` and `-=`

These patterns are used again and again in real problem solving.

Master them well.
