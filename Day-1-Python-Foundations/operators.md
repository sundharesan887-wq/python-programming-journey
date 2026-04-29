# Operators in Python

Operators help Python perform actions.

Just like:

```python
+  -  *  /
```

help in maths.

Python uses operators to:

- add
- subtract
- compare
- make decisions
- check conditions

Operators are like tools.

Without tools, work becomes hard.

---

# 🧮 Simple Story

Imagine:

You go to a shop.

You buy:

- 2 chocolates
- each costs 10

Now your brain does:

```python
2 × 10 = 20
```

That `×`

is an operator.

Python also uses operators like this.

---

# 📚 Types of Operators

Main beginner operators:

1. Arithmetic Operators  
2. Comparison Operators  
3. Assignment Operators  
4. Logical Operators  

We learn them one by one.

---

# 1️⃣ Arithmetic Operators

Used for maths.

| Operator | Meaning | Example |
|---|---|---|
| + | Addition | 10 + 5 |
| - | Subtraction | 10 - 5 |
| * | Multiplication | 10 * 5 |
| / | Division | 10 / 5 |
| % | Modulus (remainder) | 10 % 3 |
| // | Floor Division | 10 // 3 |
| ** | Power | 2 ** 3 |

---

## Example

```python
a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a % b)
```

### Output

```python
13
7
30
3.333...
1
```

---

# ⭐ Why `%` is Important

```python
10 % 3 = 1
```

because:

```python
3 × 3 = 9
remaining = 1
```

This helps a lot in even/odd problems later.

Very important.

---

# 2️⃣ Comparison Operators

Used to compare values.

They always give:

# True or False

| Operator | Meaning |
|---|---|
| == | equal to |
| != | not equal |
| > | greater than |
| < | less than |
| >= | greater than or equal |
| <= | less than or equal |

---

## Example

```python
age = 18

print(age >= 18)
```

### Output

```python
True
```

Because 18 is equal to 18.

---

# ⚠️ Important

```python
=
```

means assign

but

```python
==
```

means compare

Very important difference.

Never confuse them.

---

# 3️⃣ Assignment Operators

Used to store values.

Example:

```python
x = 5
```

Also:

```python
x += 2
```

means:

```python
x = x + 2
```

Same meaning.

Shortcut style.

---

## Example

```python
x = 10
x += 5

print(x)
```

### Output

```python
15
```

---

# 4️⃣ Logical Operators

Used for combining conditions.

| Operator | Meaning |
|---|---|
| and | both must be true |
| or | at least one true |
| not | opposite result |

---

## Example

```python
age = 20
has_id = True

print(age >= 18 and has_id)
```

### Output

```python
True
```

Both conditions are true.

---

# 🧠 Memory Trick

```text
+ - * / → Maths

== > < → Compare

= += → Store

and or not → Logic
```

Remember this forever.

---

# 📖 Summary

Operators help Python:

- calculate
- compare
- decide
- update values

Almost every program uses operators.

They are everywhere.

Master them early.

---

# 🧩 Practice Problem — Level 2

## Problem Statement

Ask the user for 2 numbers.

Then print:

- Addition
- Subtraction
- Multiplication
- Division

---

# 🖥 Example Input / Output

```python
Enter first number: 10
Enter second number: 5
```

### Output

```python
Addition: 15
Subtraction: 5
Multiplication: 50
Division: 2.0
```

---

# 💡 Small Hint (Not Full Solution)

Use:

```python
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
```

Then use operators like:

```python
+
-
*
/
```

---

# ⚡ Mini Challenge

Also print:

# Remainder

using:

```python
%
```

This will help later in even/odd problems.

Very useful.
