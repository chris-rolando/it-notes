# Bases 101
- Apuntes y recordatorios personales de IT
- 🧑‍💻: code
- 🦖: nota personal
- 🤖: truco
- 🚩: bookmark
- 🤘: You Rock!

## Lenguajes de programacion
- Reglas para dar instrucciones al PC

### Bajo nivel
- Lenguaje nativo del PC
- Para pogramar componentes

### Alto nivel
- Lenguaje humanamente entendible
- Para programar aplicaciones

### Interpretado
- El codigo se ejecuta por un intérprete en tiempo de ejecución

### Compilado
- El codigo se traduce o compila a codigo maquina



## Variable?

- 🦖 Son cajitas para guardar.
- Es un espacio reservado en memoria para guardar info!

### 🧑‍💻 JS

```
  // declarar e inicializar
  let miVariable = "es variable";
  const miConstante = "es constante";
  let numero; // declarar
  numero= 1; // inicializar
```

- 🧑‍💻 Python

```
    # Declarar e inicializar variables

    mi_variable = "es variable"
    mi_constante = "es constante"

    # Declarar y asignar valor a una variable

    numero = None

    # Inicializar la variable

    numero = 1
```

- 🧑‍💻 C#

```
    // Declarar e inicializar variables

    string miVariable = "es variable";
    const string miConstante = "es constante";

    // Declarar y asignar valor a una variable

    int numero; // declarar
    numero = 1; // inicializar
```

## camelCase?

- let, const, function: **miNombreEs**
- class: **MiClaseEs**

## Funcion?

- Es un **bloque de código para hacer una tarea** que se ejecuta cuando es llamada!
- Puede: 
    - Ser llamada o invocada.
    - Recibir parámetros - argumentos.
    - Procesar info.
    - Retornar algo o realizar una acción.
    - Sirve para organizar, reutilizar, encapsular y separar.
    - Permite modularidad y abstracción.

### 🧑‍💻 JS
```
    function sumar(a, b) {
    return a + b;
    }

    console.log(sumar(3, 4)); // Imprime 7

```

- 🧑‍💻 Python

```
    def sumar(a, b):
    return a + b

    print(sumar(3, 4))  # Imprime 7

```

- 🧑‍💻 C#

```
    public int Sumar(int a, int b)
    {
    return a + b;
    }

    Console.WriteLine(Sumar(3, 4)); // Imprime 7
```

## Objetos

- Representacion del mundo real
- Tiene propiedades y funciones
    - Propiedades o atributos: 
        - son los datos
        - son los sustantivos
        - características o atributos del objeto
        - describen su estado
    - Funciones o comportamientos: 
        - son los metodos
        - son los verbos
        - definen el comportamiento del objeto
        - realizan manipulaciones sobre los datos del objeto

- 🦖 Objeto cachorro[propiedades: nombre, raza; funciones: ladrar, correr, dormir;]

### 🧑‍💻 JS
    ```
    class Animal {
    constructor(especie) {
    this.especie = especie;
    }
    respirar() {
    console.log("Respirando...");
    }
    }

    class Perro extends Animal {
    ladrar() {
    console.log("Guau!");
    }
    }

    const perro = new Perro("Canino");
    console.log(perro.especie); // Output: "Canino"
    perro.respirar(); // Output: "Respirando..."
    perro.ladrar(); // Output: "Guau!"
    ```

## Clases
- Es una plantilla para crear objetos

## Metodo Constructor
- Se usa para inicializar un objeto cuando se crea una instancia de una clase. 

## ¿Que es POO?
- Programacion Orientada a Objetos
- Es un **Paradigma de programación que se enfoca en el uso de objetos** para representar conceptos del mundo real.

### Elementos:
  - Clases
  - Propiedades
  - Métodos
  - Objetos

### Pilares:
  - Encapsulamiento
  - Abstracción
  - Herencia
  - Polimorfismo

## Algoritmos
- Instrucciones ordenadas para resolver un problema

## IDE
- Integrated Development Environment
- Entorno de Desarrollo Integrado
- Visual studio: [entorno completo]
- VS Code: (editor de codigo) [entorno simple]

## Conversión implícita y explícita?
- **Implícita**: el intérprete convierte automáticamente un tipo de dato en otro, **sin tener que indicar que lo haga**.
- **Explícita**: **convertimos manualmente** un tipo de dato a otro llamando a la función correspondiente para el tipo de dato al que queremos convertir.

## Refactorización
- Proceso para reestructurar el código sin cambiar su funcionalidad.

## Garbage collector?
- Se encarga de liberar la memoria que ya no se está utilizando.

## Framework
- is a conceptual tool that provides guidance on the best practices and processes for solving  problems and building solutions that solve the problems of real users.

## Dependencias
- Componentes externos necesarios para que una app funcione






## Operadores abreviado en Python
i = i + 2 * j               i += 2 * j
var = var / 2               var /= 2
rem = rem % 10              rem %= 10
j = j - (i + var + rem)     j -= (i + var + rem)
x = x ** 2                  x **= 2

## Readme.md

- Consideraciones al crear el archivo
1. Descripción general
2. Estado del proyecto
3. Requisitos
4. Guía de instalación y funcionamiento
5. Bugs y posibles correcciones
6. FAQ's
7. Derechos  y licencias.

## Table of Contents
1. [General Info](#general-info)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Collaboration](#collaboration)
5. [FAQs](#faqs)

## seguir aqui!