
# LAB - Python Data Structures (Updated)

## Introduction

In this lab, you will practice working with various **Data Structures** in Python, including **Lists**, **Tuples**, **Sets**, and **Dictionaries**. You will also reinforce your understanding of functions by solving real-world inspired tasks. The goal is to progressively build up your skills and apply these core concepts efficiently.

> ***Note:*** _This can be a pair programming activity or done independently._

## Requirements

- [Learn how to fork this repo](https://guides.github.com/activities/forking/)
- Clone this repo into your `code/labs` folder

---

## Iteration 1 / **Create a Shopping List with Quantities**

Create a function that receives the name of a product and its quantity, and adds it to a list of products, each containing a name and quantity.

```python
# Example
add_product([['apples', 4], ['bananas', 6]], 'milk', 2)
```

## Iteration 2 / **Sum All Positive Numbers in Nested Lists**

Create a function that receives a matrix (list of lists) of numbers and returns the sum of all positive numbers.

```python
input => output

[[1, -4], [7, -2], [-7, 13]] => 21
```

## Iteration 3 / **Calculate Average from Tuples**

Write a function that takes a tuple of numbers and returns the average of all elements.

```python
input => output

(2, 3, 5) => 3.33
```

## Iteration 4 / **Convert List to Set, Then Return Sorted List**

Create a function that takes a list with duplicates, converts it to a set (to remove duplicates), and returns the sorted list.

```python
input => output

['apple', 'banana', 'apple', 'orange'] => ['apple', 'banana', 'orange']
```

## Iteration 5 / **Find Item in Set and Return Index in Original List**

Write a function that checks if a certain item exists in a set, and returns its index in the original list before conversion to set. If the item is not found, return -1.

```python
input => output

{'apple', 'banana', 'orange'}, 'banana' => 1
```

## Iteration 6 / **Calcular el Total de Precios en un Diccionario de Productos**

Crea una función que reciba un diccionario donde las claves sean nombres de productos y los valores sean listas de dos elementos: la cantidad de productos comprados y su precio unitario. La función debe calcular y devolver el **precio total** de todos los productos en el diccionario.

```python
# Ejemplo de entrada
productos = {
    'apple': [4, 1.5],  # 4 manzanas a 1.5 cada una
    'banana': [6, 0.9],  # 6 bananas a 0.9 cada una
    'milk': [2, 1.2]  # 2 botellas de leche a 1.2 cada una
}

# Llamada a la función
total = calcular_total(productos)

# El resultado debe ser:
# Total: 4 * 1.5 + 6 * 0.9 + 2 * 1.2 = 6 + 5.4 + 2.4 = 13.8
print(total)  # Output: 13.8
```

## Iteration 7 / **Modify Prices in a Dictionary**

Create a function that modifies the price of a product in a dictionary. If the product does not exist, add it to the dictionary with the new price.

```python
modify_price({'apple': 1.5, 'banana': 0.9}, 'milk', 1.3) => {'apple': 1.5, 'banana': 0.9, 'milk': 1.3}
```

## Iteration 8 / **Sort List of Tuples by Second Value**

Write a function that receives a list of tuples where each tuple contains a product and its price. Sort the list by price (second value).

```python
input => output

[('apple', 1.5), ('banana', 0.9), ('milk', 1.3)] => [('banana', 0.9), ('milk', 1.3), ('apple', 1.5)]
```

## Iteration 9 / **Nested Lists**

Write a function that takes a nested list (a list of lists) and prints the second element from each inner list.

```python
input => output

[[1, 2], [3, 4], [5, 6]] => 2 4 6
```

## Iteration 10 / **Find Maximum in Nested Dictionary**

Create a function that takes a dictionary of students with a list of grades and returns the student with the highest average.

```python
# Example
find_best_student({
  'Alice': [85, 90, 88],
  'Bob': [78, 81, 79],
  'Charlie': [92, 95, 91]
}) => 'Charlie'
```

## BONUS 1 / **List Comprehensions**

Create a list of squares of numbers from 0 to 9 using a list comprehension.

```python
squares = [x**2 for x in range(10)]
print(squares)
```

## BONUS 2 / **Dictionary of Even Numbers**

Create a dictionary where the keys are numbers from 1 to 10 and the values are `True` if the number is even and `False` if it is odd.

```python
# Example
{1: False, 2: True, 3: False, 4: True, 5: False, 6: True, 7: False, 8: True, 9: False, 10: True}
```

## BONUS 3 / **Tuple Operations**

Create a function that takes two tuples and concatenates them into one larger tuple.

```python
input => output

(1, 2, 3), (4, 5, 6) => (1, 2, 3, 4, 5, 6)
```

## Submission

Upon completion, run the following commands:

```bash
$ git add .
$ git commit -m "done"
$ git push origin main
```

Then create a Pull Request!

Happy coding!
