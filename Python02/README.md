# Structuring Data

**Lists**

  ```
  [element1,element2,element3] // separate with comma

  string
  ['pasta','curry']

  integer 
  [1,2,3,4]

  mixed
  ['pasta','curry',1,2]
  ```

**Assign List to Variable**

  ```
  foods = ['pasta','curry']
  print(foods)
  ```

**Getting an element Lists**

index numbers , starts with index 0

  ```
  foods = ['pasta','curry']
  print(foods[0]) // pasta
  ```

**Update element of Lists**

  ```
  foods = ['pasta','curry']
  foods[1] = 'orange'
  print(foods) // ['pasta','orange']
  ```

**Adding new element of Lists**

  ```
  foods = ['pasta','curry']
  foods.append('orange')
  print(foods) // ['pasta','curry','orange']
  ```

**Printing All Element**

  use `for`

  ```
  foods = ['pasta','curry']

  for food in foods:
    print('I like ' + food)

  ```

# Dictionary

  Like object in javascript.
  Difference with Lists is Dictionary use keys.
  ```
  fruits ={ key1:value1,
            key2:value2
          }
  ```

**Getting Element of a Dictionary**

  ```
  fruits = {'apple':'red',
            'banana':'yellow'
            }

  print('The apple is ' + fruits['apple']) // The apple is red
  ```

**Updating Element of Dictionary**

  ```
  fruits = {'apple':'red',
            'banana':'yellow'
            }

  fruits['apple'] = 'green'
  print(fruits['apple']) // green
  ```

**Adding new key & value to Dictionary**

  ```
  fruits = {'apple':'red',
            'banana':'yellow'
            }
  fruits['peach'] = 'pink'
  print(fruits) // fruits = {'apple':'red','banana':'yellow','peach':'pink'}
  ```

**Getting all elements of Dictionary**

  ```
  fruits = {'apple':'red','banana':'yellow','peach':'pink'}

  for fruit_key in fruits:
    print('The ' + fruit_key + ' is ' + fruits[fruit_key]) //
    The apple is red ..
  ```

# While Loops

**How to Write While Loops**

  ```
  x = 1
  while x <= 100
    print(x)
    x += 1 // don't be infinite loop
  ```


**Break**

  statement to exit loops. combined with if loops.

  ```
  numbers = [1,2,3,4]

  for number in numbers:
    print(number)
    if number == 3:
      break

  ```


**Continue**

  statement to skip looping

  ```
  numbers = [1,2,3,4]

  for number in numbers:
    if number % 2 == 0 :
      continue
    print(number) // 1,3
  ```