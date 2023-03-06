# Unidad IV ~ Implementación GO

## Tipos, Valores y Variables

Go provee una variedad de tipos de datos primitivos y complejos. Los tipos primitivos(primitive types) son los bloques de construcción básicos tales como strings, numbers and booleans. Los tipos de datos complejos son estructuras definidas por el usuario compuestos por una combinación de uno o más tipos primitivos y/o complejos.

### Tipos de Datos Primitivos

| Grupo | Tipos de datos | Descripción |
| ----------- | ----------- | ----------- |
| Reales | float32, float64 | Son números que tienen punto flotante, es decir, contienen decimales |
| Enteros | int, int8, int16, int32, int64 | Son números que no tienen parte decimal |
| Lógicos | bool | Solo pueden tomar dos valores *true* o *false* |
| Caracteres | string | Caracteres que van entre comillas para formar texto |

(*) Me faltaron catalogar uint, uint8, uint16, uint32, uint64, uintptr, byte, rune, complex64 y complex128


En Go las ***variables*** se declaran utilizando la palabra clave `var` seguida del nombre que le queremos dar a la variable y a continuación especificando el ***tipo*** de la misma.

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

Las constantes pueden ser de tipo character, string, boolean, o valores numericos. Si bien no se vió por el momento, cabe mencionar que las constantes no pueden ser declaradas utilizando la sintaxis `:=`.



### Tipos de Datos Complejos

Además de los tipos de datos primitivos, Go dispone tipos de datos complejos, tales como `slices` y `maps`. 