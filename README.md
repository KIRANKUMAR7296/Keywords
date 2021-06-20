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

------------------
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
--------------------
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
