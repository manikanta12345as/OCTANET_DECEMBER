# OCTANET_DECEMBER
print("Hello, World!")

Basic Input and Output:
Taking user input and displaying it:

user_input = input("Enter your name: ")
print("Hello, " + user_input)

List Comprehension:
A concise way to create lists in Python:
numbers = [1, 2, 3, 4, 5]
squared = [x**2 for x in numbers]
print(squared)

Simple Web Application using Flask:
A basic example of a web application using the Flask framework:
from flask import Flask

app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello, World!'

if __name__ == '__main__':
    app.run()

File Operations:
Reading and writing to a file:
# Writing to a file
with open('example.txt', 'w') as file:
    file.write("Hello, File!")

# Reading from a file
with open('example.txt', 'r') as file:
    content = file.read()
    print(content)

Basic Function:
Defining and calling a function in Python:
def greet(name):
    return f"Hello, {name}!"

result = greet("Alice")
print(result)

Working with Dictionaries:
Manipulating dictionaries in Python:
person = {
    'name': 'John',
    'age': 30,
    'city': 'New York'
}

# Accessing dictionary values
print(person['name'])

# Adding a new key-value pair
person['job'] = 'Engineer'

# Iterating through keys and values
for key, value in person.items():
    print(f"{key}: {value}")
