+++
title = 'I Love Vim'
date = 2024-09-30T23:57:49+02:00
tags = ["vim","tech", "workflow"]
draft = false
+++

*I actually use neovim.*

*(neo)vim as a text/code editor is amazing, but it wont be the focus of this
post, what I want to talk about are vim motions and why I believe every 
programmer should learn them.*

## Why I love vim(motions)

Vim motions are amazing, once you learn them they unlock a level of "connection"
between your mind and the computer that I have never achieved with anything 
else. It seems silly, and defenetly nerdy (because it is), but its very hard to 
leave it behind once you get used to it.

At first they might seem very hard, complicated and unnatural but its worth the
hussle.

Many applications use vim motions, so, with the right set of tools, you can 
interact with your computer without moving your hands from the home row of your
keyboard.

## The benefits

If you know how to touch type you know the concept of a home row, the middle
row of keys on your keyboard from which you can access every other key in the
most "efficient" way. When you only need to write words, like on an essey, vim
motions don't seem to give much benefit, but when writing code 2 its very common
to copy, paste, undo, redo, etc... And doing all those actions involves
some sort of key combination, like Ctrl+C, Ctrl+V, some even need multiple 
modifiers like Shift+Alt+DownArrow (to copy a line down in VSCode), all of those
require you to shift your fingers around the keyboard, and even worst is when
going for the mouse to scroll, select, or Ctrl+MouseRight to go to a definition.

[This (6:17 - 7:01)](https://youtu.be/zPMPqzjM0Fw?si=81FqeuXbEy2Ikfei&t=377) is 
one of the many things you could avoid when not using a mouse. Its true that a
mouse is more efficient for lots of things, but I doubt it is when doing a task
where your primary tool is your keyboard, not having to leave that tool keeps 
you on an uninterrupted flow state.

Vim is a modal editor, meaning that your keys do different actions depending on
what mode you are in, although it is not the same think of it like when you hold
the Ctrl key and now the C key doesn't write the C character but rather copy 
what you have selected. On vim by default you are on the Normal mode, where all
your keys are mapped to different actions, so no more holding Ctrl or Alt or 
Shift, but, by default you all your keys have a function you can use to 
manipulate/move-around your code. When you want to write all you need to do is 
change to the Insert mode, now your keyboard is just a regular keyboard, where 
every key write's it's character. Its this simple. Having every key bind to an 
action is so much more powerfull than anything that could be done by regular 
modifiers, as we also have them for even more actions on top of those other keys.

## There is no way you could remember that many keybinds

But that's the neat part, you don't!

Apart from `h` `j` `k` `l` most motions are mapped to the first letter of 
the action you want to perform, `w` moves you one [w]ord forward, `b` goes 
[b]ack one word, `u` is for [u]ndo changes (like `Ctrl+Z`), `i` is for [i]nsert 
and many more. 

But the best part comes when mixing them: 

- `d` stands for [d]elete, delete what? Whatever you want!
- `dw` will [d]elete the [w]ord you are in, `dd` will delete the whole line.
- `y` stands for [y]ank (copy)
- `yw` will [y]ank the [w]ord you are in, `yy` will yank the whole line.

And it gets better:

- Guess what `d2w` will do? [d]elete [2] [w]ords.
- And `y6j`? [y]ank [6] [j (down)]
- `p69` will [p]aste what you have selected 69 times.
- you get the point...

All motions can be combined with one another in some way so once you learn the
base motions you can combine them in countless ways to do anything you can think
of without thinking about it, as you think what you want to do, your fingers
move acordingly spelling your thoughts as movements, isn't that amazing?

## Conclusion

It doesn't take much to learn at least the basic motions that will get you to a
decent productive state, and from there it only goes up, you can still use your
favourite IDE, it probably has a VIM mode/plugin available so you can keep using
the same tools you are used to, but really give it a fair try, you won't regret 
it.
