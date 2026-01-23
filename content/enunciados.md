# Ejercicios Complementarios de Programación en Python

Este documento contiene 50 ejercicios adicionales organizados por nivel de dificultad.

## Nivel 1: Base

### Ejercicio 1.1: Suma de dígitos
**Tags**: `strings` `conversión` `acumulador` `lazos`

Escribí una función que reciba un número entero y retorne la suma de sus dígitos.

#### Ejemplo
```python
suma_digitos(1234)  # Retorna: 10 (1+2+3+4)
suma_digitos(999)   # Retorna: 27
```

### Ejercicio 1.2: Contar vocales
**Tags**: `strings` `contador` `lazos` `condicionales`

Creá una función que cuente cuántas vocales (a, e, i, o, u) hay en un texto dado.
La función debe ser case-insensitive (no distingue mayúsculas/minúsculas).

#### Ejemplo
```python
contar_vocales("Hola Mundo")    # Retorna: 4
contar_vocales("Python")        # Retorna: 1
```

### Ejercicio 1.3: Invertir string
**Tags**: `strings` `slicing` `métodos`

Escribí una función que reciba un string y lo retorne invertido.

#### Ejemplo
```python
invertir("Python")    # Retorna: "nohtyP"
invertir("12345")     # Retorna: "54321"
```


### Ejercicio 1.4: Números pares en rango
**Tags**: `listas` `range` `comprehension` `condicionales`

Creá una función que retorne una lista con todos los números pares entre dos valores dados (inclusive).

#### Ejemplo
```python
pares_en_rango(1, 10)   # Retorna: [2, 4, 6, 8, 10]
pares_en_rango(5, 15)   # Retorna: [6, 8, 10, 12, 14]
```

### Ejercicio 1.5: Palíndromo
**Tags**: `strings` `comparación` `slicing`

Escribí una función que determine si una palabra es un palíndromo (se lee igual de izquierda a derecha que de derecha a izquierda).

#### Ejemplo
```python
es_palindromo("radar")    # Retorna: True
es_palindromo("python")   # Retorna: False
es_palindromo("Ana")      # Retorna: True (ignorando mayúsculas)
```

### Ejercicio 1.6: Buscar elemento
**Tags**: `listas` `búsqueda` `condicionales` `lazos`

Implementá una función que busque un elemento en una lista y retorne su índice.
Si no lo encuentra, retorna -1.

#### Ejemplo
```python
buscar([10, 20, 30, 40], 30)   # Retorna: 2
buscar([10, 20, 30, 40], 99)   # Retorna: -1
```

### Ejercicio 1.7: Tabla de multiplicar
**Tags**: `lazos` `formato` `operadores`

Creá una función que imprima la tabla de multiplicar de un número dado, del 1 al 10.

#### Ejemplo
```python
tabla_multiplicar(5)
# Imprime:
# 5 x 1 = 5
# 5 x 2 = 10
# ...
# 5 x 10 = 50
```

### Ejercicio 1.8: Eliminar duplicados
**Tags**: `listas` `sets` `conversión`

Escribí una función que reciba una lista y retorne una nueva lista sin elementos duplicados, manteniendo el orden original.

#### Ejemplo
```python
sin_duplicados([1, 2, 2, 3, 1, 4])   # Retorna: [1, 2, 3, 4]
sin_duplicados(['a', 'b', 'a', 'c']) # Retorna: ['a', 'b', 'c']
```



### Ejercicio 1.9: Capitalizar palabras
**Tags**: `strings` `métodos` `split` `join`

Creá una función que capitalice la primera letra de cada palabra en un texto.

#### Ejemplo
```python
capitalizar("hola mundo python")   # Retorna: "Hola Mundo Python"
capitalizar("buenos días")         # Retorna: "Buenos Días"
```



### Ejercicio 1.10: Números en rango
**Tags**: `listas` `filtrado` `comprehension`

Escribí una función que reciba una lista de números y dos límites, y retorne los números que están dentro del rango (inclusive).

#### Ejemplo
```python
en_rango([1, 5, 10, 15, 20], 5, 15)   # Retorna: [5, 10, 15]
en_rango([3, 7, 2, 9, 1], 2, 7)       # Retorna: [3, 7, 2]
```



### Ejercicio 1.11: Frecuencia de caracteres
**Tags**: `strings` `diccionarios` `contador`

Creá una función que cuente cuántas veces aparece cada carácter en un string.

#### Ejemplo
```python
frecuencia("hello")
# Retorna: {'h': 1, 'e': 1, 'l': 2, 'o': 1}
```



### Ejercicio 1.12: Máximo y mínimo
**Tags**: `listas` `comparación` `tuplas`

Escribí una función que retorne tanto el valor máximo como el mínimo de una lista en una tupla.

