# Classes

**Creating Object**

  make blueprint aka classes. classes => objects .

**Defining Object**

  make blueprint aka classes.

  ```
  class ClassName:  // start with Capital letter

  ```

**Instation**

  create instance of the class.
  ```
  variable_name = ClassName()
  ```

**Adding Data to Instances**

  ```
  class MenuItem:
    pass

  menu_item1 = MenuItem()
  menu_item1.name = 'Sandwich'
  ```


**Multiple Instances**

  ```
  class MenuItem:
    pass

  menu_item1 = MenuItem()
  menu_item1.name = 'Sandwich'

  menu_item2 = MenuItem()
  menu_item2.name = 'Chocolate'
  ```

# Classes & Methods

**Methods**

  function within classes. Must have parameter `self` in first parameter.

  ```
  class MenuItem:
    def hello(self):
      print('Hello')

  menu_item1 = MenuItem()

  menu_item1.hello() //Hello
  ``` 

**Instance Methods**

  Methods called from instance are called `instanced methods`.

  ```
  class MenuItem:
    def info(self):
      print(self.name)

  menu_item1 = MenuItem()
  menu_item1.name = 'Sandwich'

  menu_item1.info() // Sandwich
  ```

**Instance Methods can return value**

  ```
  class MenuItem:
    def info(self):
      return self.name

  menu_item1 = MenuItem()
  menu_item1.name = 'Sandwich'

  print(menu_item1.info()) // Sandwich
  ```


**Instance Methods parameter**

 ```
  class MenuItem:
    def info(self):
      print(self.name)

    def get_price(self,count):
      
  menu_item1 = MenuItem()
  menu_item1.name = 'Sandwich'


  menu_item1.get_price(4) // 4
   ```


**Special Methods**

  use __init__

  ```
  class MenuItem:
    def __init__(self):
      print('a menu item was created')

  
  ```


**Instance variable**

  ```
  class MenuItem:
    def __init__(self):
      self.name = 'Sandwich'

  
  ```


**__init__ method Arguments**

  ```
  class MenuItem:
    def __init__(self,name):
      self.name = name
  ```


**File Separation**

  from module_name import ClassName



**Numbering Items**

  ```
  lessons = ['Ruby','Python']
  index = 0
  for lesson in lessons:
    print(str(index)+'.'lesson)
    index += 1
  ```


  