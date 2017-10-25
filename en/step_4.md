## Ordering monsters

### How many monsters can you make?
A quick bit of maths can tell you how many monsters you can make with the parts of names you've got there. Let's have Python tell the user how many that is! All you need to do is multiply (`*`) the number of parts of a name in each list by one another.

#### Getting the length of a list
To get a count of how many **items** are in a **list**, you can use `len()` like this:

```python
my_list = [1, 2, 3]
length = len(my_list)
```

--- hints ---
--- hint ---
You need to get the length of your name beginnings list, multiplied by the length of your name middles list, multiplied by the length of your name endings list and then `print` that out for the user.
--- /hint ---
--- hint ---
This code will work, but you may need to change the variable names!
```python
print('This program can make '+str(len(name_start)*len(name_middle)*len(name_end))+' different monsters!')
```
--- /hint ---
--- /hints ---

### Placing an order
Then ask the user for the number of monsters they'd like, and store that number in a variable.

--- hints ---
--- hint ---
Remember that you can use `input()` to ask for the user's input!
--- /hint ---
--- hint ---
This code will do it.
```python
requested_monsters = input('How many monsters would you like?')
```
--- /hint ---
--- /hints ---