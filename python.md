# Handbook: Python

🚩 Leer antes Fundamentos.md

# 🤘 1: Base

## Que es Python?

- Lenguaje de programación de alto nivel.
- multipropósito. 
- interpretado.
- de código abierto. 

## Hola mundo!
- 🧑‍💻
```
    print("Hola mundo")
```

## Operadores aritméticos

Simples: x + y ; x - y ; x * y ; x / y ;
x**e  Exponente 
x**2  Square
x**3  Cube 
x**(1/2) Square root (½) or (0.5) fractional exponent operator returns the square root of x
x // y Floor division operator returns the integer part of the integer division of x by y
x % y Modulo operator returns the remainder part of the integer division of x by y

## Tipos de datos

- int
- float
- str
- bool
- list
- tuple 
- set
- dict

##

# 🤘 Cap: Estructuras de control

## loops

### Recursion
- Es la aplicación repetida del mismo procedimiento a un problema más pequeño.

- Una función recursiva debe incluir:
    -   recursive case:
        - Llama a la función nuevamente, pero con un valor diferente. 
    -   base case:
        - Devuelve un valor sin llamar a la misma función.
 
- 🧑‍💻
```
   def recursive_function(parameters):
    if base_case_condition(parameters):
        return base_case_value
    recursive_function(modified_parameters)
```


