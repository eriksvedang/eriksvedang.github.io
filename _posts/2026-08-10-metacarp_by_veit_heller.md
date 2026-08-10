---
layout: note
title: "Metacarp by Veit Heller"
color: '#09F'
image: Metacarp.png
tags: [blog, note]
---

For the last 5-6 years there hasn't been much work on
[Carp](https://www.eriksvedang.com/carp), neither by me, nor the
community. The whole project did feel quite dormant and possibly
"done" (which in the software world often equals dead). You could use
the language for stuff, but no one really did.

All of that changed during the first half of 2026 when [Veit
Heller](https://veitheller.de/) started contributing major features to
the project again, big time. Veit has been a core maintainer of the
project for a long time, and has also helped Carp reach a bigger
audience through his blog and by giving talks at conferences about it.

In addition to the language improvements, he also wrote a bunch of
useful libraries (all collected in the
[Carpentry](https://github.com/carpentry-org/) Github
organization). Using the libraries made him find even more bugs in the
language that then got fixed, improving the state of the compiler
vastly.

All of this culminated in Veit deciding to rewrite the Carp compiler
in Carp itself, eventually creating
[Metacarp](https://github.com/cyberwitchery/metacarp)! This new
compiler passes the original test suite of the regular compiler (which
is written in Haskell) and can also compile itself.

Given how well all of this works, perhaps Metacarp will become the
best compiler to use for Carp programmers. Maybe it can even help me
fulfill my personal dream of using Carp for an actual finished game?
In any case, thanks Veit for all your hard work!
