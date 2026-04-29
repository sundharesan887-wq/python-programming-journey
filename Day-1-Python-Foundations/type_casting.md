# Type Casting in Python

Same value

Different data type.

---

# 🧠 What is Type Casting?

Type casting means:

> converting one data type into another

# Example

```python
  age = "21"
```
This is:

# String

(text)

But if we want math:

```python
  age + 1
```

Python gets confused.

Because text and number are different.

So we convert:

```python
age = int(age)
```

Now it becomes:

# Integer

and math works.

---

# 💻 Example

```python
age = "21"

print(type(age))

age = int(age)

print(type(age))
```

---

# 🖥 Output

```text
<class 'str'>
<class 'int'>
```

Perfect.

Type changed.

---

# 📚 Main Type Casting Functions

These are very important:

- `int()`
- `float()`
- `str()`
- `bool()`

Learn these well.

---

# 1️⃣ int()

Used to convert into:

# Integer

---

# 💻 Example

```python
num = int("10")
print(num)
```

### Output

```text
10
```

Now it is a number.

---

# 2️⃣ float()

Used to convert into:

# Decimal Number

---

# 💻 Example

```python
price = float("99.5")
print(price)
```

### Output

```text
99.5
```

---

# 3️⃣ str()

Used to convert into:

# String (Text)

---

# 💻 Example

```python
age = 21

age = str(age)

print(type(age))
```

### Output

```text
<class 'str'>
```

---

# 4️⃣ bool()

Used to convert into:

# Boolean

---

# 💻 Example

```python
print(bool(1))
print(bool(0))
```

### Output

```text
True
False
```

Usually:

```text
0 → False
non-zero → True
```

---

# ⚠️ Most Important Beginner Mistake

Look at this:

```python
num = input("Enter number: ")

print(num + 5)
```

This gives error.

---

# ❓ Why?

Because:

```python
input()
```

always gives:

# String

not integer.

So:

```python
"5" + 5
```

is invalid.

Python gets angry.

---

# ✅ Correct Way

```python
num = int(input("Enter number: "))

print(num + 5)
```

Now it works.

Very important.

Remember forever.

---

# 🔗 String + String

This works:

```python
print("5" + "5")
```

### Output

```text
55
```

because Python joins text.

This is called:

# Concatenation

Not addition.

Very important.

---

# ➕ Integer + Integer

This works:

```python
print(5 + 5)
```

### Output

```text
10
```

because this is real math.

Understand the difference.

---

# 🌊 Float Input Example

```python
height = float(input("Enter height: "))
```

Useful for:

- marks
- money
- height
- weight

Very common.

---

# 🧠 Memory Trick

```text
input() → always string

Need math?

Use int() or float()
```

This saves beginners from many errors.

---

# 📊 Summary Table

| Function | Converts To |
|---|---|
| `int()` | Integer |
| `float()` | Decimal |
| `str()` | Text |
| `bool()` | True / False |

Remember this table.

Very important.

---

# 🧠 One-Line Memory Trick

```text
Same value, different type

That is Type Casting.
```

Remember forever.
