# 100 Days Of Code - Log

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
