# DAY 3 - BEGGINER
#### CONTROL FLOW AND LOGICAL OPERATORS

## CONTROL FLOW WITH IF / ELSE

```
if condition:
    do this
else
    do this
```
```
water_level = 50
if water_level > 80:
    print("Drain Wather")
else:
    print("Keep going")

print("Welcome to the rollercoaster!")
height = int(input("What is yout height in cm? "))

if height >= 120:
    print("You can ride the rollecoaster!")
else:
    print("Sorry, you have to grow taller before you can ride!")
```

## COMPARISON OPERATORS

```
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
```
if condition:
   do this
elif condition1:
   do B
else:
   do this
```
```
print("Welcome to the rollercoaster!")
height = int(input("What is yout height in cm? "))

if height >= 120:
    print("You can ride the rollecoaster!")
    age = int(input("What's your age? "))
    if age < 12:
        print ("Please pay $5.")
    elif age <= 18:
        print("Please pay $7.")
    else:
        print("Please pay $12.")
else:
    print ("Sorry, you have to grow taller before you can ride!")
```
```
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


---

## FINAL PROJECT - TREASURE ISLAND
<img src = DAY_1.png>