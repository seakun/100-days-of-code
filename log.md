# 100 Days Of Code - Log

### Day 13: April 6, 2020

**Today's Progress:** Split and join. Any and all.
    * split() - split() method divides a string into substrings by a separator.
    * join() - used to create a string out of a collection of strings
        * the argument of the method must be an iterable object with strings as its elements
        * the method must be applied to a separator: a string that will separate the elements in a resulting string object
        * this method only works if the elements in the iterable object are strings
    * splitlines() - used specifically to split the string by the line boundaries
    * any() - it returns True if an element or a group of elements in an iterable object are evaluated True.
        * the value True corresponds to 1, while False can be represented by 0. all numbers other than 0 will be regarded as True, even the negative ones
    * all() - checks if all the elements of an iterable object are True and returns True if they are.

**Thoughts:** Finished Tic-Tac-Toe.

**Link to work:** [Tic-Tac-Toe](https://github.com/seakun/Python-Projects/blob/master/Tic-Tac-Toe/)

### Day 12: April 5, 2020

**Today's Progress:** Type Casting. Escape sequences. Scopes. LEGB rule:
    * Locals. Variables defined within the function body and not declared global.
    * Enclosing. Names of the local scope in all enclosing functions from inner to outer.
    * Globals. Names defined at the top-level of a module or declared global with a global keyword.
    * Built-in. Any built-in name in Python.
    * Global keyword.
    * nonlocal keyword lets us assign to variables in the outer (but not global) scope
    * Though global and nonlocal are present in the language, they are not often used in practice. 

**Thoughts:** More griding.

**Link to work:** [Tic-Tac-Toe](https://github.com/seakun/Python-Projects/blob/master/Tic-Tac-Toe/)

### Day 11: April 2, 2020

**Today's Progress:** Finish Tic-Tac-Toe Part 3.

**Thoughts:** Getting the game status is pretty hard.

**Link to work:** [Tic-Tac-Toe](https://github.com/seakun/Python-Projects/blob/master/Tic-Tac-Toe/)

### Day 10: March 31, 2020

**Today's Progress:** List comprehensions. Nested lists.
    * # list comprehension syntax
    * new_list = [x for x in some_iterable]
    * # list comprehension with condition
    * new_list = [x for x in some_iterable if condition]
    * # original list
    * school = [["Mary", "Jack", "Tiffany"], 
    *           ["Brad", "Claire"],
    *           ["Molly", "Andy", "Carla"]]
    * student_list = []
    * for class_group in school:
    *     for student in class_group:
    *       student_list.append(student)
    * student_list = [student for class_group in school for student in class_group]

**Thoughts:** Pretty straightfowards. Arrays are List in Python.

**Link to work:** [Tic-Tac-Toe](https://github.com/seakun/Python-Projects/blob/master/Tic-Tac-Toe/)

### Day 9: March 30, 2020

**Today's Progress:** Finish Hangman project. Start Tic-Tac-Toe project.

**Thoughts:** Very thorough project on Python basics.  

**Link to work:** [Hangman](https://github.com/seakun/Python-Projects/blob/master/Hangman/) [Tic-Tac-Toe](https://github.com/seakun/Python-Projects/blob/master/Tic-Tac-Toe/)

### Day 8: March 28, 2020

**Today's Progress:** Program execution. Errors.

**Thoughts:** Python is an interpreted language. There's a Python Virtual Machine. 

**Link to work:** [Hangman](https://github.com/seakun/Python-Projects/blob/master/Hangman/)

### Day 7: March 27, 2020

**Today's Progress:** Loop control statements. Finish Hangman Part 6.
  * break - exits from the loop immediately. 
  * continue - stop the iteration if your condition is true and return to the beginning of the loop. 
  * else - used to specify a block of code to be executed after the loop.
    * runs if and only if the loop is exited normally (without hitting break).
    * runs when the loop is never executed
      * the condition of the while loop is false right from the start

**Thoughts:** Very confusing.

**Link to work:** [Hangman](https://github.com/seakun/Python-Projects/blob/master/Hangman/)

### Day 6: March 26, 2020

**Today's Progress:** Sets. For Loops. Finished Hangman Part 5. 

**Thoughts:** Similar to dicts?

* Set:
  * unordered, hashable objects
  * {} or set()
  * len()
  * in, not in
  * use for loop to iterate through it
  * add(), update()
  * discard(), remove()
    * remove generates KeyError if it's not there
  * pop()
    * remove random element
  * clear() - delete everything
  * Advantages: allow you to run membership tests much faster than lists

**Link to work:** [Hangman](https://github.com/seakun/Python-Projects/blob/master/Hangman/)

### Day 5: March 25, 2020

**Today's Progress:** Arguments. Operations with list. How to load modules and load specific functions from modules. Using Random module. String formatting. Basic string methods. Finished Hangman Part 4. 

* List operations:  
* list.append(element)
* list.extend(another_list)
  * list.append(element) instead of list.extend(another_list), it adds the entire list as an element.
* list.remove(element)
* list.insert(position, element)
  * The first argument is the index of the element before which to insert
  * list.reverse()
    * it performs the operation in place, i.e. it returns nothing, so you can't assign the result of this function to another variable, although the initial list will still be changed
* list.sort()
  * performs an inplace sorting, meaning that it changes the original list and doesn't return anything
  * To sort a list in the descending order, you need to specify reverse argument as True: numbers.sort(reverse=True)
* Membership testing in a list: checking if an item is present in the list.
  * in
  * not in 
* Random Module:
  * random.seed([x])
  * random.uniform(a, b)
  * random.randint(a, b)
  * random.choice(seq)
  * random.randrange(a, b, c)
  * random.shuffle(seq, [random])
  * random.sample(population, k)
* String formatting
  * string % value
    * print('%.3f' % (10/3))
  * print('Mix {}, {} and a {} to make an ideal omelet.'.format('2 eggs', '30 g of milk', 'pinch of salt'))
  * print('{0} in the {1} by Frank Sinatra'.format('Strangers', 'Night'))
  * print('The {film} at {theatre} was {adjective}!'.format(film='Lord of the Rings', adjective='incredible', theatre='BFI IMAX'))
  * name = 'Elizabeth II'
  * title = 'Queen of the United Kingdom and the other Commonwealth realms'
  * reign = 'the longest-lived and longest-reigning British monarch'
  * f'{name}, the {title}, is {reign}.'
  * hundred_percent_number = 1823
  * needed_percent = 16
  * needed_percent_number = hundred_percent_number * needed_percent / 100
   * print(f'{needed_percent}% from {hundred_percent_number} is {needed_percent_number}') # 16% from 1823 is 291.68
   * print(f'Rounding {needed_percent_number} to 1 decimal place is {needed_percent_number:.1f}') # Rounding 291.68 to 1 decimal place is 291.7
* String methods
  * str.replace(old, new[, count])
  * str.upper()
  * str.lower()
  * str.title()
  * str.swapcase()
  * str.capitalize()
  * str.lstrip([chars])
  * str.rstrip([chars])
  * str.strip([chars])
  * startswith()
    * str.startswith(pattern, start, end)
  * endswith()
    * str.endswith(pattern, start, end)

**Thoughts:** Even more griding.

**Link to work:** [Hangman](https://github.com/seakun/Python-Projects/blob/master/Hangman/)

### Day 4: March 24, 2020

**Today's Progress:** Control flow statements → Elif statement. Tuples.

**Thoughts:** More griding.

**Link to work:** [Hangman](https://github.com/seakun/Python-Projects/blob/master/Hangman/)


### Day 3: March 23, 2020

**Today's Progress:** Submitted pull request to fullstackpython.com 

**Thoughts:** More involved than originally thought. Needed to clone the repository, make the changes, and then submit pull request.

**Link to work:** [fullstackpython.com pull request](https://github.com/mattmakai/fullstackpython.com/pull/232)

### Day 2: March 22, 2020

**Today's Progress:** Collections -> Lists and Indexes. Finishing Zookeeper project.

**Thoughts:** Lists. 

**Link to work:** [Zookeeper](https://github.com/seakun/Python-Projects/blob/master/Zookeeper/zookeeper.py)

### Day 1: March 21, 2020

**Today's Progress:** Avoiding bad comments. Printing. Quotes and multi-line strings. 

**Thoughts:** Code should be intuitive. 

**Link to work:** [Zookeeper Part 1](https://github.com/seakun/Python-Projects/blob/master/Zookeeper/zookeeper_part1.py)
