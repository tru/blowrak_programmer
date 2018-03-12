# The blowrak programmer keyboard layout.

This is my customized [blowrak](https://github.com/wanders/blowrak) keyboard
layout to better suite a programmer. This is very inspired by the [Programmer
dvorak layout](https://www.kaufmann.no/roland/dvorak/).

![layout](https://raw.githubusercontent.com/tru/blowrak_programmer/master/blowrak_programmer.png)

## Brief history of this keyboard layout

When I decided to switch to Dvorak a long time ago I actually switched to a
modified version of dvorak that was made by my friend
[Anders](https://github.com/wanders). The modifications to dvorak made by him
was to accommodate for the trackpoint on the thinkpads. Mainly switching place
of `h` and `d`, `x` and `m` and adding the Swedish extra characters `åäö`.

My own version of blowrak did some lighter edits to the placement of brackets
and braces to have easier access to them.

After I have been using this layout for more than 10 years I think it's clear
that while it's a great setup for writing text, it's not as great for a
programmer. I wanted to change this and looked around for some inspiration and
found the "Programmer Dvorak Keyboard Layout". I then used the blowrak setup
as my starting point and reworked all non-character keys similar to what the
programmer dvorak setup did, and so the blowrak programmer keyboard layout was
born.

## Changes from Programmer Dvorak

I started by adding the numbers back in sequential ordering. I didn't see a huge
benefit of having them in odd/even split. The Swedish characters where then added
under the extra buttons on the first row with the modifier Alt+Gr. I very rarely
write Swedish on my keyboard and those buttons could just be used for other stuff.

I am still not 100 sold on the fact that the `[]` and `()` keys are split while
the `{}` are not. We will see if I change that in the future.

# Included in this repo

* macOS keyboard layout file. Just drop it in `~/Library/Keyboard Layouts`
* xkb symbol file for x11. Drop it in `/usr/share/X11/xkb/symbols` and then you
  need to edit `rules/evdev.xml` for it to show up globally.
* Windows KbdEdit file. You need [KbdEdit](http://www.kbdedit.com/) in order to
  install this. There might be a better way to do this on windows, but I haven't
  found it yet.
