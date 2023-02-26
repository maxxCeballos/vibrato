# Implementación: GO

## Introducción

En esta sección veremos algunos conceptos de Go que son elementales para comenzar a programar. Se describe como especificar variables, constantes tipos de dato, operadores y operandos, expresiones y el concepto de asignación en Go.
Adicionalmente se resume la sintaxis asociada a estos conceptos, caracterīsticas de entrada/salida, y la estructura básica de un programa en Go.


## Variables y Constantes

### Variables

En Go las variables se declaran utilizando la palabra clave `var` seguida del nombre o etiqueta que le queremos dar a la variable y a continuación especificando el tipo de la misma. Las variables pueden almacenar datos de tipo primitivo o de estructura, y su valor puede cambiar durante la ejecución del programa tantas veces como sea necesario, además pueden aplicarse ciertas operaciones dependiendo del tipo de las variables. Por ejemplo

```go
var name string
var isWork bool
var cantContributors int
```

### Constantes

En Go las constantes se declaran utilizando la palabra clave `const` seguida del nombre o etiqueta que se le quiere dar a la variable y a continuación se debe inicializar la variable con el valor con el cual operará durante la ejecución del programa, es decir, la variable se debe inicializar al momento de declararla y el valor de dicha variable no puede cambiar durante la ejecución de un programa.

```go
const Pi = 3.14
const Port = 8080
```

Las constantes pueden ser de tipo character, string, boolean, o valores numericos. Si bien no se vio por el momento, cabe mencionar que las constantes no pueden ser declaradas utilizando la sintaxis `:=`.