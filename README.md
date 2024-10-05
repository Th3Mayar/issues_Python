### Issue 1: Modified FizzBuzz
#### Función: `fizz_buzz_mod(n)`
**Descripción:**
Esta función genera una lista de números del 1 al `n`, pero con modificaciones:
- Si el número es múltiplo de 3, se reemplaza por `"Fizz"`.
- Si el número es múltiplo de 5, se reemplaza por `"Buzz"`.
- Si el número es múltiplo de 3 y 5, se reemplaza por `"FizzBuzz"`.
- Si el número no es múltiplo de 3 ni de 5, se mantiene el número.

**Parámetros:**
- `n` (int): Un número entero positivo que define el límite superior de la lista.

**Retorno:**
- Una lista con números y cadenas según las reglas de FizzBuzz.

**Ejemplo de uso:**
```python
fizz_buzz_mod(15)
```
Salida:
```python
[1, 2, 'Fizz', 4, 'Buzz', 'Fizz', 7, 8, 'Fizz', 'Buzz', 11, 'Fizz', 13, 14, 'FizzBuzz']
```

---

### Issue 2: Find the Second Longest Word
#### Función: `segunda_palabra_mas_larga(texto)`
**Descripción:**
Esta función devuelve la segunda palabra más larga en una cadena de texto. Si hay varias palabras con la misma longitud, devuelve la que aparezca primero en el texto. Si solo hay una palabra, devuelve esa palabra.

**Parámetros:**
- `texto` (str): Una cadena de texto que contiene varias palabras separadas por espacios.

**Retorno:**
- Una cadena de texto que representa la segunda palabra más larga en la cadena.

**Ejemplo de uso:**
```python
segunda_palabra_mas_larga("In programming, practice makes perfect")
```
Salida:
```python
'practice'
```

---

### Issue 3: Adding Submatrices of a Matrix
#### Función: `sumar_submatrices(matriz)`
**Descripción:**
Esta función calcula las sumas de todas las posibles submatrices cuadradas de una matriz dada. Considera submatrices de diferentes tamaños (desde 1x1 hasta `n x n`), y devuelve una lista con las sumas de estas submatrices.

**Parámetros:**
- `matriz` (list of lists): Una matriz cuadrada `n x n` de números enteros.

**Retorno:**
- Una lista que contiene las sumas de todas las submatrices posibles dentro de la matriz.

**Ejemplo de uso:**
```python
matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
sumar_submatrices(matriz)
```
Salida:
```python
[1, 2, 3, 4, 5, 6, 7, 8, 9, 12, 16, 24, 28, 45]
```

---

### Ejecución de Ejemplos

**Ejemplo de ejecución:**
```python
fizzbuzz_result = fizz_buzz_mod(15)
segunda_palabra_result = segunda_palabra_mas_larga("In programming, practice makes perfect")
matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
submatrices_result = sumar_submatrices(matriz)

print("Issue 1: Modified FizzBuzz")
print(fizzbuzz_result)

print("\nIssue 2: Second longest word")
print(segunda_palabra_result)

print("\nIssue 3: Submatrix sums")
print(submatrices_result)
```

---
