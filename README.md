#Filter function and a lambda function to create a new list that contains only the strings with more than 5 characters.
fruits = ['apple', 'banana', 'cherry', 'date', 'elderberry']
filtered_fruits = list(filter(lambda fruit: len(fruit) > 5, fruits))
print(filtered_fruits)

# map function and a lambda function to double each number.
numbers = [2, 4, 6, 8, 10]
doubled_numbers = list(map(lambda x: x * 2, numbers))
print(doubled_numbers)

# reduce function to find the product of the doubled numbers.
from functools import reduce
doubled_numbers = list(map(lambda x: x * 2, numbers))
product_of_doubled_numbers = reduce(lambda x, y: x * y, doubled_numbers)
print(product_of_doubled_numbers)# Lamda_function_assignment
