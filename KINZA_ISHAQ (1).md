# Assignment 02: -

### 1. Declare and print a variable with the name "name" containing your name.


```python
name = "kinza"
print(name)
```

    kinza
    

### 2. Create two variables, x and y, and swap their values without using a third variable.


```python
x = 5
y = 13
x,y = y,x
print(x)
print(y)
```

    13
    5
    

### 3. Calculate the area of a rectangle with length and width stored in variables.¶


```python
length = 9
width = 16
area = length*width
print(area)
```

    144
    

### 4. Create a variable with a long string (multi-line) and print its length.



```python
k = """i am a student of CGIS 
and i am practising python"""
print(k)
```

    i am a student of CGIS 
    and i am practising python
    


```python
len(k)
```




    50



### 5. Create a variable to store your favorite number and print it.


```python
num = 12
print(num)
```

    12
    

### 6. Declare and assign values to multiple variables to represent the sides of a triangle. Calculate and print its perimeter.


```python
side1 = 12
side2 = 10
perimeter = (side1 + side2)
print(perimeter)
```

    22
    

### 7. Store the price of an item in one variable and the quantity in another. Calculate and print the total cost.


```python
price_of_an_item  = 70
quantity = 3
tot_cost = (price_of_an_item)*(quantity)
print(tot_cost)
```

    210
    

### 8. Declare a constant variable for the value of pi (π) and use it to calculate the circumference of a circle with a given radius.


```python
pi = 3.14
radius = 5
circum = (2)*(pi)*(radius)
print(circum)
```

    31.400000000000002
    

### 9. Calculate the sum of two numbers, a and b.


```python
a = 44
b = 22
sum = a+b
print(sum)
```

    66
    

### 10. Calculate the product of two numbers, a and b.


```python
a = 7
b = 9
product = a*b
print(product)
```

    63
    

### 11. Calculate the result of dividing a by b (with proper error handling for division by zero).


```python
a = 63
b = 0
div = a/b
print(div)
```


    ---------------------------------------------------------------------------

    ZeroDivisionError                         Traceback (most recent call last)

    Cell In[13], line 3
          1 a = 63
          2 b = 0
    ----> 3 div = a/b
          4 print(div)
    

    ZeroDivisionError: division by zero


### 12. Calculate the square of a number x.


```python
x = 8
sq = x*x
print(sq)
```

    64
    

### 13. Calculate the remainder when a is divided by b.


```python
a = 10
b = 3
remain = a%b
print(remain)
```

    1
    

### 14. Calculate the result of dividing 17 by 3 and print the quotient and remainder.


```python
x=17
y=3
quotient = x//y
remain = x%y
```


```python
print(quotient)
```

    5
    


```python
print(remain)
```

    2
    

### 15. Calculate the area of a square with a given side length.


```python
length = 6
area = length*length
print(area)
```

    36
    

### 16. Calculate the average of five numbers.


```python
num = 1,2,3,4,5
sum = (1+2+3+4+5)
tot_num = 5
avg = (sum)/(tot_num)
```


```python
print(sum)
```

    15
    


```python
print(avg)
```

    3.0
    

### 17. Create a variable with a boolean value and print its opposite value.


```python
value = True
opposite = not value
print(opposite)
```

    False
    

### 18. Store your birth year in a variable and calculate your age.



```python
k = 1999
now = 2023
age = now-k
print(age)
```

    24
    

### 19. Create a variable with an integer and convert it to a float.


```python
integer_value = 42
type(integer_value)
```




    int




```python
float_value = float(integer_value)
print(float_value)
```

    42.0
    


```python
type(float_value)
```




    float



### 20. Create a variable with a float and convert it to an integer.


```python
float_value = 43.6793901
type(float_value)
```




    float




```python
integer_value = int(float_value)

print(integer_value)
```

    43
    


```python
type(integer_value)
```




    int



### 21. Create a variable with a string that represents an integer and convert it to an integer.


```python
string = "90"
type(string)
```




    str




```python
integer = int(string)
print(integer)
```

    90
    


```python
type(integer)
```




    int



### 22. Create a variable with a string that represents a float and convert it to a float.


```python
string = "27"
type(string)
```




    str




```python
float_value = float(string)
print(float_value)
```

    27.0
    


```python
type(float_value)
```




    float



### 23. Create a variable with a number and convert it to a string.


```python
num = 76
type(num)
```




    int




```python
string_value = str(num)
print(string_value)
```

    76
    


```python
type(string_value)
```




    str



### 24. Calculate the absolute value of a number.


```python
num = -43
absolute = abs(num)
print(absolute)
```

    43
    

### 25. Calculate the square root of a number.


```python
import math
num = 81
square_root = math.sqrt(num)
print(square_root)
```

    9.0
    

### 26. Calculate the value of a raised to the power of b.


```python
a = 4
b = 3
power = a**b
print(power)
```

    64
    

### 27. Round a float to the nearest integer.


```python
float_value = 49.01827
rounded = round(float_value)
print(rounded)
```

    49
    

### 28. Combine multiple conditions using logical operators and print the result.


```python
s = 6
w = 11
condition1 = s>1
condition2 = w>4
result = condition1 and condition2
print(result)
```

    True
    

### 2nd condition


```python
s = 6
w = 11
condition1 = s<1
condition2 = w>4
result = condition1 and condition2
print(result)
```

    False
    

### 3rd condition


```python
s = 6
w = 11
condition1 = s>1
condition2 = w<4
result = condition1 and condition2
print(result)
```

    False
    

### 29. Generate a random number between 1 and 100.


```python
import random
random_num = random.randint(1, 100)
print(random_num)

```

    46
    


```python

```
