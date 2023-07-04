# Conceptos
<!-- Nota: leer periodicamente -->

## camelCase?

- 🦖 let, const, function: "miNombreEs"
- 🦖 class: "MiClaseEs"

## Variable?

- 🦖 Son cajitas donde guardamos cosas.
- Es un **espacio reservado en memoria** para guardar info!

### code:

- 🧑‍💻 **JS**:

```
  // declarar e inicializar
  let miVariable = "es variable";
  const miConstante = "es constante";
  let numero; // declarar
  numero= 1; // inicializar
```

- 🧑‍💻 **Python**:

```
    # Declarar e inicializar variables

    mi_variable = "es variable"
    mi_constante = "es constante"

    # Declarar y asignar valor a una variable

    numero = None

    # Inicializar la variable

    numero = 1
```

- 🧑‍💻 **C#**:

```
    // Declarar e inicializar variables

    string miVariable = "es variable";
    const string miConstante = "es constante";

    // Declarar y asignar valor a una variable

    int numero; // declarar
    numero = 1; // inicializar
```

## Funcion?

- 🦖 Es un **bloque de código para hacer una tarea** que se ejecuta cuando es llamada!
- Puede ser llamada o invocada.
- Puede recibir parámetros - argumentos.
- Puede procesar info.
- Puede retornar algo o realizar una acción.
- Sirve para organizar, reutilizar, encapsular y separar.
- Permite modularidad y abstracción.

### code

- 🧑‍💻 **JS**:

```
    function sumar(a, b) {
    return a + b;
    }

    console.log(sumar(3, 4)); // Imprime 7

```

- 🧑‍💻 **Python**:

```
    def sumar(a, b):
    return a + b

    print(sumar(3, 4))  # Imprime 7

```

- 🧑‍💻 **C#**:

```
    public int Sumar(int a, int b)
    {
    return a + b;
    }

    Console.WriteLine(Sumar(3, 4)); // Imprime 7
```

## lenguaje interpretado

## lenguaje compilado

## IDE?

## Que es conversión implícita y explícita?
- **Implícita**: el intérprete convierte automáticamente un tipo de dato en otro, **sin tener que indicar que lo haga**.
- **Explícita**: **convertimos manualmente** un tipo de dato a otro llamando a la función correspondiente para el tipo de dato al que queremos convertir.

## Refactorización
- Proceso para reestructurar el código sin cambiar su funcionalidad.

## Garbage collector?
- Se encarga de liberar la memoria que ya no se está utilizando.