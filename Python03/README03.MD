# Functions

**More Functions**

  map(),input(),len(),print()

**Defining Functions**

  ```
  def function_name():
    code#

  def greet():
    print('Hello) // indentation

  greet() // call function
  ```

**Parameters & Arguments**

  Arguments = pass value to function
  to pass argument to Function , the functions has to have a variable called Arguments

  ```
  def greet(name): // name is parameter
    print('Hello ' + name)

  greet('John') // Hello John
  ```


**Scope**

  variables have a scope. Indetation.

  ```
  def greet(name):
    print(name)
  print(name) // (X) - ERROR - name is not defined
  ```

**Function with multiple parameter**

  ```
  def greet(name, message): // separate with comma
    print(name+','+message)
  ```

**Default Value**

  ```
  def greet(name, message = 'nice to meet you'):
    print(name+ ',' + message)

  greet('John','hallo') // John, hallo
  greet('Mike') // Mike,nice to meet you
  ```

**Return**

  anything comes after return in the function won't be executed.

**Dividing Files**

  ```
  import utils // without extension

  print(utils.validate) // how to call function from utils.py
  ```

**Python Standart Library**

  List of built-in-modules. 

    ```
    Math - module for complex calculations
      sin() , cos(), tan()
    
    Random - module for generate random values
      random() , randint() , shuffle()

    DateTime - module for handling date & time
      date() , time() , datetime()
    ```




  ```
  import random

  computer_hand = random.randint(0,2) // range 0 - 2
  ```