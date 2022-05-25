# doit
[![asciicast](https://asciinema.org/a/jkPtGtg1HqBgb4neMxLqYTDi6.svg)](https://asciinema.org/a/jkPtGtg1HqBgb4neMxLqYTDi6)


doit is a simple, minimal todo list app. Written in Python

# Features
- [ ] Saving your todo list in a database
- [x] Support tag and tag colors
- [x] Support 2 modes of rendering the todo:
   - Basic mode: Simple rendering
   - Board mode: Rendering the todo like a board
- [x] Support simple adding and deleting a todo
- [x] Support deleting all the todos
- [ ] Support deleting todos based on tag

# Getting started

First, clone this repository:

```sh
git clone https://github.com/devanshmehra/doit
```

Then, install the required library for doit(`rich`):

```sh
pip3 install rich
```

Next, go to the `doit` directory, and type:

```sh
python3 main.py
```

Finally, you should see your CLI screen like this:

```
Welcome to doit!
Type help for help
And quit to quit
Todos:

>>>
```

If you see it, that means that doit has successfully worked! :smiley:

# Commands

Here is the complete list of commands in doit:
- __add__: Add a todo
- __delete__: Delete a todo
- __help__: Prints the help page
- __quit__ or __exit__: Quit the program
- __delete_all__: Delete all the todos
- __clear__: Clear the screen
- __delete_tag__ (Further feature): Delete every todo that has the same tag is `tag`

# Help

If you see a bug or an error, just push one at the `Issues` page!
If you want to contribute, you can fork it and make it better!

