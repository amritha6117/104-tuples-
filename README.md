# 104-tuples-
numbers=(10,20,30,40,50)
print("Original Tuple:",numbers)
print("First element:",numbers[0])
print("Last element:",numbers[-1])
print("Tuple slice (index 1 to 4):", numbers[1:5])
print("Count of 20:", numbers.count(20))
print("Index of 40:", numbers.index(40))
print("Length of tuple:", len(numbers))
print("Maximum value:", max(numbers))
print("Minimum value:", min(numbers))
print("Sum of tuple elements:", sum(numbers))
new_tuple = numbers + (60, 70, 80)
print("After concatenation:", new_tuple)
repeat_tuple = numbers * 2
print("Repeated Tuple:",numbers)


OUTPUT:


Original Tuple: (10, 20, 30, 40, 50)
First element: 10
Last element: 50
Tuple slice (index 1 to 4): (20, 30, 40, 50)
Count of 20: 1
Index of 40: 3
Length of tuple: 5
Maximum value: 50
Minimum value: 10
Sum of tuple elements: 150
After concatenation: (10, 20, 30, 40, 50, 60, 70, 80)
Repeated Tuple: (10, 20, 30, 40, 50)
