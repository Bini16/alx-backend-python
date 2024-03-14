0x00. Python - Variable Annotations
AUTHOR: Bini16(abrahambiniyam6@gmail.com)
TASKS
0. Basic annotations - add
Write a type-annotated function add that takes a float a and a float b as arguments and returns their sum as a float.
GitHub repository: alx-backend-python
Directory: 0x00-python_variable_annotations
File: 0-add.py
1. Basic annotations - concat
Write a type-annotated function concat that takes a string str1 and a string str2 as arguments and returns a concatenated string
GitHub repository: alx-backend-python
Directory: 0x00-python_variable_annotations
File: 1-concat.py
2. Basic annotations - floor
Write a type-annotated function floor which takes a float n as argument and returns the floor of the float.
GitHub repository: alx-backend-python
Directory: 0x00-python_variable_annotations
File: 2-floor.py
3. Basic annotations - to string
Write a type-annotated function to_str that takes a float n as argument and returns the string representation of the float.
GitHub repository: alx-backend-python
Directory: 0x00-python_variable_annotations
File: 3-to_str.py
4. Define variables
Define and annotate the following variables with the specified values:
a, an integer with a value of 1
pi, a float with a value of 3.14
i_understand_annotations, a boolean with a value of True
school, a string with a value of “Holberton”
GitHub repository: alx-backend-python
Directory: 0x00-python_variable_annotations
File: 4-define_variables.py
5. Complex types - list of floats
Write a type-annotated function sum_list which takes a list input_list of floats as argument and returns their sum as a float.
GitHub repository: alx-backend-python
Directory: 0x00-python_variable_annotations
File: 5-sum_list.py
6. Complex types - mixed list
Write a type-annotated function sum_mixed_list which takes a list mxd_lst of integers and floats and returns their sum as a float.
GitHub repository: alx-backend-python
Directory: 0x00-python_variable_annotations
File: 6-sum_mixed_list.py
7. Complex types - string and int/float to tuple
Write a type-annotated function to_kv that takes a string k and an int OR float v as arguments and returns a tuple. The first element of the tuple is the string k. The second element is the square of the int/float v and should be annotated as a float.
GitHub repository: alx-backend-python
Directory: 0x00-python_variable_annotations
File: 7-to_kv.py
8. Complex types - functions
Write a type-annotated function make_multiplier that takes a float multiplier as argument and returns a function that multiplies a float by multiplier.
GitHub repository: alx-backend-python
Directory: 0x00-python_variable_annotations
File: 8-make_multiplier.py
9. Let's duck type an iterable object
Annotate the below function’s parameters and return values with the appropriate types
def element_length(lst):
    return [(i, len(i)) for i in lst]
GitHub repository: alx-backend-python
Directory: 0x00-python_variable_annotations
File: 9-element_length.py
10. Duck typing - first element of a sequence
Augment the following code with the correct duck-typed annotations:
# The types of the elements of the input are not know
def safe_first_element(lst):
    if lst:
        return lst[0]
    else:
        return None
GitHub repository: alx-backend-python
Directory: 0x00-python_variable_annotations
File: 100-safe_first_element.py
11. More involved type annotations
Given the parameters and the return values, add type annotations to the function
Hint: look into TypeVar

def safely_get_value(dct, key, default = None):
    if key in dct:
        return dct[key]
    else:
        return default
GitHub repository: alx-backend-python
Directory: 0x00-python_variable_annotations
File: 101-safely_get_value.py
12. Type Checking
Use mypy to validate the following piece of code and apply any necessary changes.

def zoom_array(lst: Tuple, factor: int = 2) -> Tuple:
    zoomed_in: Tuple = [
        item for item in lst
        for i in range(factor)
    ]
    return zoomed_in


array = [12, 72, 91]

zoom_2x = zoom_array(array)

zoom_3x = zoom_array(array, 3.0)
GitHub repository: alx-backend-python
Directory: 0x00-python_variable_annotations
File: 102-type_checking.py
