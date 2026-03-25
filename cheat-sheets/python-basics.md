# Python Basics Cheat Sheet

*Python syntax I'm learning*

---

## Hello World
```python
print("Hello, World!")
```

---

## Variables
```python
name = "Amna"          # String
age = 25               # Integer
height = 5.5           # Float
is_learning = True     # Boolean
```

---

## Comments
```python
# This is a comment (Python ignores this line)

"""
This is a multi-line comment
Good for longer explanations
"""
```

---

## If Statements
```python
if age >= 18:
    print("You're an adult")
else:
    print("You're a minor")
```

---

## Loops

### For Loop
```python
for i in range(5):     # 0 to 4
    print(i)
```

### While Loop
```python
count = 0
while count < 5:
    print(count)
    count += 1
```

---

## Functions
```python
def greet(name):
    return f"Hello, {name}!"

message = greet("Amna")
print(message)
```

---

## Lists (Arrays)
```python
fruits = ["apple", "banana", "cherry"]
fruits[0]          # "apple"
fruits.append("orange")    # Add item
len(fruits)        # Get length (4)
```

---

## Dictionaries
```python
person = {
    "name": "Amna",
    "age": 25,
    "city": "Karachi"
}
person["name"]           # "Amna"
person["age"] = 26       # Update value
```

---

## Common Errors

| Error | What It Means | How to Fix |
|-------|--------------|------------|
| `IndentationError` | Wrong spacing | Use consistent 4-space indents |
| `SyntaxError` | Typo in code | Check for missing colons, quotes |
| `NameError` | Variable doesn't exist | Check spelling |
| `TypeError` | Wrong data type | Convert types (str(), int()) |
