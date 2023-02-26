# Implementación: GO

## Introducción

En esta sección veremos algunos conceptos de Go que son elementales para comenzar a programar. Se describe como especificar variables, constantes tipos de dato, operadores y operandos, expresiones y el concepto de asignación en Go.
Adicionalmente se resume la sintaxis asociada a estos conceptos, caracterīsticas de entrada/salida, y la estructura básica de un programa en Go.


## Variables y Constantes

### Variables

En Go las variables se declaran utilizando la palabra clave `var` seguida del nombre o etiqueta que le queremos dar a la variable y a continuación especificando el tipo de la misma, por ejemplo `var name string`. Las variables pueden almacenar datos de tipo primitivo o de estructura, y su valor puede cambiar durante la ejecución del programa tantas veces como sea necesario, además pueden aplicarse ciertas operaciones dependiendo del tipo de las variables.

```go
package main

import "fmt"

var c, python, java bool

func main() {
	var i int
	fmt.Println(i, c, python, java)
}

// output: 
```
