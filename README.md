# Learn a Language

If you're learning a new programming language or framework, it's important to have a project or exercise to perform that gives you a chance to put the language through it's paces - Hello World generally doesn't cut it.

This repo is a description of some ideas of such projects - please fork, pull request and add to the list!

This project is very much work in progress!

## The Fundamentals

Learning programming languages can be surprisingly easy. This is partly because whilst the _syntax_ of languages can vary considerably, most languages will fall into a 'category', once you know how languages in this category work there will be a lot of overlap.

### Types of Languages

Most languages can be loosely categorised into the groups below. I have described them in the order in which they became popular historically - as this is actually a very good way to understand _why_ certain categories or patterns evolved.

#### Imperative or Procedural Languages

**Imperative** or **Procedural** languages are essential to understand, at least conceptually. These languages are often **low-level**, they instruct the computer to very explicitly perform a sequence of operations. The earliest programming languages were procedural.

Some key examples:

[Assembly](https://en.wikipedia.org/wiki/Assembly_language) - not a specific language but the collection of all languages which basically allow you to express logic in the form of instructions which correspond to a chipset. This was one of the earliest ways to program and is perhaps the "most" imperative - you are typing out code which very closely corresponds to the chipset instructions which will be performed. A challenge with these languages is that they are often exceptionally complex to work with and require a deep understanding of how CPUs work and code will often be specific to a chipset. The power of these languages tends to be in the ability to be able to write highly optimised code, but with a high cost in complexity.

[C](https://en.wikipedia.org/wiki/C_(programming_language) - a huge amount of code written in assembly would be repetitive. The C language was a higher level abstraction which allowed logic to be expressed in a more friendly, readable form, which would then be compiled into binaries which target a given chipset. This meant that code would be easier to write, maintain, and make portable - the compiler would be responsible for turning the language constructs into machine code for the target chipset.

## How to Learn

Simple programming exercises, such as the ones given in the [Exercises](#exercises) section can be useful for learning _syntax_. However, it is really important when learning a programming language to make sure that you learn the _idioms_. This means you should learn how people commonly write code using this language. There is no point learning Java and trying to make it work in the way that you like Rust to work - the languages are used for different purposes. You want to write _idomatically correct_ code, code which people who are familiar with the language will understand quickly and which follow common programming patterns.

Some languages are highly idiomatic - there are extremely well-defined ways of writing them, particularly when creating certain types of project. An example would be a writing a web server in Java using "Spring Boot". There are standard patterns which are used for dependency injection, inversion of control, separation of concerns and so on, and it is important to use these conventions rather than creating your own.

Other languages are more flexible, but come with the challenge that there are _many_ idioms. One example would be ECMASript - it is possible to write code which is procedural in style, object orientated, functional, or even create meta-languages. The very flexibility can make the language hard to learn - some projects will use one set of idioms, other projects will use others.

### Find Excellent Examples

One of the most effective ways to learn an language is to find some really good examples of projects which are written in the language. Download the project, look through the codebase see if you can find where different elements live.

Some examples of excellent projects are given in the examples listed below.

## Languages

### Node.js

## Exercises

The following exercises may be useful for learning languages. Note that basic examples are only really going to help you learn the _syntax_, rather than the _idioms_, so I would in general prioritise more 'real-world' activities where possible!

## Pascal's Triangle

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

I've got an implementation that's clearly commented and tested at [github.com/dwmkerr/fsharpexperiments](https://github.com/dwmkerr/fsharpexperiments).

## Langton's Ant

tl;dr - Hard, great opportunities to be clever and use language specific features.

[Langton's Ant](http://en.wikipedia.org/wiki/Langtons_ant) is another mathematical simulation. In the simulation you create a basic universe with a few rules and let it run - it's quite similar to [Conway's Game of Life](http://en.wikipedia.org/wiki/Conway%27s_Game_of_Life).

A screenshot of such an application, written in Javascript would look like this:

![Langton's Ant](https://raw.githubusercontent.com/dwmkerr/langtonsant/master/docs/langtonsant.jpg)

(This project is on GitHub at [github.com/dwmkerr/langtonsant](https://github.com/dwmkerr/langtonsant)).

What should this teach?
* More complex collections
* State management
* Console or process input
* Console, graphical or file output
* Basic algorithms.

## Skip Lists

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
