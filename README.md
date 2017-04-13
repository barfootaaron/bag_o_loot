# Bag o' Loot

This exercises will help with your comprehension of command line parameters.

You have an acquaintance whose job is to, once a year, delivery presents to the best kids around the world. They have a problem, though. There are so many good boys and girls in the world now, that their old paper accounting systems just don't cut it anymore. They want you to write a program that will let them do the following tasks.

### Add a toy to the bag o' loot, and label it with the child's name who will receive it. The first argument must be the word add. The second argument is the gift to be delivered. The third argument is the name of the child.
```
python lootbag.py add kite suzy
python lootbag.py add baseball michael
```

### Remove a toy from the bag o' loot in case a child's status changes before delivery starts.
```
python lootbag.py remove suzy kite
python lootbag.py remove michael baseball
```

### Produce a list of children currently receiving presents.
```
python lootbag.py ls
```

### List toys in the bag o' loot for a specific child.
```
python lootbag.py ls suzy
```


### Specify when a child's toys have been delivered.
```
python lootbag.py delivered suzy
```


## Write a unittest test before you write implementation code


