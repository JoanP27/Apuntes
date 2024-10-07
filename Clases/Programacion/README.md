<a href="https://joanp27.github.io/Apuntes/"><< volver atras</a>
# Unidades

### string

```C#
"Hello World"
```
### char (Character)
```C#
'e'
```

### int

```C#
1
```

### bool

```C#
true

false
```

# Expresiones


### Using System

sirve para no tener que volver a usar el Termino ```System``` en el codigo de nuevo, asi a la hora de escribir codigo nos ahorramos

```C#
// sin usar system
using system;
Class Test
{
    static void Main()
    {
        System.Console.WriteLine("Hello World")
    }
}
```

```C#
// usando system
using system;
Class Test
{
    static void Main()
    {
        Console.WriteLine("Hello World")
    }
}
```

### Read Line

sirve para no tener que volver a usar el Termino ```System``` en el codigo de nuevo, asi a la hora de escribir codigo nos ahorramos

```C#
using system;
Class Test
{
    static void Main()
    {
        Console.WriteLine("Hello World")
    }
}
```
<br>
<br>

# Condiciones
### Operador ternario

funciona como un condicional de una sola linea, si la condicion da ``true`` se asignara la primera opcion, si da ``false`` se asignara la segunda opcion a la variable num1

```C#
num1 = condicion ? true : false
```

### Switch

se usan varias opciones, siempre se debe poner un ``break`` para finalizar la expresion en cada una de las opciones, o ``goto`` para cambiar a otra opcion del ``case``

```C#
switch (expresión)
{
case valor1:
    sentencia1;
    break;
case valor2:
    sentencia2;
    sentencia2b;
    break;
case valor3:
    goto case valor1;
...
case valorN:
    sentenciaN;
    break;
default:
    otraSentencia;
    break;
}
```
