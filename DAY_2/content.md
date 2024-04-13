# DAY 2 - BEGGINER
#### UNDERSTANDING DATA TYPES AND HOW TO MANIPULATES STRINGS

## PRIMITIVE DATA TYPES
```
### STRING
print("Hello"[4])
### INTEGER
print(123 + 345)
### FLOAT
3.14159
### BOOLEAN
True
False
```
## TYPE ERROR, TYPE CHECKING AND TYPE CONVERSION
```
num_char = len(input("What is your name?"))

### Verifica o tipo de uma variável
print(type(num_char))
### Altera o tipo de uma variável
new_num_char = str(num_char)
print("Your name has" + " " + new_num_char + " " + "characters.")
### Checa o tipo de uma variável
a = 123
print(type(a))
a = float(123)
print(type(a))
a = str(123)
print(type(a))
```

## MATHEMATICAL OPERATIONS IN PYTHON
```
print(3 + 5) #soma
print(7 - 4) #subtração
print(3 * 2) #multiplicação
print(6 / 3) #divisão
print(2 ** 3) #potencia
```
### BMI CALCULATOR
```
height = input("Insira sua altura: ")
weight = input("Insira seu peso: ")

height_as_float = float(height)
weight_as_int = int(weight)

bmi = weight_as_int / height_as_float ** 2
bmi_as_int = int(bmi)
print(bmi_as_int)
```

## NUMBER MANIPULATION AND F STRINGS IN PYTHON
```
print(round(8 / 3)) #arredonda para o inteiro mais proximo
print(round(8 / 3, 2)) #arredonda para a casa decimal mais proxima com 2 numeros após o ponto
print(round(8 // 3)) #recebe sempre um numero inteiro, nesse caso, 2

result = 4 / 2
result /= 2 #divide o resultado por dois

score = 0
score += 1 #adiciona 1
score -= 1 #diminui 1
score *= 2 #multiplica por 2
score /= 2 #divide por 2

## f-String
print(f"your score ir {score}") #converte todo o valor
```
---

## FINAL PROJECT - TIP CALCULATOR
<img src = DAY_2.png>