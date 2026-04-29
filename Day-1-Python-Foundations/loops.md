# Loops in Python

Loops are one of the most powerful things in programming.

Because computers are great at:

- repeating work

Humans get tired.

Computers do not.

That is where loops help.

---

# 🔁 Simple Story

Imagine your teacher says:

> Write “I will practice Python”  10 times

You have 2 choices:

## Bad way ❌

Write it manually 10 times.

Very boring.

## Smart way ✅

Tell Python:

> Repeat this 10 times

That is called:

# Loop

---

# 🧠 What is a Loop?

A loop is used to:

> repeat code multiple times

instead of writing the same code again and again.

This saves:

- time
- effort
- mistakes

Very important topic.

---

# 📚 Two Main Loops

In Python beginners mainly use:

- `for` loop
- `while` loop

We start with `for`

because it is easier.

---

# 1️⃣ for Loop

Used when we know:

> how many times to repeat

### Example

```python
for i in range(5):
    print("Hello")
```

### Output

```text
Hello
Hello
Hello
Hello
Hello
```

Printed 5 times.

---

# 🔍 Understanding `range()`

```python
range(5)
```

means:

```text
0, 1, 2, 3, 4
```

It starts from `0`

and stops before `5`.

Very important.

---

# Example with Numbers

```python
for i in range(5):
    print(i)
```

### Output

```text
0
1
2
3
4
```

Now Python prints the value of `i`

each time.

---

# Example Starting from 1

```python
for i in range(1, 6):
    print(i)
```

### Output

```text
1
2
3
4
5
```

This is more common.

---

# 2️⃣ while Loop

Used when we do NOT know

exactly how many times to repeat.

It works using a condition.

### Example

```python
count = 1

while count <= 5:
    print(count)
    count += 1
```

### Output

```text
1
2
3
4
5
```

---

# ⚠️ Very Important

If you forget:

```python
count += 1
```

the loop may run forever.

This is called:

# Infinite Loop

Dangerous for beginners.

Be careful.

---

# 🧮 Multiplication Table Example

Now your question:

How to print like this?

```text
2 × 1 = 2
2 × 2 = 4
2 × 3 = 6
```

and so on.

This is a very important loop problem.

---

# 💻 Code for Multiplication Table

```python
num = 2

for i in range(1, 11):
    print(num, "*", i, "=", num * i)
```

### Output

```text
2 * 1 = 2
2 * 2 = 4
2 * 3 = 6
2 * 4 = 8
...
2 * 10 = 20
```

Perfect.

---

# 🔍 How This Works

Let’s understand:

```python
for i in range(1, 11):
```

means:

> i = 1 to 10

Then:

```python
num * i
```

means:

```text
2 × 1
2 × 2
2 × 3
...
```

Python repeats automatically.

Very powerful.

---

# ✨ Better Beautiful Version (f-string)

You can also write:

```python
num = 2

for i in range(1, 11):
    print(f"{num} * {i} = {num * i}")
```

This is cleaner.

This is called:

# f-string

Very useful.

We will use this more later.

---

# 🔗 Loop + Condition Example

```python
for i in range(1, 11):
    if i % 2 == 0:
        print(i)
```

### Output

```text
2
4
6
8
10
```

This prints only even numbers.

Powerful combination.

---

# 🧠 Memory Trick

```text
for → known number of times

while → based on condition
```

Remember this forever.

---

# 📖 Summary

Loops help programs:

- repeat work
- save time
- handle large tasks
- solve real problems faster

Without loops,

coding becomes painful.

Loops are a huge step forward.

---

# 🧩 Practice Problem — Level 2

## Problem Statement

Ask the user for a number.

Print its multiplication table from:

> 1 to 10

like this:

```text
5 * 1 = 5
5 * 2 = 10
5 * 3 = 15
...
5 * 10 = 50
```

---

# 🖥 Example Input / Output

```text
Enter number: 5
```

### Output

```text
5 * 1 = 5
5 * 2 = 10
5 * 3 = 15
...
5 * 10 = 50
```

---

# 💡 Small Hint (Not Full Solution)

Use:

```python
num = int(input("Enter number: "))
```

Then:

```python
for i in range(1, 11):
```

and:

```python
num * i
```

---

# ⚡ Mini Challenge

Upgrade the program:

Print table till:

> 20

instead of 10.

Now your loop becomes stronger.
