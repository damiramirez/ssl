# Hello, World!

## Ejercicios

1. Indique en el readme.md el compilador seleccionado.
2. Pruebe el compilador con un programa hello.c que envíe a stdout la línea Hello, World! o similar.
3. Ejecute el programa y verifique que la salida es la esperada.
4. Ejecute el programa con la salida redireccionada a un archivo output.txt; verifique su contenido

## Resolución

```
  ssl/00-CHelloWorld
  ❯ gcc --version
  gcc (GCC) 13.2.1 20230801
  Copyright (C) 2023 Free Software Foundation, Inc.
  This is free software; see the source for copying conditions.  There is NO
  warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

  ssl/00-CHelloWorld
  ❯ gcc -std=c11 hello.c -o hello

  ssl/00-CHelloWorld
  ❯ ./hello
  Hello, World!

  ssl/00-CHelloWorld
  ❯ ./hello > output.txt

  ssl/00-CHelloWorld
  ❯ cat output.txt
  Hello, World!
```
