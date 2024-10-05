### Issue 1: Modified FizzBuzz
#### Function: `fizz_buzz_mod(n)`
**Description:**
This function generates a list of numbers from 1 to `n`, with the following modifications:
- If the number is a multiple of 3, it is replaced by `"Fizz"`.
- If the number is a multiple of 5, it is replaced by `"Buzz"`.
- If the number is a multiple of both 3 and 5, it is replaced by `"FizzBuzz"`.
- If the number is neither a multiple of 3 nor 5, the number itself is included in the list.

**Parameters:**
- `n` (int): A positive integer that defines the upper limit of the list.

**Return:**
- A list containing numbers and strings according to FizzBuzz rules.

**Usage Example:**
```python
fizz_buzz_mod(15)
```
Output:
```python
[1, 2, 'Fizz', 4, 'Buzz', 'Fizz', 7, 8, 'Fizz', 'Buzz', 11, 'Fizz', 13, 14, 'FizzBuzz']
```

---

### Issue 2: Find the Second Longest Word
#### Function: `segunda_palabra_mas_larga(texto)`
**Description:**
This function returns the second longest word in a string. If multiple words have the same length, it returns the one that appears first in the string. If there is only one word, it returns that word.

**Parameters:**
- `texto` (str): A string containing several words separated by spaces.

**Return:**
- A string representing the second longest word in the text.

**Usage Example:**
```python
segunda_palabra_mas_larga("In programming, practice makes perfect")
```
Output:
```python
'practice'
```

---

### Issue 3: Adding Submatrices of a Matrix
#### Function: `sumar_submatrices(matriz)`
**Description:**
This function calculates the sums of all possible square submatrices within a given matrix. It considers submatrices of different sizes (from 1x1 to `n x n`), and returns a list with the sums of these submatrices.

**Parameters:**
- `matriz` (list of lists): A square `n x n` matrix of integers.

**Return:**
- A list containing the sums of all possible submatrices within the matrix.

**Usage Example:**
```python
matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
sumar_submatrices(matriz)
```
Output:
```python
[1, 2, 3, 4, 5, 6, 7, 8, 9, 12, 16, 24, 28, 45]
```

---

### Example Execution

**Execution Example:**
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