#### Ejemplo
```python
max_min([3, 7, 1, 9, 2])   # Retorna: (9, 1)
max_min([10, 10, 10])      # Retorna: (10, 10)
```



### Ejercicio 1.13: Aplanar lista
**Tags**: `listas` `anidado` `comprehension`

Creá una función que "aplane" una lista de listas en una sola lista.

#### Ejemplo
```python
aplanar([[1, 2], [3, 4], [5]])   # Retorna: [1, 2, 3, 4, 5]
aplanar([[1], [], [2, 3]])       # Retorna: [1, 2, 3]
```


### Ejercicio 1.14: Reemplazar valores
**Tags**: `listas` `modificación` `condicionales`

Escribí una función que reemplace todas las apariciones de un valor por otro en una lista.

#### Ejemplo
```python
reemplazar([1, 2, 3, 2, 4], 2, 99)   # Retorna: [1, 99, 3, 99, 4]
reemplazar(['a', 'b', 'a'], 'a', 'z') # Retorna: ['z', 'b', 'z']
```



### Ejercicio 1.15: Suma acumulativa
**Tags**: `listas` `acumulador` `comprehension`

Creá una función que retorne una lista con las sumas acumulativas de otra lista.

#### Ejemplo
```python
suma_acumulativa([1, 2, 3, 4])   # Retorna: [1, 3, 6, 10]
suma_acumulativa([10, -5, 3])    # Retorna: [10, 5, 8]
```



### Ejercicio 1.16: Contar palabras
**Tags**: `strings` `split` `diccionarios`

Escribí una función que cuente cuántas veces aparece cada palabra en un texto.

#### Ejemplo
```python
contar_palabras("hola mundo hola")
# Retorna: {'hola': 2, 'mundo': 1}
```



### Ejercicio 1.17: Rotar lista
**Tags**: `listas` `slicing` `concatenación`

Creá una función que rote una lista n posiciones a la derecha.

#### Ejemplo
```python
rotar([1, 2, 3, 4, 5], 2)   # Retorna: [4, 5, 1, 2, 3]
rotar([1, 2, 3], 1)         # Retorna: [3, 1, 2]
```


### Ejercicio 1.18: Números primos
**Tags**: `matemática` `lazos` `condicionales`

Escribí una función que determine si un número es primo.

#### Ejemplo
```python
es_primo(7)    # Retorna: True
es_primo(10)   # Retorna: False
es_primo(1)    # Retorna: False
```


### Ejercicio 1.19: Común en listas
**Tags**: `listas` `sets` `intersección`

Creá una función que encuentre los elementos comunes entre dos listas.

#### Ejemplo
```python
comunes([1, 2, 3, 4], [3, 4, 5, 6])   # Retorna: [3, 4]
comunes(['a', 'b'], ['b', 'c'])       # Retorna: ['b']
```


### Ejercicio 1.20: Alternar mayúsculas
**Tags**: `strings` `métodos` `lazos`

Escribí una función que alterne entre mayúsculas y minúsculas en cada carácter.

#### Ejemplo
```python
alternar("hello")   # Retorna: "HeLlO"
alternar("Python")  # Retorna: "PyThOn"
```


## Nivel 2: Medio

### Ejercicio 2.1: Ordenar por longitud
**Tags**: `listas` `strings` `sorting` `funciones`

Creá una función que ordene una lista de strings por su longitud (de menor a mayor).

#### Ejemplo
```python
ordenar_por_longitud(["Python", "a", "es", "genial"])
# Retorna: ["a", "es", "Python", "genial"]
```

### Ejercicio 2.2: Agrupar por paridad
**Tags**: `listas` `diccionarios` `clasificación`

Escribí una función que agrupe números en pares e impares.

#### Ejemplo
```python
agrupar_paridad([1, 2, 3, 4, 5])
# Retorna: {'pares': [2, 4], 'impares': [1, 3, 5]}
```



### Ejercicio 2.3: Matriz transpuesta
**Tags**: `listas` `matrices` `anidado` `comprehension`

Creá una función que transponga una matriz (intercambie filas por columnas).

#### Ejemplo
```python
transponer([[1, 2, 3], [4, 5, 6]])
# Retorna: [[1, 4], [2, 5], [3, 6]]
```

### Ejercicio 2.4: Fusionar diccionarios
**Tags**: `diccionarios` `merge` `operadores`

Escribí una función que fusione dos diccionarios. Si hay claves repetidas, suma sus valores.

#### Ejemplo
```python
fusionar({'a': 1, 'b': 2}, {'b': 3, 'c': 4})
# Retorna: {'a': 1, 'b': 5, 'c': 4}
```


### Ejercicio 2.5: Palabras más largas
**Tags**: `strings` `listas` `filtrado` `max`

