---
title: "Introduction"
---

[%b Tedre2008 %] describes three views of computing:

-   The *mathematical tradition*
    considers programs to be implementations of algorithms
    which are correct or incorrect as well as more or less efficient.
    Its main aim is to create coherent theoretical structures and systems.

-   The *engineering tradition*
    thinks of programs as processes that can affect the world,
    which are more or less effective and reliable.
    Its goal is to build things that work.

-   The *scientific tradition*
    views programs as more or less accurate models of natural or artificial processes,
    and sees them as a way to deepen our understanding of other things.

The starting point of this book is that there is a fourth option:
a *humanist tradition*
that focuses on who gets to decide how computing is used
and on how what we build and how we build it are shaped by the ways we think.

That probably sounds like warm hugs and fuzzy blankets,
so try this.
[% b Sedano2017 %] found that software development projects have
nine types of waste:
building the wrong feature or product,
mismanaging the backlog,
rework,
unnecessarily complex solutions,
extraneous cognitive load,
psychological distress,
waiting and multitasking,
knowledge loss,
and ineffective communication.
*None of these are software issues,*
so if you only think about the code in your project and not about the people writing it,
everything will take longer and hurt more than it needs to.

Why hasn't this problem already been solved?
Again, the answer is "people".
The authors of [%b Storey2021 %] asked programmers what social and technical factors matter to them the most,
then ranked the results.
The most and least important out of the 40 topics were:

|    | Most                   |     | Least                                          |
| -- | ---------------------- | --- | ---------------------------------------------- |
| 1. | Good manager           | 36. | Lateral move opportunities                     |
| 2. | Perceived productivity | 37. | Training for engineering technologies          |
| 3. | Rewards                | 38. | Training for soft skills                       |
| 4. | Team culture           | 39. | Private office / number of people in workplace |
| 5. | Skills are well used   | 40. | Training for engineering tools                 |

In other words,
everyone wants a good manager and a good team culture,
but they place training in the skills those things need near the bottom of the list.
And everyone wants to feel they're productive,
but being taught how to use tools well is dead last among programmers' priorities.

This book's aim is to introduce you to those skills
and to convince you that they're worth learning.
To start,
here's an overview of the departments in a typical tech company:

| Department         | Also Called | What It Does |
| ------------------ | ----------- | ------------ |
| Engineering        | -           | Build, test, and deploy software |
| Human Resources    | Community   | Hiring, firing, benefits, and staff development |
| Marketing          | Awareness   | Making people aware of who you're trying to help and how |
| Product Management | —           | Figure out what problems to solve and what features will solve them |
| Project Management | —           | Keep track of who's doing what and when it's needed |
| Sales              | Adoption    | Getting people from "this looks interesting" to "we're using it" |
| Support            | Success     | Removing roadblocks and providing help |

Another way to look at these roles is to ask what disaster they are responsible for preventing:

| Department         | What Risk It Addresses |
| ------------------ | ---------------------- |
| Engineering        | We aren't building things or the things we build don't work |
| Human Resources    | We don't have the right people to do the work |
| Marketing          | People don't know we exist or how we can help |
| Product Management | We're building the wrong thing |
| Project Management | People aren't working on the right things or aren't working well together |
| Sales              | It's too hard to *start* using what we build |
| Support            | It's too hard to *keep* using what we build |
