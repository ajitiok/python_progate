# Class Inheritance

  Making a new class based on another class is called inheritance.

  Parent Class  => Child Class

  ```
  class ChildClassName(ParentClassName)
    code
  ```


**How Inheritance Works**

  The child class inherits the instance methods of the parent class.




**Adding Instance Methods to ChildClass**\

  However, parent classes cannot use methods defined in the child class.


**Overriding Methods**

  //childclass
  ```
  class Food(MenuItem):
    def info(self):
      return //must return to override
  ```


**Overriding __init__ childclass**

  ```
  class Food(MenuItem):
    def __init__(self,name,price):
      self.name = name // overide init
      self.price = price // overide init
  ```

**Overlap Inside Methods**
  
  duplicate code at ParentClass & ChildClass 
  ```
  class Food(MenuItem):
    def __init__(self,name,price):
      self.name = name // overide init
      self.price = price // overide init

  class MenuItem():
    def __init__(self,name,price):
      self.name = name 
      self.price = price 
 
  ```

  Using super() in the method that you overrode allows you to call methods of the parent class.

  ```
  class MenuItem():
    def __init__(self,name,price):
      self.name = name // overide init
      self.price = price // overide init
 
  class Food(MenuItem):
    def __init__(self,name,price,calories):
      super().__init__(name,price)
      self.calories = calories
  ```