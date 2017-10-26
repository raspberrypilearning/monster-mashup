## Making enough monsters
Your user ordered a certain number of monsters from you earlier. You need to deliver! 

   - Create a list of monsters and then use a `while` loop to make them until you have enough.

### Adding things to lists
You can add an **item** to a **list** using the `append` **function**.

```python
my_list = ['cat', 'dog']
my_list.append('rabbit')
```

--- hints ---
--- hint ---
You can check whether the length (`len()`) of your monsters list is still less than the number of monsters your user requested.
--- /hint ---
--- hint ---
The code could look something like this:

```python
while len(monsters) < requested_monsters:
  monsters.append(make_monster())
```
--- /hint ---
--- /hints ---