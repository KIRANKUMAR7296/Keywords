# Keywords

Python Keywords are **Predefined**

### False, True

- Boolean Data Types

```python
False == (1 > 2) ,True == (2 > 1)
```

### None 

- `Empty` Value Constant

```python
def func():
  x = 2

func() == None 
--------------
True
```

### and, or, not  

Logical Operators

1. x and y : both x and y must be True.
2. x or y : either x or y must be True.
3. not x : x must be False.

```python
x, y = True, False

print(x and y)
print(x or y)
print(not x )
```

```python
Output : 
False
True
False
```

### break 

- Premature Loop Ending.

```python
while(True):
    break 
print('hello world')
```

```python
Output : 
hello world
```

### class, def 

- `class` : Create New **Class**
- `def` : Define a New **Function** or **Class Method**.

```python
class Car:
    def __init__(self, Name, Company, Model, Type):
        self.Name = Name
        self.Company = Company
        self.Model = Model
        self.Type = Type
        
    def Details(self):
        return f'🚗 Tata Motors\nCompany : {self.Company}\nName    : {self.Name}\nModel   : {self.Model}'
```

```python
C = Car(Name = 'Safari', 
        Company = 'Tata',
        Model = 'ZX',
        Type = 'SUV')

print(C.Details())
```

```python
Output :
🚗 Tata Motors
Company : Tata
Name    : Safari
Model   : ZX
```

### if, elif, else 

- Conditional Program Execution.

```python
x = int(input('Enter the Value : '))
if x > 3: 
    print('Big')
elif x == 3: 
    print('Medium')
else:
    print('Small')
```

```python
Output : 
Enter the Value : 1
Small
```

### for, while 

- Creating **Loops**

```python
for i in [0,1,2]:
    print(i)
```

```python
j = 0
while j < 3:
    print(j)
    j = j + 1
```

```python
Output :
0
1
2
```

### in 

- Check for **Presence** in Sequence.

```python
5 in [5,10,15]
```

```python
Output :
True
```

### is

- Check for **Similary**.

```python
x = y = 3
x is y
```

```python
Output :
True
```

### lambda 

- Create **Anonymous** Function

```python
x = (lambda x : x + 3)
x(2)
```

```python
Output :
5
```

### return 

- **Result** of Function

```Python
def increase(x):
    return x + 1
    
increase(99)    
```

```python
Output :
100
```
