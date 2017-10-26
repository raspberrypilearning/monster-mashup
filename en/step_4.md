## Ordering monsters

### How many monsters can you make?
A quick bit of maths can tell you how many monsters you can make with the parts of names you've got.

- Have Python `print` out the number of monsters your program can create! All you need to do is multiply (`*`) the number of parts in each list by one another.

#### Getting the length of a list
To get a count of how many items are in a list, you can use `len()` like this:

```python
my_list = [1, 2, 3]
length = len(my_list)
```

--- hints ---
--- hint ---
This code will work, but you may need to change the variable names to match your lists!
```python
print('This program can make '+str(len(name_start)*len(name_middle)*len(name_end))+' different monsters!')
```
--- /hint ---
--- /hints ---

### Placing an order
Next, ask the user for the number of monsters they'd like, and store that number in a variable.

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
