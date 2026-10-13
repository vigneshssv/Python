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

# List, Set, Tuple, Dictionary
   ### Lists
   - store multiple values and support for add, update, delete a values
   - support for ordering(sorting)
   - allow duplicate values
   - support indexing
   ```bash
   numbers = [1,2,3]
   numbers.append(4) # add a new value
   number[0] = 4 # update a value
   numbers.remove(3) #  remove a value
   ```
   ### tuple
   - store a items and support ordering, indexing, allow duplicate values
   - cannot modify values directly after create a tuple
   - create new tuple, copy for the tuple to add, update, delete a values
   ```bash
   numbers = (1,2,3)
   numbers[0] = 4 # raise error, not possible to update value
   # create new tuple to modify existing one
   numbers = numbers + (4,5,) #  add a new values result: (1,2,3,4,5)
   # update and delete a tuple value
   numbers = (1,2,3,5)
   temp = lists(numbers) # convert a number variable tuple to list
   temp[1] = 4 # change the value
   temp.remove(3) # remove the value
   numbers = tuple(temp) # convert the existing list into tuple once again
   result: (1,4,3)
   ```
   ### set - () or {}
   - store a unique values, remove duplicate values automatically
   - does not support indexing
    
    ```bash
        numbers = {1,2,3}
        numbers.add(4) # add new value
        numbers.update([4,5]) #  add multiple values result: {1,2,3,4,5}
        numbers.remove(3) # remove value, if value is not exists raise key error
        numbers.discard(3) # remove a value safely, if value missing to its not raise error
        numbers.pop() # remove value first like left to right
        numbers.clear() # clear all values
     ```
   ### dictionary (object array)
   - store value as key value {key: value}, same one like object array
   - support add, update, delete a values
   - using for data store user profile, api response, json data
    
   ```bash
   user = {
     "name" : "vignesh",
   "age" : 22
   }
   user.name = 'raj' # update a value
   user.email = 'v@g.com' # add a value
   user.pop('name', none) # remove a key value, none - if value is not available to its not raise error
   user.popitem() # remove last key value
   ```
# Functions
- Reusable block of code start with def keyword:
```bash
#sample code
def numbers(a,b = 0):
   return a+b, a*b

a = int(input('no a:'))
b = int(input('no b:'))

addition, multi = numbers(a,b)
print(addition, multi)
```


