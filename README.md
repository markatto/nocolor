# Nocolor

## What is nocolor?
Nocolor is a simple script that removes terminal color codes from
data piped through it. 

## Why nocolor?
Colors are great. Everyone loves colors, right?

Wrong. Colors should always be optional. Color codes get in the way when you are
trying to parse the output. This is a simple utility to make the parsing of colored
output simpler.

## Usage
```console
$ stupid_colored_program | nocolor.sh
```
you can move/symlink it into /usr/bin, /usr/local/bin, or anywhere else in `$PATH`


## Why are you making such a big deal out of a stupid sed one-liner?
Because I can. Also, I figured that this might be useful to some people.
