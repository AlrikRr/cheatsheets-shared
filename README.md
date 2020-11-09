# cheatsheets-shared

Download [cheat](https://github.com/cheat/cheat)

## config.yml
Add thoses lines into the ~/.config/cheat/config.yml file
```
  - name: shared
    path: <path to cheatsheets-shared folder>
    tags: [ shared ]
    readonly: false
```


## Tags and syntax
```
---
syntax: bash
tags : [shared, tag1 , tag2 ]
---
```

- Bash syntax here is an example, use the right syntax !
- Use the shared tag, You are free to choose for the others

## Contribution

You can contribute to this cheatsheets database !
But, there are rules !

- Write everything in English, or understandable English.

- The cheatsheet name must be easy to understand and fast to type !

- No duplicates

- If this is a language like python, put all the cheatsheets into a folder, like I did for **bash** and **python**

- I don't have a syntax for cheatsheets, if it's easy to understand and not a mess, go ahead.

- Be sure to use the **shared** tag !

- If you want to create a folder, like I did for python, make sure to put a **model-cheat** inside, so that way if someone want to contribute to your category, he can use the same syntax.

- Well, if there is a model-cheat inside a category and you want to put your own cheatsheet, use the model !

- You can edit a cheatsheet that already exist.

- If you want to put you name into the cheatsheet, put it at the end of the file like :
```
-----------------------------
Author : AlrikRr
-----------------------------
``` 

- If you want to edit someone else's file and it has their name at the end, add your own as follows
```
-----------------------------
Author : AlrikRr 
Edited : Michel, Bernard
-----------------------------
```

