# boom

A Kaboom clone for the CHIP-8

![image.png](Screenshot of Boom)

## About

This game was originally written in about a day just for fun, but I added a few
things here and there (as well as fixing a few bugs) since then.
I think that Kaboom for the
Atari is just a fun game so I wanted to port it to the CHIP-8.

This game was written using the [Octo](https://github.com/JohnEarnest/Octo)
language, which is a sort-of "high-level" assembly language for the CHIP-8 and
can compile to native CHIP-8 bytecode.

## How to Play

The controls are very simple: `A` moves left and `D` moves right. That's it.
Press `E` to start/restart the game

In order to run this you will need a CHIP-8 emulator/virtual machine, I just
happen to have written one [here](https://git.sr.ht/~bpv/c8).
Just supply your emulator of choice with the given `.c8` file (you can find the
game [here](boom.c8).
You may want to run this game at a higher speed than normal if it is too slow
for you.

## A Note:

This game is basically 100% complete, however bug reports and optimizations are
welcome.
