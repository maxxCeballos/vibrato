# Unidad IV


## Tipos, Valores y Variables

Los programas de computadoras funcionan manipulando ***valores*** (values), tal como 2.78 o el texto "Hola Mundo". 

Cuando un programa necesita retener un valor para su futuro uso, este asigna el valor a (o almacena el valor en) una ***variable*** y su valor puede cambiar durante la ejecución del programa tantas veces como sea necesario. Una variable define un nombre simbólico para un valor y permite que el valor sea referido mediante el nombre. La manera en que las variables trabajan es otra característica fundamental de cualquier lenguaje de programación. 

Los tipos de valores que pueden ser representados y manipulados en un lenguaje de programación son conocidos como ***tipos de datos*** (data types), y una de las características más importantes de un lenguaje de programación es el conjunto de tipos que este soporta. Los tipos de datos determinan los valores que puede tomar una variable y las operaciones que pueden realizarse con ella, por ejemplo, una variable de tipo entero sólo podrá almacenar números enteros y se podrán aplicar operaciones que admiten los enteros, como la suma, multiplicación, etc.


## Constantes

Una ***constante*** es una variable, es decir, un lugar donde podemos almacenar un valor al cual accedemos mediante un nombre, pero con la garantía de que cuyo valor no puede ser modificado durante la ejecución de un programa.


## Operadores y Operandos

Los ***operadores*** son símbolos que representan algún tipo de operación sobre dos operandos(salvo operadores unarios que actúan sobre un solo operando) y arrojan un resultado. Se deben considerar los *tipos* de operandos para determinar cuales operadores son aplicables. Por ejemplo, si los operandos son números, el operador deberá ser un operador aritmético.


## Expresiones

Una ***expresión*** es todo aquello que se puede evaluar, es decir, que lanza un resultado. Las siguientes son expresiones:

- Variable
- Constante
- Operando Operador
- Operando Operador Operando
- Expresión Operador
- Expresión Operador Expresión

Considerando los tipos de operadores, podemos decir que existen expresiones de tipo aritméticas, relacionales y lógicas, que al ser evaluadas retornan un resultado de cierto tipo. En cada caso tanto los operadores como los operandos deben ser compatibles, de lo contrario la expresión no se podría evaluar. Por ejemplo, si intentamos sumar un entero con un valor lógico (true o false) sería una expresión incorrecta que no se podría evaluar.


## Declaración y Asignación

Antes de que pueda utilizar una variable es necesario ***declarar*** dicha variable. Por ejemplo, como veremos en los ejemplos de implementación con Go, una variable se declara con la palabra clave `var`. Una vez declarada, podemos inicializar la variable, esto es mediante una ***asignación***. El operador de asignación es aquel que permite almacenar en una variable el resultado de evaluar una expresión.