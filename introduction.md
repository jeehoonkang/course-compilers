# Introduction

There is a big gap between high- and low-level programming languages.
*High-level programming languages*, such as C, C++, Rust, C#, Java,
Scala, Haskell, and OCaml, focus on supporting programmers to clearly
present the idea behind the programs written in them.  On the other
hand, *low-level languages*, such as the ARM, x86, and PowerPC
Assembly languages, focus on supporting the machine (i.e., CPU) to
easily understand and efficiently execute programs.

*Compilers* bridge the gap between the high- and low-level languages.
At the very early stage of computing, there was no such a gap because
people just wrote programs in low-level languages, even though it is
really costly and error-prone.  So
[Grace Hopper](https://en.wikipedia.org/wiki/Grace_Hopper) invented
the first compiler, which automatically translates a program written
in a high-level language into another written in a low-level language.
Today compilers are a fundamental building block of the entire
computer science and engineering: only few programmers are writing
programs in low-level languages, and almost all the programs are
written in high-level languages and then compiled.

In this course we will study the principle and the practice of
compiler construction:

- Principle:

    + Programming languages, in essence
    + Difference between high- and low-level languages
    + The meaning of translation and its specification
    + Typical organization of compilers

- Practice: constructing (a subset of) C-to-ARM compilers from the
  scratch!
