Learn a Language
================

If you're learning a new programming language or framework, it's important to have a project or exercise to perform that gives you a chance to put the language through it's paces - Hello World generally doesn't cut it.

This repo is a description of some ideas of such projects - please fork, pull request and add to the list!

1. [Pascal's Triangle](#pascals-triangle)
2. [Langton's Ant](#langtons-ant)
3. [Skip Lists](#skip-lists)
4. [SLA](#sla)

Pascal's Triangle
-----------------

tl;dr - Basic and perfect for day one of a new language.

One of the best - [Pascal's Triangle](http://en.wikipedia.org/wiki/Pascal's_triangle) is a simple mathematical construct that you should be able to implement quickly in almost any language. The sort of output you'd be looking for would be:

````

How many lines? 5

1
1 1
1 2 1
1 3 3 1 
1 4 6 4 1
````

What should this teach?
* Basic mathematical functions of the language.
* Console or process input
* Console or file ouput
* Recursion or looping

I've got an implementation that's clearly commentted and tested at [github.com/dwmkerr/fsharpexperiments](https://github.com/dwmkerr/fsharpexperiments).

Langton's Ant
-------------

tl;dr - Hard, great opportunities to be clever and use language specific features.

[Langton's Ant](http://en.wikipedia.org/wiki/Langtons_ant) is another mathematical simulation. In the simulation you create a basic universe with a few rules and let it run - it's quite similar to [Conway's Game of Life](http://en.wikipedia.org/wiki/Conway%27s_Game_of_Life).

A screenshot of such an application, written in Javascript would look like this:

![Langton's Ant](http://www.dwmkerr.com/experiments/langtonsant/langtonsant.jpg)

(This project is on GitHub at [github.com/dwmkerr/langtonsant](https://github.com/dwmkerr/langtonsant)).

What should this teach?
* More complex collections
* State management
* Console or process input
* Console, graphical or file output
* Basic algorithms.

Skip Lists
----------

Skip lists are a data structure which allow O(logN) speed access to a list. Rather more complicated than linked lists and a basic B-tree but easier than an AVL tree.

There's a great article [on Skip Lists on the CodeProject by Mostaffa Eissa](http://www.codeproject.com/Articles/874643/Skip-Lists-Demystified).

This would be an ideal project for C or C++, any language where you manage memory directly.

What should this teach?
 * Memory management
 * Algorithmic Complexity
 * Data structures



http://www.codeproject.com/Articles/874643/Skip-Lists-Demystified

## SLA

A nice simple idea for a console app:

```
$ sla 99.9
Daily Downtime   : 1m 26.4s
Weekly Downtime  : 10m 4.8s
Monthly Downtime : 43m 49.7s
Yearly Downtime  : 8h 45m 57.0s
```

What would this teach?

- Simple console programs
- Time formatting
