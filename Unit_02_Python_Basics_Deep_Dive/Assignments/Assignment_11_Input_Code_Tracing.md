## Unit 2, Assignment 11 - Input Code Tracing
Due: Tuesday, October 28th 2025

### Input Code Tracing

In your notes, code trace each of the code snippets below to determine what the code will output.  If executing the code will result in an error, explain why:

a. Assume the user inputs `1` and `2` respectively:
```python
num_1 = input()
num_2 = input()
print(num_1 + num_2)
```

b. Assume the user inputs `2` and `3` respectively:
```python
num_1 = input()
num_1 = int(num_1)
num_2 = input()
num_2 = int(num_2)
print(num_1 + num_2)
```

c. Assume the user inputs `3` and `4` respectively:
```python
num_1 = int(input())
num_2 = int(input())
print(num_1 * num_2)
```

d. Assume the user inputs `4` and `5` respectively:
```python
num_1 = input(int())
num_2 = input(int())
print(num_1 * num_2)
```

e. Assume the user inputs `5` and `6` respectively:
```python
num_1 = input()
num_2 = int(input())
print(num_1 * num_2)
```

f. Assume the user inputs `6` and `7` respectively:
```python
num_1 = input()
num_2 = input()
print(num_1 * num_2)
```

g. Assume the user inputs `5` and `2` respectively:
```python
num_1 = int(input())
num_2 = int(input())
num_1 = num_1 % num_2
num_2 = num_2 % num_1
print(num_1, num_2)
```

h. Assume the user inputs `6` and `3` respectively:
```python
num_1 = int(input())
num_2 = int(input())
num_1 = num_1 % num_2
num_2 = num_2 % num_1
print(num_1, num_2)
```

i. Assume the user inputs `7` and `4` respectively:
```python
num_1 = int(input())
num_2 = int(input())
num_1 = num_1 // num_2
num_2 = num_2 / num_1
num_1 = num_2 ** num_1
print(num_1, num_2)
```

j. Assume the user inputs `8` and `5` respectively:
```python
num_1 = int(input())
num_2 = int(input())
num_1 = num_1 - num_2
num_2 = num_2 % num_1
num_1 = num_1 / num_2
print(num_1, num_2)
```

Scan your work, save it as `LastNameFirstInitial_Input_Code_Tracing_Practice.pdf`, and upload it to your assignments folder.<br>

Commit your progress.  Remember to write an appropriate commit message.  For example, *"Completed input code tracing practice."*