Creá una función que encuentre todas las palabras de longitud máxima en un texto.

#### Ejemplo
```python
palabras_mas_largas("Python es un lenguaje genial")
# Retorna: ["lenguaje"]
```


### Ejercicio 2.6: Diferencia simétrica
**Tags**: `sets` `listas` `operaciones`

Implementá una función que encuentre la diferencia simétrica entre dos listas (elementos que están en una u otra, pero no en ambas).

#### Ejemplo
```python
diferencia_simetrica([1, 2, 3], [2, 3, 4])   # Retorna: [1, 4]
```



### Ejercicio 2.7: Filtrar por condición
**Tags**: `listas` `funciones` `filter` `lambda`

Creá una función que filtre elementos de una lista según una condición dada como función.

#### Ejemplo
```python
filtrar([1, 2, 3, 4, 5], lambda x: x > 3)   # Retorna: [4, 5]
filtrar(["a", "ab", "abc"], lambda x: len(x) > 1)  # Retorna: ["ab", "abc"]
```


### Ejercicio 2.8: Mapeo de valores
**Tags**: `listas` `diccionarios` `transformación`

Escribí una función que aplique un diccionario de mapeo a una lista de valores.

#### Ejemplo
```python
mapear([1, 2, 3], {1: 'uno', 2: 'dos', 3: 'tres'})
# Retorna: ['uno', 'dos', 'tres']
```


### Ejercicio 2.9: Sublistas de tamaño n
**Tags**: `listas` `slicing` `generadores`

Creá una función que divida una lista en sublistas de tamaño n.

#### Ejemplo
```python
dividir([1, 2, 3, 4, 5, 6, 7], 3)
# Retorna: [[1, 2, 3], [4, 5, 6], [7]]
```



### Ejercicio 2.10: Formato de número
**Tags**: `strings` `formato` `números`

Implementá una función que formatee un número con separadores de miles.

#### Ejemplo
```python
formatear_numero(1234567)   # Retorna: "1,234,567"
formatear_numero(1000)      # Retorna: "1,000"
```



### Ejercicio 2.11: Validar paréntesis
**Tags**: `strings` `stack` `validación`

Creá una función que valide si los paréntesis en una expresión están balanceados.

#### Ejemplo
```python
parentesis_balanceados("(())")      # Retorna: True
parentesis_balanceados("(()")       # Retorna: False
parentesis_balanceados("()())")     # Retorna: False
```



### Ejercicio 2.12: Media móvil
**Tags**: `listas` `estadística` `ventana`

Escribí una función que calcule la media móvil de una lista con ventana de tamaño k.

#### Ejemplo
```python
media_movil([1, 2, 3, 4, 5], 3)
# Retorna: [2.0, 3.0, 4.0]  # (1+2+3)/3, (2+3+4)/3, (3+4+5)/3
```


### Ejercicio 2.13: Comprimir string
**Tags**: `strings` `contador` `formato`

Creá una función que comprima un string contando caracteres consecutivos repetidos.

#### Ejemplo
```python
comprimir("aaabbc")    # Retorna: "a3b2c1"
comprimir("abc")       # Retorna: "a1b1c1"
```


### Ejercicio 2.14: Anagramas
**Tags**: `strings` `sorting` `comparación`

Implementá una función que determine si dos palabras son anagramas.

#### Ejemplo
```python
son_anagramas("listen", "silent")   # Retorna: True
son_anagramas("hello", "world")     # Retorna: False
```


### Ejercicio 2.15: Fibonacci
**Tags**: `recursión` `matemática` `secuencias`

Creá una función que genere los primeros n números de Fibonacci.

#### Ejemplo
```python
fibonacci(7)   # Retorna: [0, 1, 1, 2, 3, 5, 8]
```



### Ejercicio 2.16: Partición de lista
**Tags**: `listas` `filtrado` `clasificación`

Escribí una función que particione una lista en dos según una condición.

#### Ejemplo
```python
particionar([1, 2, 3, 4, 5], lambda x: x % 2 == 0)
# Retorna: ([2, 4], [1, 3, 5])  # (cumple, no cumple)
```


### Ejercicio 2.17: Producto cartesiano
**Tags**: `listas` `anidado` `comprehension`

Creá una función que genere el producto cartesiano de dos listas.

#### Ejemplo
```python
producto_cartesiano([1, 2], ['a', 'b'])
# Retorna: [(1, 'a'), (1, 'b'), (2, 'a'), (2, 'b')]
```


### Ejercicio 2.18: Índices de subcadena
**Tags**: `strings` `búsqueda` `listas`

Implementá una función que encuentre todos los índices donde aparece una subcadena.

#### Ejemplo
```python
indices_subcadena("ababa", "ab")   # Retorna: [0, 2]
indices_subcadena("hello", "l")    # Retorna: [2, 3]
```



