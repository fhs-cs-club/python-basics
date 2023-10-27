# Resources

# Basics
[Learn Python](https://www.learnpython.org/)

Follow the links to learn the basic of python

## Beginner
- [Hello, World!](https://www.learnpython.org/en/Hello%2C_World%21)
- [Variables and Types](https://www.learnpython.org/en/Variables_and_Types)
- [Lists](https://www.learnpython.org/en/Lists)
- [Basic Operators](https://www.learnpython.org/en/Basic_Operators)
- [String Formatting](https://www.learnpython.org/en/String_Formatting)
- [Basic String Operations](https://www.learnpython.org/en/Basic_String_Operations)
- [Conditions](https://www.learnpython.org/en/Conditions)
- [Loops](https://www.learnpython.org/en/Loops)
- [Functions](https://www.learnpython.org/en/Functions)
- [Classes and Objects](https://www.learnpython.org/en/Classes_and_Objects)
- [Dictionaries](https://www.learnpython.org/en/Dictionaries)
- [Modules and Packages](https://www.learnpython.org/en/Modules_and_Packages)


***Basic Grade Checker***
```python

# Basic Import Statement
# To install type ```pip install hacapi```
# Located at https://pypi.org/project/hacapi/ 

from hacapi import hac # Eshan's Web Scraping Package

# Change the values t
username = "sample-username"
password = "sample-password"

acc = hac.Account(username, password)

# Prints tuple of Grades and Class Names
print(acc.return_current_grades())

# Prints College 4.0 GPA
print(acc.return_college_gpa())

```
