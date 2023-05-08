<link rel="stylesheet" type="text/css" href="styles.css">





# python_problems
hackers rank problems

# NOTES: 
1. {:.2f}".format() --- formating to 2 decimal points
2. set(dic.values()) --- to get unique values
3. (map(float, line) ---- to map each value in a iterable 
4. ### List Comprehensions:

List comprehensions are a concise way of creating lists in Python. They allow you to create a new list from an existing one by applying a transformation to each element in the original list. List comprehensions are written in a single line of code, making them easy to read and understand. The syntax for a list comprehension is as follows:

```python
new_list = [expression for item in list if condition]
```
Here, expression is the transformation to apply to each element in the original list. item is a variable that takes on the value of each element in the original list. condition is an optional statement that filters the elements in the original list before they are transformed. The resulting new_list is a transformed version of the original list.

5. ### Sets:

A set is an unordered collection of unique elements in Python. Sets are useful for tasks that involve comparing or removing duplicates from lists. You can create a set using curly braces {} or the set() function. Here is an example of how to create a set:
```python
my_set = {1, 2, 3, 4, 5}
print(my_set)  # Output: {1, 2, 3, 4, 5}
```
you can add elements to a set using the add() method, and you can remove elements using the remove()

**You can use the | operator to perform a union operation **
![union operation](https://user-images.githubusercontent.com/95610357/236809639-539f4cfe-6efb-435e-8e81-ac53462234c6.png)

<a href="https://www.hackerrank.com/challenges/py-set-union/problem?isFullScreen=true" style="color: #0366d6; text-decoration: none;"><b>the & operator to perform an intersection operation</b></a>.
![intersection operation](https://user-images.githubusercontent.com/95610357/236809722-58aeec73-4ec4-4476-8a33-195c9d81dab0.png)

**the - operator to perform a difference operation **
![difference operation](https://user-images.githubusercontent.com/95610357/236809823-732b3108-7a2e-4d14-84d0-cc79335d4a1b.png)

**the ^ operator to perform an .symmetric_difference()**
![symmetric_difference](https://user-images.githubusercontent.com/95610357/236809506-75e956d5-4959-4e42-b86c-4237d04cba81.png)
>>> s = set("Hacker")
>>> print s.difference("Rank")
set(['c', 'r', 'e', 'H'])

>>> print s.difference(set(['R', 'a', 'n', 'k']))
set(['c', 'r', 'e', 'H'])

>>> print s.difference(['R', 'a', 'n', 'k'])
set(['c', 'r', 'e', 'H'])

>>> print s.difference(enumerate(['R', 'a', 'n', 'k']))
set(['a', 'c', 'r', 'e', 'H', 'k'])

>>> print s.difference({"Rank":1})
set(['a', 'c', 'e', 'H', 'k', 'r'])

>>> s - set("Rank")
set(['H', 'c', 'r', 'e']

| Syntax | Description |
| --- | --- |
| `new_list = [expression for item in list if condition]` | Creates a new list by applying an expression to each item in an existing list that meets a certain condition |


6.  



</body>
</html>
