
# Python program which accepts the radius of a circle from the user and compute the area :


```python

r=float(input("radius of the cirle in cms : "))
area = (3.142)*(r**2)
print("area of the circle in cm^2 is " + str(area))
```

    radius of the cirle in cms : 1
    area of the circle in cm^2 is 3.142
    

# Python program to find whether a given number is even or odd :


```python

n=int(input("enter a no: "))
d=n%2
if d==0:
        print("number is even")
else:
        print("number is odd")


```

    enter a no: 5
    number is odd
    

#  Python program to check if a number is positive, negative or zero :


```python

x=int(input("enter a number : "))
if x > 0 :
    print("number is positve")
elif x < 0 :
    print("number is negative")
elif x ==0 :   
    print("number is zero")
```

    enter a number : 4404
    number is positve
    

# Python program to check whether a number is completely divisible by another number :


```python

x=int(input("enter numerator : "))
y=int(input("enter demonimator : "))
z=x/y
a=x%y
print("quotient = " + str(z))
print("remainder = " + str(a))
if x%y ==0:
    print(str(x) + " is completely divisible by " + str(y))
else:
    print(str(x) + " is not completely divisible by " + str(y))
```

    enter numerator : 7
    enter demonimator : 4
    quotient = 1.75
    remainder = 3
    7 is not completely divisible by 4
    

# Python program which accepts the radius of a circle from the user and compute the volume :


```python

r=float(input("enter the radius of sphere in cms : "))
v=(4/3)*(3.142)*r**3
print("volume of sphere is " + str(v) + " cms^3")
```

    enter the radius of sphere in cms : 1
    volume of sphere is 4.189333333333333 cms^3
    

# Python program to get a string which is n (non-negative integer) copies of a given string :


```python

print("hi\n" * 4)
```

    hi
    hi
    hi
    hi
    
    

# Python program to get a string which is n (non-negative integer) copies of a given string :


```python

print("hi " * 4)
```

    hi hi hi hi 
    

# Python program to test whether a passed letter is a vowel or not :


```python

x=input("enter an alphabet : ").lower()
if  (x=="a" or x=="e" or x=="i" or x=="o" or x=="u") :
    print("alphabet you entered is a vowel")
else :
    print("alphabet you entered is a consonant")
```

    enter an alphabet : A
    alphabet you entered is a vowel
    

# Python program that will accept the base and height of a triangle and compute the area :


```python

x=float(input("enter base of triangle in cms :"))
y=float(input("enter height of triangle in cms :"))   
a=(1/2)*x*y
print("area of triangle is " + str(a) + " cm^2")
```

    enter base of triangle in cms :2
    enter height of triangle in cms :4
    area of triangle is 4.0 cm^2
    

# Python program to compute the distance between the points (x1, y1) and   (x2, y2) :


```python

x1=int(input("enter x1 : "))
x2=int(input("enter x2 : "))
y1=int(input("enter y1 : "))
y2=int(input("enter y2 : "))
d=((x2-x1)**2 + (y2-y1)**2)**(1/2)
print("the distance between points " + str((x1,y1)) + " and " + str((x2,y2)) + " is " + str(d) + " units")

```

    enter x1 : 2
    enter x2 : 4
    enter y1 : 0
    enter y2 : 0
    the distance between points (2, 0) and (4, 0) is 2.0 units
    

# Python program to convert length from feet to centimeters :


```python

l=float(input("enter length in feet : "))
x=l*30.48
print("lenght in cms is " + str(x))

```

    enter length in feet : 5
    lenght in cms is 152.4
    

# Python program to calculate body mass index :


```python

m=float(input("enter mass : "))
h=float(input("enter height : "))
bmi=m/(h**2)
print("body mass index is " + str(bmi) + " kg\/m^2")
```

    enter mass : 50
    enter height : 3
    body mass index is 5.555555555555555 kg\/m^2
    

# Python program to sum of the first n positive integers :


```python

n=int(input("enter any number : "))
s=(n*(n+1))/2
print("sum of first " + str(n) + " integers is " + str(s))
```

    enter any number : 5
    sum of first 5 integers is 15.0
    


```python

```
