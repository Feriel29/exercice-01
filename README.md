# exercice-01 

# Q1: Create a variable named `age` and assign your age to it.
Age = 22

# Q2: Create two variables, `city` and `country`, and assign your city and country to them.
city = "Algeries"
country = "Algeria"

# Q3: Combine `city` and `country` into a single string `location` and print it.
location = f"{city}, {country}"
print(location)

# Q4: Change the value of `age` to a different number and print it.
Age = 24
print(Age)

# Q5: Create a variable `height` and assign a float value representing your height in meters.
Height = 1.71

# Q6: Check and print the data type of the `height` variable using the `type()` function.
print(type(Height))

# Q7: Assign the value `True` to a variable named `is_student` and print the variable.
is_student = True
print(is_student)
# Q8: Create a variable `name` with your first name using double quotes and then another variable `surname` with your last name using single quotes. Combine them into `full_name`.
name = "FERIEL"
surname = 'FIFI'
full_name = f"{name} {surname}"
print(full_name)

# Q9: Create two variables `x` and `y` and assign them integer values. Swap their values without using a third variable.
x = 10
y = 5
x, y = y, x
print(x, y)

# Q10: Write a statement to update the `age` variable by adding 5 to it.
Age += 5
print(Age)

# Q11: Create a variable `length` and assign it the value 15. Create another variable `width` and assign it 10. Calculate the area of a rectangle using these variables and print the result.
length = 15
width = 10
area_rectangle = length * width
print(area_rectangle)

# Q12: Using the variables `base` and `height`, calculate the area of a triangle and print it. Assume `base = 8` and `height = 5`.
base = 8
Height = 5
area_triangle = 0.5 * base * height
print(area_triangle)

# Q13: Create a string variable `greeting` with the text "Hello" and another variable `recipient` with the text "World". Combine them with a space in between and print the result.
greeting = "Hello"
recipient = "World"
combined = f"{greeting} {recipient}"
print(combined)

# Q14: Create a boolean variable `is_active` and set it to `False`. Then change its value to `True` and print it.
is_active = False
is_active = True
print(is_active)

# Q15: Using f-strings, print a formatted message: "My name is [name] and I am [Age] years old." Replace [name] and [Age] with the appropriate variables.
print(f"My name is {name} and I am {Age} years old.")

# Q16: Create a variable `pi` and assign it the value 3.14159. Print the variable, ensuring it only shows 2 decimal places.
pi = 3.14159
print(f"{pi:.2f}")

# Q17: Assign the value of a mathematical expression (e.g., `2 * (3 + 5)`) to a variable and print it.
expression_value = 2 * (3 + 5)
print(expression_value)

# Q18: Create a variable `sentence` and assign it a sentence of your choice. Use slicing to print the first 5 characters.
sentence = "This is a sample sentence."
print(sentence[:5])

# Q19: Create a variable `number` with the value 100. Use an arithmetic operation to double its value and then print it.
number = 100
number *= 2
print(number)

# Q20: Declare three variables `a`, `b`, and `c` with values 5, 10, and 15 respectively. Calculate and print their average.
a = 5
b = 10
c = 15
average = (a + b + c) / 3
print(average)
