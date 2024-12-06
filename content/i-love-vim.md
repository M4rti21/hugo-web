+++
title = 'I Love Vim'
date = 2024-09-30T23:57:49+02:00
tags = ["vim","tech", "workflow"]
draft = false
+++

*I use neovim btw*

*(neo)vim as a text/code editor is amazing, but it wont be the focus of this
post, what I want to talk about are vim motions and why I believe every 
programmer should learn them.*

## Why I love motions

Vim motions are amazing, once you learn them they unlock a level of "connection"
between your thoughts and the computer that I have never achieved with anything 
else before. 

At first it may seem very complicated and unnatural but its worth the hussle.

## The benefits

Its the same as when using cli tools (if you know what you want to
do you can do it instantly with a single command, instead of having to find that 
one hidden button across different menus/screens). With vim if you want to do
something you are usually just a couple keypresses away of achieving it.

Also, many applications use vim motions, so, with the right set of tools, you i
can interact with your computer without moving your hands from the home row of 
your keyboard.

## Why would I want that?

If you know how to touch type you know the concept of a home row, the middle
row on your keyboard from which you can access every other key in the
most "efficient" way. 

Some basic actions most code editors have are ones such as copy, paste, undo, 
redo, etc... And doing all those actions involves some sort of key combination, 
like Ctrl+C, Ctrl+V... Some even need multiple modifiers like Shift+Alt+DownArrow 
(to copy a line down in VSCode), all of those require you to shift your fingers 
around the keyboard which (even if slightly) break your "zen" state of just 
writing code, and even worst is when going for the mouse to scroll, select, 
or Ctrl+MouseRight to go to a definition.

You might identify with [*this (6:17 - 7:01)*](https://youtu.be/zPMPqzjM0Fw?si=81FqeuXbEy2Ikfei&t=377),
so did I and so does probably everyone.

Its true that a mouse is more efficient for lots of things, but I doubt that's 
the case for a task mostly consisting on editing **text**.

## What does vim do differently?

Vim is a modal editor, meaning that your keys do different actions depending on
what mode you are in, (although it is not quite the same) think of it like when 
you hold the Ctrl key and now the C key doesn't write the C character but rather 
performs the copy action. On vim by default you are on the Normal mode, where 
all your keys are mapped to different actions, most of the basic actions you do
on all other editors are now binded to a single key press, (some actions still
require a modifier, but that's because all other keys are taken). All those 
actions are for manipulating/moving-around text. 

When you want to write all you need to do is change to the Insert mode, now your 
keyboard is just a regular keyboard, where every key writes it's character. 
Its that simple. Having every key bind to an action is so much more powerfull 
than anything that could be done just by using modifiers.

## There is no way you could remember all those keybinds!

![neat-part](/neat-part.jpg#cover)

The basic movements are `h` (left), `j` (down), `k` (up), and `l` (right), but
other than that, most motions are mapped to the first letter of the action you 
want to perform, `w` moves you one [w]ord forward, `b` goes [b]ack one word, `u` 
is for [u]ndo changes (like `Ctrl+Z`), `p` is for [p]asting, `i` is for [i]nsert 
and many more. 

But the best part comes when combining them: 

- `d` stands for [d]elete, delete what you say? Whatever you want!
    - `dw` will [d]elete the [w]ord you are in, `dd` will delete the whole line.
    - `di"` will [d]elete [i]nside [" *quotes*] (see example).
    ```
  this is your cursor                   This is your cursor
           v                                     v
    "hello |how are you"  ->  (turns into)  ->  "|"
    ```
- `y` stands for [y]ank (copy)
    - Guess what `yw` will do? [y]ank the [w]ord.
    - And `yap`? [y]ank [a]round [p]aragraph

And it gets better:

- Guess what `d2w` will do? [d]elete [2] [w]ords.
- And `y6j`? [y]ank [6] [j *down*]
- `p69` will [p]aste what you have selected 69 times.
- you get the point...

All motions can be combined with one another in some way so once you learn the
base motions you can combine them in countless ways to do anything you can think
of, WITHOUT EVEN THINKING ABOUT IT!, when you learn how to touch type you dont
need to learn how to write every word, right? you just learn the letters and then
form any word without thinking it, its the same here, you dont need to know all
the possible combinations, you just do what you want to do and your editor will
do exactly that. Isn't that amazing?

## Conclusion

It doesn't take much to learn at least the basic motions that will get you up to 
a decent productive state, and from there it only gets better, you can still use 
your favourite IDE, as it probably has a VIM mode/plugin available so you can 
keep using the same tools you are used to, but really give it a fair try, you 
won't regret it.
