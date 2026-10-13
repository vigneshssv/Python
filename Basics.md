# What is python and usage
   - Python is higher level programming language, its easy to read, write and learn.
   - its used for multiple platform like AI, software development, web development, Data Analysis, 
   automation, testing and devops.

# Why py is popular
   - easy to learn, write less code compare to other languages, support cross platform like windows, mac, linux
# variables
 - In php and other language use var, const, let for mention the variable keyword
 - Py not need to write a var, const, let.
 - just write a = 10 means its automatically consider var a is integer.
   ```bash
   a = 10
   print(a)
   result: 10
   ```
   ### variable types
    | Type        | Example                             | Description |
    | :---        | :------                             | :---------- |
    | int         | age = 25                            |             |
    | str         | name = "vig"                        |             |
    | float       | price = 22.5                        |             |
    | bool        | status = True                       |             |
    | list        | nums = [1,2,3]                      | ordered, changeable collection          |
    | tuple       | nums = (1,2,3)                      | ordered, unchangeable collections           |
    | set         | nums = {1,2,3}                      | collections of unique values            |
    | dict        | user = {"name": "john", "age":25}   | key value pairs            |
    | NoneType    | result = none                       |             |
   ### Boolean
   - True, False => start with capital letters only
   
   ### Type
   - check data type for the value
   ```bash
   a = 10
   type(a)
   result: int
   a = "vig"
   type(a)
   result: str
   ```
   ### Length
   - len(a) => used to check length of the string, list(array), and object
   - len() => its not support to check length of the integer no. raise error
   ```bash
   a = "vignesh"
   len(a) => 7
   a = [1,2,3]
   len(a) => 3
   ```
# Lists
   - same one like a array
  ```bash
   a = [1,2,3,4]
   print(a) => [1,2,3,4] 
   print(a[0]) => 1
   ```
   - same list write different type of values like
   ```bash
   a = [True,False, 1,2.3, "Vig"]
   ```
# Input()
   - Command prompt write it for input() option like
   ```bash
   a = input("choose a no:")
   choose a no: 3
   a = 3 assigned print(a) means result get 3
   ```
   - input value store as string only.
   - For ex: a = 3 means 3 is not a integer, its store as string.
   - we used int(a) to convert data type
   ```bash
   a = input('age: ')
   age: 3
   type(a)
   result: str
   # convert a data type
   a = int(a) or a = int(input('age:'))
   type(a)
   result: int
   ```
# Convert DataType
   - convert a data type for the variable directly using int(), str(), bool()
   ```bash
   a = 10
   type(a) -> result int
   a = str(a)
   type(a)
   result: str
   ex: int(), str(), bool(), float() 
   ```
# pycharm (Code Editor)
   - ycharm is a code editor same one like for vs code.
   - its available build in multiple library packages and used to run the py codes
# comments (#)
   - using the '#' tag to create a comment line
   - disable the python code we use for the '#' hash tag

   
   