### Ejercicio 2.19: Pivotar lista
**Tags**: `listas` `partición` `sorting`

Creá una función que "pivotee" una lista: menores o iguales a un valor a la izquierda, mayores a la derecha.

#### Ejemplo
```python
pivotar([3, 7, 1, 9, 2], 5)   # Retorna: [3, 1, 2, 7, 9]
```



### Ejercicio 2.20: Agrupar por propiedad
**Tags**: `listas` `diccionarios` `agrupación`

Escribí una función que agrupe elementos según una propiedad extraída por una función.

#### Ejemplo
```python
agrupar(['abc', 'a', 'ab', 'abcd'], len)
# Retorna: {1: ['a'], 2: ['ab'], 3: ['abc'], 4: ['abcd']}
```


## Nivel 3: Avanzado

### Ejercicio 3.1: Subsecuencia común más larga
**Tags**: `strings` `algoritmos` `programación dinámica`

Implementá una función que encuentre la longitud de la subsecuencia común más larga entre dos strings.

#### Ejemplo
```python
lcs("ABCDGH", "AEDFHR")   # Retorna: 3  # "ADH"
lcs("AGGTAB", "GXTXAYB")  # Retorna: 4  # "GTAB"
```


### Ejercicio 3.2: Generador de combinaciones
**Tags**: `listas` `recursión` `backtracking`

Creá una función que genere todas las combinaciones de k elementos de una lista.

#### Ejemplo
```python
combinaciones([1, 2, 3], 2)
# Retorna: [[1, 2], [1, 3], [2, 3]]
```



### Ejercicio 3.3: Evaluador de expresiones
**Tags**: `strings` `stack` `parsing`

Implementá una función que evalúe expresiones matemáticas simples en notación infija.

#### Ejemplo
```python
evaluar("3 + 5 * 2")      # Retorna: 13
evaluar("(1 + 2) * 3")    # Retorna: 9
```



### Ejercicio 3.4: Ordenamiento por mezcla
**Tags**: `listas` `algoritmos` `recursión` `sorting`

Implementá el algoritmo de ordenamiento merge sort.

#### Ejemplo
```python
merge_sort([38, 27, 43, 3, 9, 82, 10])
# Retorna: [3, 9, 10, 27, 38, 43, 82]
```



### Ejercicio 3.5: Generador de permutaciones
**Tags**: `listas` `recursión` `backtracking`

Implementá una función que genere todas las permutaciones de una lista.

#### Ejemplo
```python
permutaciones([1, 2, 3])
# Retorna: [[1,2,3], [1,3,2], [2,1,3], [2,3,1], [3,1,2], [3,2,1]]
```



### Ejercicio 3.6: Búsqueda binaria
**Tags**: `listas` `búsqueda` `algoritmos` `recursión`

Implementá el algoritmo de búsqueda binaria (la lista debe estar ordenada).

#### Ejemplo
```python
busqueda_binaria([1, 3, 5, 7, 9, 11], 7)   # Retorna: 3
busqueda_binaria([1, 3, 5, 7, 9, 11], 4)   # Retorna: -1
```


### Ejercicio 3.7: Validador de sudoku
**Tags**: `matrices` `validación` `sets`

Creá una función que valide si una matriz 9x9 representa un sudoku válido.

#### Ejemplo
```python
# Tablero válido (ejemplo parcial)
tablero = [
    [5,3,0,0,7,0,0,0,0],
    [6,0,0,1,9,5,0,0,0],
    [0,9,8,0,0,0,0,6,0],
    [8,0,0,0,6,0,0,0,3],
    [4,0,0,8,0,3,0,0,1],
    [7,0,0,0,2,0,0,0,6],
    [0,6,0,0,0,0,2,8,0],
    [0,0,0,4,1,9,0,0,5],
    [0,0,0,0,8,0,0,7,9]
]
validar_sudoku(tablero)  # Retorna: True
```



### Ejercicio 3.8: Subsecuencia creciente más larga
**Tags**: `listas` `algoritmos` `programación dinámica`

Implementá una función que encuentre la longitud de la subsecuencia creciente más larga.

#### Ejemplo
```python
lis([10, 9, 2, 5, 3, 7, 101, 18])   # Retorna: 4  # [2,3,7,101]
```


### Ejercicio 3.9: Árbol de expresión
**Tags**: `árboles` `recursión` `evaluación`

Implementá una clase para representar y evaluar árboles de expresión matemática.

#### Ejemplo
```python
# Árbol para: (3 + 5) * 2
arbol = Nodo('*',
    Nodo('+', Nodo(3), Nodo(5)),
    Nodo(2)
)
arbol.evaluar()  # Retorna: 16
```
