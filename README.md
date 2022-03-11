# Brightness

Script for manipulating brightness on linux.

Requires Python 3.5 or above.

## Install

You can just `chmod 755 brightness.py` and move it to some
directory in your `PATH`, you can also rename it to remove
the `.py` if you want.

## Usage

The program is very self explanatory, but here's 3 examples:

*Set brightness to 75%*
```
$ doas brightness set 0.75
```

*Increase brightness by 12%*
```
$ doas brightness inc 0.12`
```

*Reset brightness to default(50%)*
```
$ doas brightness reset
```

The other commands are very obvious, and need not be
explained.
