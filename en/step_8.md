## Delivering your monsters
Now that you have enough monsters, time to introduce them to the user by printing them out! You can use a `for` loop to do something once for each item in a list, like your list of monsters.

### For loops
For loops let you repeat a piece of code for every item in a list, like this:

```python
my_list = ['cat', 'dog', 'rabbit']

for animal in my_list:
  print('I like to pet my '+animal)
```
--- hints ---
--- hint ---
The code could look something like this:

```python
for monster in monsters:
    print('Presenting the '+monster+'!')
```
--- /hint ---
--- /hints ---

### Deliver with style!
Give your monsters an impressive introduction: Create a list of introductions and pick one at random for each monster as you're presenting them.

--- hints ---
--- hint ---
You'll need:
  * A list of introductions
  * An update to your `for` loop to choose one at `random` for each monster
--- /hint ---
--- hint ---
The code could look something like this:

```python
introductions = ['Awesome',
                 'Amazing',
                 'Terrifying',
                 'Fire breathing'
                 ]

for monster in monsters:
    print('Presenting the '+random.choice(introductions)+' '+monster+'!')
```
--- /hint ---
--- /hints ---