# Vim

> A modal text editor built around the idea that editing text can be done efficiently without constantly reaching for the mouse.

## 🔗 Resources

* [Vim Documentation](https://www.vim.org/docs.php)
* [Vim Help](https://vimhelp.org/)

## 🧠 What is Vim?

Vim is a terminal-based text editor and an improved version of the original **Vi** editor.

The main idea behind Vim is **modal editing**.

Instead of using the keyboard only to type text, different modes give the keyboard different purposes.

## ⌨️ Modes

### Normal Mode

Used for navigating and manipulating text.

```text
Esc
```

Examples:

```text
h → left
j → down
k → up
l → right

w → next word
b → previous word
0 → beginning of line
$ → end of line
```

### Insert Mode

Used for typing text.

```text
i → insert before cursor
a → insert after cursor
o → new line below
O → new line above
```

### Visual Mode

Used to select text.

```text
v → character selection
V → line selection
Ctrl + v → block selection
```

### Command Mode

Used for commands such as saving and quitting.

```text
:w  → save
:q  → quit
:wq → save and quit
:q! → quit without saving
```

## 🔥 Important Commands

```text
dd      delete line
yy      copy line
p       paste
u       undo
Ctrl+r  redo

dw      delete word
cw      change word

/search → search
n       → next result
N       → previous result
```

## 💡 What I'm Learning

* Modal editing
* Keyboard-based navigation
* Text manipulation
* Motions and operators
* Vim commands
* Efficient editing without a mouse

## 🤔 Why I Find It Interesting

Vim changes the way I think about editing.

Instead of:

> Move → select → click → delete → move → type

I can describe an operation directly using commands.

For example:

```text
ci"
```

means:

> Change Inside Quotes

This combination of commands is one of the things that makes Vim interesting to me.

## 📝 My Notes

I'll add commands, tricks, workflows, and things I discover while actually using Vim here.

---

**Status:** 🟡 Learning
