## Unit 3, Assignment 3 - Nested For Loops
Due: Friday, December 5th 2025

### Nested For Loops

Navigate to https://www.edube.org, sign in, access Python Essentials 1, and read **Python Essentials 1 Module 3**

### For Loop Labs

### For Loop Exercises

In your notes, code trace each of the code snippets below to determine what the code will output.  If executing the code will result in an error, explain why:

a. 
```python
a = 0
for i in range(2):
  for j in range(2):
    if i == j:
      a += 1
print(a, end= '') 
```

b. 
```python
b = 2
for i in range(2):
  for j in range(2):
    if i == j:
      b -= 1
  print(b, end= '')
```  
  

c.
```python
c = 0
for i in range(2):
  for j in range(2):
    if i != j:
      c += 1
    print(c, end= '')
```

d. 
```python
d = 4
for i in range(2):
  for j in range(2):
    if i == j:
      d += 1
    else:
      d -= 2
print(d, end= '')
```

e. 
```python
e = 4
for i in range(2):
  for j in range(2):
    if i != j:
      e -= 1
    else:
      e += 2
  print(e, end= '')
```

f. 
```python
f = 0
for i in range(2):
  for j in range(2):
    if i == j:
      f += 2
    else:
      f *= 2
    print(f, end= '')
```

g. 
```python
g = 0
for i in range(2):
  for j in range(2):
    if i != j:
      g += 2
    else:
      g *= 2
      print(g, end= '')
```

h. 
```python
h = 2
for i in range(2):
  for j in range(2):
    if i % 2 == j:
      h -= 1
    else:
      h += 1
print(h, end= '')
```
Scan your work, save it as `LastNameFirstInitial_Nested_For_Loop_Code_Tracing_Practice.pdf`, and upload it to your assignments folder.<br>

Commit your progress.  Remember to write an appropriate commit message.  For example, *"Completed nested for loop code tracing practice."*
