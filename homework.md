# Homework

As a homework, you will construct (a subset of) C-to-ARM compilers from
the scratch.

TODO: motivation, ...


## Skeleton

- We provide skeletons for the homework based on the two languages:
  the C++ skeleton (TBA) and the OCaml skeleton (TBA).  You can use
  either of them.

- The skeletons are [Git](git.md) repositories.  It is *required* to
  maintain a Git repository for your homework: you will submit the
  repository.

- The skeletons contain:

    + README for building & extending the skeleton;

    + Makefile (a build script);

    + Sample parser written in a parser generator;

    + Skeleton source codes for the typical organization of compilers.


## Specification

To construct a compiler, typically you should:

- Write a C parser;

- Design intermediate languages;

- Write pretty-printers for the languages;

    + An ARM pretty-printer is required since a compiler should print
      out the target language.  Also, it is strongly recommended to
      write pretty-printers for the other languages for debugging
      purposes;

- Write a translator from C to IL(s) & IL(s) to ARM;

- Write optimizations on the IL (optional);

- Do anything you want for your own compiler!


TODO: what is th homework's specification?

### Timeline

TODO


## Honor Code

*Do not cheat*.  The cheating includes, but not limited to, the
following activities:

- *Copying other's source code*, including those of fellow students or
  around the internet.  You can see other's source code, but it is
  strictly limited to copy as-is.

- TODO
