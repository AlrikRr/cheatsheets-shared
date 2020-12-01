# cheatsheets-shared

To use this collection of cheatsheets you need to download a tool called: [cheat](https://github.com/cheat/cheat)
Upon installation run the `cheat` command without any arguments to generate all the default configuration.

## config.yml
In your ~/.config/cheat/config.yml file, Add the following lines below your personal tag:
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

- You can use whatever syntax you want. For this example we use the bash syntax.
- Remember to use the `shared` tag, followed by tags you find relevant to the cheatsheet (Ex: `networking`, `sysadmin`, ...etc).

## Contribution

All contributions to this database are welcome!
But, there are rules (Yes we're familiar with the second law of thermodynamics, but please make an effort!):

- Write everything in English, or understandable English :smirk:, or find a friend that can do the translation for you.

- The cheatsheet name must be unambiguous and fast to type !

- No duplicates !

- No duplicates !

- If you're writing cheatsheets for a programming language, group them into a single folder, like I did for **bash** and **python**

- I don't have a syntax for cheatsheets, if it's easy to understand and not a mess, go ahead.

- Be sure to use the **shared** tag ! (In an alternate universe, this would be the first rule)

- If you're creating a folder, like I did for python, make sure to put a **model-cheat** inside, so that way if someone want to contribute to your category, he can use the same "template".

- Well, if there is a model-cheat inside a category and you want to put your own cheatsheet, use the "template" ! (I know, redundant rule, but i've been on the internet way to long not to include it)

- You can edit a cheatsheet that already exist. (In layman's terms: No duplicates !)

- If you want to put your name into the cheatsheet ([attention whore](https://en.wiktionary.org/wiki/attention_whore)), put it at the end of the file like :
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

- Ignore these rules and become our lifelong enemy or just have your pull request rejected ( depending on the mood of the maintainer that day) 

# Contributors
<a href="https://github.com/AlrikRr/cheatsheets-shared/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=AlrikRr/cheatsheets-shared" />
</a>
