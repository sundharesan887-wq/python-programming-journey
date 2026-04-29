# Jump Statements in Python

Jump statements help Python control loops better.

Sometimes we do NOT want the loop to continue normally.

Sometimes we want to:

- stop the loop
- skip one step
- keep a place empty for later

That is where jump statements help.

---

# 📚 3 Important Jump Statements

- `break`
- `continue`
- `pass`

Very important topic.

---

# 🚦 Simple Story

Imagine you are walking to school.

## Situation 1

You see heavy rain

→ you stop going

This is:

# break

---

## Situation 2

You see a small puddle

→ you skip it and keep walking

This is:

# continue

---

## Situation 3

Teacher says:

> “I will tell you later what to do”

→ for now, do nothing

This is:

# pass

---

# 1️⃣ break Statement

Used to:

# Stop the loop completely

---

# 💻 Example

```python
for i in range(1, 11):
    if i == 5:
        break
    print(i)
```

---

# 🖥 Output

```text
1
2
3
4
```

When Python reaches:

```python
i == 5
```

it stops everything.

Loop ends.

---

# 🧠 Real-Life Meaning

Walk until shop number 5

Then stop

That is `break`.

---

# 2️⃣ continue Statement

Used to:

# Skip one step and continue

---

# 💻 Example

```python
for i in range(1, 6):
    if i == 3:
        continue
    print(i)
```

---

# 🖥 Output

```text
1
2
4
5
```

Python skips:

```text
3
```

but continues the loop.

---

# 🧠 Real-Life Meaning

Skip one bad question

Solve the rest

That is `continue`.

---

# 3️⃣ pass Statement

Used when:

# You want to write code later

For now:

> do nothing

---

# 💻 Example

```python
for i in range(5):
    pass
```

This runs without error.

Even though nothing happens.

---

# ❓ Why `pass` Exists

Sometimes Python expects code.

But you are not ready yet.

Without `pass`, Python gives error.

So `pass` is like:

# Reserved for later

Very useful.

---

# Example with if

```python
age = 20

if age > 18:
    pass
else:
    print("Minor")
```

This means:

We will write logic later.

---

# 🔍 Difference Between Them

| Statement | Meaning |
|---|---|
| `break` | Stop loop completely |
| `continue` | Skip current step |
| `pass` | Do nothing for now |

Remember this table.

Very important.

---

# 🔗 Example Together

```python
for i in range(1, 6):
    if i == 2:
        continue

    if i == 4:
        break

    print(i)
```

---

# 🖥 Output

```text
1
3
```

---

# 🧠 Why?

- skip `2`
- stop at `4`

Very powerful.

---

# 🧠 Memory Trick

```text
break → stop

continue → skip

pass → leave for later
```

Remember forever.

---

# 📖 Summary

Jump statements help us control loops better.

Without them,

loops are limited.

With them,

we can build smarter programs.

This topic is used everywhere.

Master it well.
