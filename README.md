![](https://user-images.githubusercontent.com/970858/63474771-d6734700-c469-11e9-83bb-9429da563909.png)

# LAB-Python-Data-Structures-and-Functions

## Introduction

> ***Note:*** _This can be a pair programming activity or done independently._

With what we have learned about functions and data structures we will be able to solve new problems and challenges in python, let's see how it goes.

## Requirements

- [Learn how to fork this repo](https://guides.github.com/activities/forking/)
- Clone this repo into your `code/labs` folder


---
## Iteration 1 / **Add_the_positives**

Create a function in which you get a tuple of numbers, and return the sum of all positive numbers:

input => output
[1,-4,7,-2, -7,13] => 1 + 7 + 13 = 21


## Iteration 2

### Iteration 2.1 / **Count_the_color**

Write a function that asks the user for a color and counts the number of times it appears in the list.

["red", "blue", "red", "white", “green”, “black”, “orange”, “black”, “red”]

input => output

blue => the color blue appears 2 times.

### Iteration 2.2 / **Count_the_color_multidimensional** 

try now to search in a multidimensional list

[
["red", "blue", "red", "white"],
["yellow", "red", "blue", "green"],
["white", "red", "blue", "yellow"],
["green", "black", "orange", "orange"]
]

## Iteration 3 / **strings_order**

Write a function that takes a list of strings as an argument and returns a sorted list containing the same strings, ordered from shortest to longest.

input => output
["Multidimensional", "Earth", "Try", "Banana"] => ["Try", "Earth", "Banana", "Multidimensional"]


## Iteration 4
### iteration 4.1 / **Join_the_dictionary**

This function has to return the join of the firstName and the lastName attributes of the person argument with a space between them.
input --> output
{ firstName : 'Luis' , lastName: 'Burón' } => "Luis Burón"

### Iteration 4.2 / **Fix_the_string**

This function has to return the join of the firstName and the lastName attributes of the person argument with a space between them. Also it has to transform the first letter of both values to upperCase if necessary.

input --> output
{ firstName : 'Luis' , lastName: 'burón' } => "Luis Burón"

### Iteration 4.3 / **Fix_the_dictionary**

This function has to return the join of the firstName and the lastName attributes of the person argument with a space between them. Also it has to transform the first letter of every word of both values to upperCase if it is necessary. In this case, you can receive as lastName or firstName value a compound name.

input => output
{ firstName : 'Luis Álvaro' , lastName: 'burón mejías' } => "Luis Álvaro Burón Mejías"

## BONUS - **get_best_students**

Create a function get_best_students that takes a dictionary of students. The function must return a dictionary with the emails and the average of the students. These students must have a average value of 9 or more in their subjects. The output have to be orderer by average mark.
For example:
getBestStudents([
  {name : "Luis", age : 20, email : "luis@gmail.com", subjectsMarks : [9, 8, 10, 5 , 10]},
  {name : "Luigi", age : 14, email : "luigi@gmail.com", subjectsMarks : [9, 8, 10, 9 , 10]},
  {name : "Mario", age : 25, email : "mario@gmail.com", subjectsMarks : [9, 10, 10, 9, 10]},
])

returns [
  {email : "mario@gmail.com", average : 9.6 }, 
  {email : "luis@gmail.com", average : 9.2 }
 ]

## Submission

Upon completion, run the following commands:

```
$ git add .
$ git commit -m "done"
$ git push origin main
```

Then create a Pull Request!!

![happy_coding](https://user-images.githubusercontent.com/970858/63899010-c23fc480-c9ea-11e9-84a2-542907e42362.png)
