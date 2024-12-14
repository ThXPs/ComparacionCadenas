# Comparación de Cadenas en C++ usando `strcmp`

Este programa compara dos cadenas de caracteres (`const char*`) utilizando la función `strcmp()` de la biblioteca estándar de C++. La comparación determina si las cadenas son iguales, si una es mayor o menor que la otra en orden lexicográfico.

## Descripción

La función `strcmp()` toma dos cadenas de caracteres como entrada y devuelve:
- `0` si las cadenas son iguales.
- Un valor negativo si la primera cadena es menor que la segunda.
- Un valor positivo si la primera cadena es mayor que la segunda.

## Estructura del Código

1. Define dos cadenas (`str1` y `str2`).
2. Utiliza la función `strcmp()` para comparar las cadenas.
3. Según el valor devuelto por `strcmp()`, determina e imprime el resultado de la comparación.

## Instrucciones

1. Guarda el código en un archivo llamado `ComparacionCadenas.cpp`.
2. Compila el código:
   ```bash
   g++ ComparacionCadenas.cpp -o ComparacionCadenas

