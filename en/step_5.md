## Making monsters—Picking pieces
You will need to make a few monsters to fill your user's order. The easiest way to do that is with a **function** which will let you re-use the same piece of code over and over again. Try creating a function that joins together the first items in each list.

### Functions
Python functions are like pre-written sets of instructions that you can use by just **calling** the function's name. A similar example for a human would be "make a cup of tea". You don't need to be told to put the teabag into the pot, then add water, etc. You know you'll need to do that to make tea. You can teach Python in the same way. Functions are created using `def`, which is short for define. They usually **return** something, like that cup of tea!

```python
def my_function(():
  first_number = 4
  second_number = 6
  return first_number + second_number
```

You **call** a function so that the code runs by using its name, like this:

```python
my_function()
```

You can put the result of the function into a variable too:

```python
my_number = my_function()
```

### Getting things from lists
You can get the **item** at any position on the list by using its **index**—the number that marks its position. The count of the position starts from 0, not 1 though.

```python
  my_list = ['cat', 'dog', 'rabbit']
  print(my_list[0]) # this will print 'cat' 
```

--- hints ---
--- hint ---
Remember that you can join **variables** and text together inside a `print` with `+`.
--- /hint ---
--- hint ---
A function that joins together the first items on each list would look like this, though you might need to change some variable names!

```python
def make_monster():
    start = name_start[0]
    middle = name_middle[0]
    end = name_end[0]

    name = start+'-'+middle+'-'+end

    return name
```

And you can test it like this:

```python
print(make_monster())
```
--- /hint ---
--- /hints ---
