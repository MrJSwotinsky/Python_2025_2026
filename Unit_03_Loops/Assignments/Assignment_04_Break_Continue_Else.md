## Unit 3, Assignment 4 - `break`, `continue`, and a new application of `else`
Due: Thursday, December 10th 2025

###  `break`, `continue`, and a new application of `else`

Navigate to https://www.edube.org, sign in, access Python Essentials 1, and read **Python Essentials 1 Module 3**

### `break`, `continue`, `else` Exercises

In your notes, code trace each of the code snippets below to determine what the code will output.  If executing the code will result in an error, explain why:

a. 
```python
a = 0
while a < 4:
    a += 2
    print('!', end = ' ')
else:
    print('!', end = ' ')
```

b. 
```python
b = 8
while b >= 2:
    b /= 2
    print('$', end = ' ')
else:
    print('$$', end = ' ')
```

c. 
```python
c = 1
while c <= 5:
    if c % 2 == 0:
        c += 1
        print('*', end = ' ')
    else:
        print('**', end = ' ')
```

d. 
```python
d = 1
while d <= 5:
    if d % 2 == 0:
        d += 1
        print('*', end = ' ')
else:
    print('**', end = ' ')
```

e. 
```python
e = 5
while e > 0:
    e -= 1
    if e % 2 == 1:
        break
    print('@', end = ' ')
else:
    print('@', end = ' ')
```


f. 
```python
f = 1
while f > 10:
    f *= 2
    print('#', end = ' ')
    if f == 8:
        break
else:
    print('#', end = ' ')
```

g. 
```python
g = 1
while g > 10:
    f *= 2
    print('#', end = ' ')
    if g == 8:
        break
    else:
        print('#', end = ' ')
```

h. 
```python
h = 5
while h > 0:
    h -= 1
    if h % 2 == 1:
        continue
    print('&')
else:
    print('&', end = ' ')
```

i. 
```python
i = 5
while h > 0:
    i -= 1
    if h % 2 == 1:
        continue
    print('&', end = ' ')
    else:
        print('&', end = ' ')
```

j. 
```python
j = 0
while j > 3:
    j += 1
    if j % 2 == 0:
        continue
        print('!', end = ' ')
    else:
        break
else:
    print('!!', end = ' ')
```


k. 
```python
k = 0
for i in range(2):
    for j in range(2):
        if i == j:
            k += 1
        else:
            k += 2
print(k)
```

l. 
```python
l = 0
for i in range(2):
    for j in range(2):
        if i == j:
            l += 1
    else:
        l += 2
print(l)
```

m. 
```python
m = 0
for i in range(2):
    for j in range(2):
        if i == j:
            m += 1
else:
    m += 2
print(m)
```

n. 
```python
n = 0
for i in range(2):
    for j in range(2):
        n += 1
        if i * j < i:
            break
        else:
            n += 1
print(n)
```

o. 
```python
o = 0
for i in range(2):
    for j in range(2):
        o += 1
        if i * j < i:
            break
    else:
        o += 1
print(o)
```

p. 
```python
p = 0
for i in range(2):
    for j in range(2):
        p += 1
        if i * j < i:
            break
else:
    p += 1
print(p)
```

q. 
```python
q = 0
for i in range(2):
    for j in range(2):
        q += 1
        if i * j < i:
            continue
        q += 1
    else:
        q += 1
print(q)
```

r. 
```python
r = 0
for i in range(2):
    for j in range(2):
        r += 1
        if i * j < i:
            continue
        r += 1
else:
    r += 1
print(r)
```
Scan your work, save it as `LastNameFirstInitial_Break_Continue_Else_Code_Tracing_Practice.pdf`, and upload it to your assignments folder.<br>

Commit your progress.  Remember to write an appropriate commit message.  For example, *"Completed break, continue, else code tracing practice."*
