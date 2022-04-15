## Reorder Data in Log Files

- Use python comparator to compare items in a list
- If two elements have the same value on key_1, the comparison will carry on for the following keys, i.e. key_2 ... key_n.
Python sorting algorithm
>>> sorted(student_objects, key=lambda student: (student.grade, student.age))
[('john', 'A', 15), ('dave', 'B', 10), ('jane', 'B', 12)]

## Reverse a string
s = s[::-1] # reverse a string

## Equality of lists in Python
A straightforward way to check the equality of the two lists in Python is by using the equality == operator. When the equality == is used on the list type in Python, it returns True if the lists are equal and False if they are not.

## Binary Search

Peak index problem - binary search: if None found, then return left 
- ( if while(left < right) and mid = left+right+1 / 2
- Check mid - 1 and mid + 1
