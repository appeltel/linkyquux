# LinkyQuux

LinkyQuux is a public-facing learning exercise that I am performing
for fun and education in order to build skill in writing and
distributing C extension modules for python. I have another, potentially
useful idea that I may try to implement after using this exercise
as a "warm up".

LinkyQuux intentionally has a silly and obfuscated name as I would like to
put this on pypi as part of the exercise and don't want to encroach on
any useful namespace.

### Goals

The goals of the project are as follows:

1. Write a linked list mutable sequence type that:
   * Is implemented completely in C
   * Fully implements slicing, iteration protocol, and generally everything that the builtin `list` type does.
   * Outperforms a `list` for random insertion and deletion

2. Construct full unit testing suite in C and python, use appropriate tools to test for memory leaks.

3. Make a working setup, and produce viable anylinux wheels, successfully host on pypi and verfiy deployment to various distributions.
