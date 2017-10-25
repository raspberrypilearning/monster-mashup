## Making monsters—At random!
Ok, your program makes the one monster. It's always the same. Time to make more of them! You're going to need to pick bits off of each list at random. Luckily, this is pretty easy in Python! You just need to add `random`! Update your monster making function to choose the pieces of the name at random.

### Choosing from a list at random
You'll need to **import** some extra code, so you can use the `random` **functions**, but it's built into Python, so it'll always be there for you.

```python
import random # this line goes at the top of your file

my_list = ['cat', 'dog', 'rabbit']
random_animal = random.choice(my_list)
```

--- hints ---
--- hint ---
Add this at the top of the file:

```python
import random # this line goes at the top of your file
```

Update the function so it looks like this:

```python
def make_monster():
    start = random.choice(name_start)
    middle = random.choice(name_middle)
    end = random.choice(name_end)

    name = start+'-'+middle+'-'+end

    return name
```

And you can test it like this:

```python
print(make_monster())
print(make_monster())
print(make_monster())
```

They should be different!
--- /hint ---
--- /hints ---