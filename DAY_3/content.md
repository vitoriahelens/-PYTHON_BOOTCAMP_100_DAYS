# DAY 3 - BEGGINER
#### CONTROL FLOW AND LOGICAL OPERATORS

## CONTROL FLOW WITH IF / ELSE

```python
if condition:
    do this
else
    do this
```
```python
# Verify water level from bathtub
water_level = 50
if water_level > 80:
    print("Drain Water")
else:
    print("Keep going")

print("Welcome to the rollercoaster!")
height = int(input("What is yout height in cm? "))

if height >= 120:
    print("You can ride the rollecoaster!")
else:
    print("Sorry, you have to grow taller before you can ride!")
```

```python
# Leap Calculator
year = int(input("Wich year do you want do check? "))

if year % 4 == 0:
    if year % 100 == 0:
        if year % 400 == 0:
            print("Leap year")
        else:
            print("Not leap year")
    else:
        print("Leap year")
else:
    print("Not leap year")
```


## COMPARISON OPERATORS

```python
>  | Greater than
<  | Less than
>= | Greater than or equal to 
<= | Less than  or equal to 
== | Equal to
!= | Not equal to

number = int(input("Insert a number: "))

if number % 2 == 0:
    print ("This is an even number.")
else:
    print ("This is a odd number.")
```

## ELIF
```python
if condition:
   do A
elif condition1:
   do B
else:
   do C
```
```python
# BMI Calculator
height = float(input("Enter your height in meters: "))
weight = int(input("Enter your wight in kilograms: "))

bmi = weight / height ** 2

if bmi < 18.5:
    print(f"Your BMI is {bmi}, you are underweight.")
elif bmi < 25:
    print(f"Your BMI is {bmi}, you have a normal weight.")
elif bmi < 30:
    print(f"Your BMI is {bmi}, you are slightly overweigh.")
elif bmi < 35:
    print(f"Your BMI is {bmi}, you are obese.")
else:
    print(f"Your BMI is {bmi}, you are clinically obese.")
```
## MULTIPLE IF STATEMENTS

```python
if condition1:
    do A
if condition2:
    do B
if condition3:
    do C
```

```python
# Pizza Order
print("Thank your for choosing Python Pizza Deliveries")
size = input("What size pizza do yout want? S, M or L \n")
add_pepperoni = input("Do you want pepperoni? Y or N \n")
extra_cheese = input ("Do you want extra cheese? Y or N \n")

bill = 0

if size == "S":
    bill += 15
elif size == "M":
    bill += 20
else:
    bill += 25

if add_pepperoni == "Y":
    if size == "S":
        bill += 2
    else:
        bill += 3
    
if extra_cheese == "Y":
    bill += 1

print(f"Your final bill is: ${bill}")
```

## LOGICAL OPERATORS

```python
and | A and B, if one is false, everything is false 
or  | C or D, if one is true, everything is true 
not | not E, if E is true, than it's be false
```

```python
# Rollercoaster Tickets
print("Welcome to the rollercoaster!")
height = int(input("What is yout height in cm? "))

bill = 0

if height >= 120:
    print("You can ride the rollecoaster!")
    age = int(input("What's your age? "))
    if age < 12:
        bill = 5
        print ("Child tickets are $5.")
    elif age <= 18:
        bill = 7
        print("Youth tickets are $7.")
    elif age >= 45 and age <= 85:
        print("Everything is gona be okay. Have a free ride on us!")
    else:
        bill = 7
        print("Adult tickets are $12.")
    
    wants_photo = input("Do you want a photo taken? Y or N. ")

    if wants_photo == "Y":
        bill += 3
    
    print(f"Your final bill is ${bill}.")

else:
    print ("Sorry, you have to grow taller before you can ride!")
```
---

## FINAL PROJECT - TREASURE ISLAND
<img src = DAY_1.png>
