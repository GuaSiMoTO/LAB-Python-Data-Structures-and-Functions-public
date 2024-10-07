![](https://user-images.githubusercontent.com/970858/63474771-d6734700-c469-11e9-83bb-9429da563909.png)

# LAB-Python-Data-Structures-and-Functions

## Introduction

> ***Note:*** _This can be a pair programming activity or done independently._

With what we have learned about functions and data structures we will be able to solve new problems and challenges in python, let's see how it goes.

## Requirements

- [Learn how to fork this repo](https://guides.github.com/activities/forking/)
- Clone this repo into your `code/labs` folder


---

## Iteration 0 / **Add_the_positives**

Create a function in which you get a tuple of numbers, and return the sum of all positive numbers:
```
input => output

[1,-4,7,-2, -7,13] => 1 + 7 + 13 = 21
```

### Iteration 1 / **Count_the_color**

Write a function that asks the user for a color and counts the number of times it appears in the list.
```
["red", "blue", "red", "white", “green”, “black”, “orange”, “black”, “red”]

input => output

blue => the color blue appears 2 times.
```
### Iteration 2 / **Count_the_color_multidimensional** 

try now to search in a multidimensional list
```
[
["red", "blue", "red", "white"],
["yellow", "red", "blue", "green"],
["white", "red", "blue", "yellow"],
["green", "black", "orange", "orange"]
]
```
## Iteration 3 / **strings_order**

Write a function that takes a list of strings as an argument and returns a sorted list containing the same strings, ordered from shortest to longest.
```
input => output

["Multidimensional", "Earth", "Try", "Banana"] => ["Try", "Earth", "Banana", "Multidimensional"]
```

### Iteration 4 / **Fix_the_string**

This function has to return the join of the firstName and the lastName attributes of the person argument with a space between them. Also it has to transform the first letter of both values to upperCase if necessary.
```
input --> output

{ firstName : 'Luis' , lastName: 'burón' } => "Luis Burón"
```
### Iteration 5 / **Fix_the_dictionary**

This function has to return the join of the firstName and the lastName attributes of the person argument with a space between them. Also it has to transform the first letter of every word of both values to upperCase if it is necessary. In this case, you can receive as lastName or firstName value a compound name.
```
input => output

{ firstName : 'Luis Álvaro' , lastName: 'burón mejías' } => "Luis Álvaro Burón Mejías"
```


## Iteration 6 / **Calculate Total Prices in a Product Dictionary**

Create a function that receives a dictionary where the keys are product names and the values are lists containing two elements: the quantity of the product bought and the unit price. The function should calculate and return the **total price** of all the products in the dictionary.

```python
# Example input
products = {
    'apple': [4, 1.5],  # 4 apples at 1.5 each
    'banana': [6, 0.9],  # 6 bananas at 0.9 each
    'milk': [2, 1.2]  # 2 bottles of milk at 1.2 each
}

# Call the function
total = calculate_total(products)

# The result should be:
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

## Bonus 1 - **Find Maximum in Nested Dictionary**

Create a function that takes a dictionary of students with a list of grades and returns the student with the highest average.

```python
# Example
find_best_student({
  'Alice': [85, 90, 88],
  'Bob': [78, 81, 79],
  'Charlie': [92, 95, 91]
}) => 'Charlie'
```

## BONUS 2 - **get_best_students**

Create a function get_best_students that takes a dictionary of students. The function must return a dictionary with the emails and the average of the students. These students must have a average value of 9 or more in their subjects. The output have to be orderer by average mark.
For example:
```
getBestStudents([
  {name : "Luis", age : 20, email : "luis@gmail.com", subjectsMarks : [9, 8, 10, 5 , 10]},
  {name : "Luigi", age : 14, email : "luigi@gmail.com", subjectsMarks : [9, 8, 10, 9 , 10]},
  {name : "Mario", age : 25, email : "mario@gmail.com", subjectsMarks : [9, 10, 10, 9, 10]},
])

returns [
  {email : "mario@gmail.com", average : 9.6 }, 
  {email : "luis@gmail.com", average : 9.2 }
 ]
```
## Submission

Upon completion, run the following commands:

```
$ git add .
$ git commit -m "done"
$ git push origin main
```

Then create a Pull Request!!

![happy_coding](https://user-images.githubusercontent.com/970858/63899010-c23fc480-c9ea-11e9-84a2-542907e42362.png)
