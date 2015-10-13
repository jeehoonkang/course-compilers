# Parsing


Parsing is *giving a 2-dimensional structure to a 1-dimensional
string*.  For example, a compiler may get the following string input
from the user:

```
#include <stdio.h>

int main() {
  printf("Hello, World!\n");
  return 0;
}
```

It is just a string, and we can do almost nothing compiler-ish with
just this string.  So compilers give some structure on the string so
that they can do some useful works.  Below is an example structure of
the above string:

- preprocessor directives
    + `#include`
        * filename: `"stdio.h"`
- global declarations
    + function definition
        * type: `int ()`
        * name: `"main"`
        * body:
            - function call
                + function to call: `"printf"`
                + arguments
                    * string constant `"Hello, World!\n"`
            - return
                + return value: `0`

Note that this is 2-dimensional because the bullets can be represented
as a tree, which is clearly 2-dimensional.

This 2-dimensional structure is much more useful than the
1-dimensional string, because:

- 2-dimensional structures have the essence of the information.
  Unnecessary details, such as the number of spaces (` `) or the
  position of brackets (`{`, `}`), are abstracted out.

- Relevant information is easily retrieved.  For example, it is easy
  to find the name or the body of a function definition.

Thus giving a 2-dimensional structure to a 1-dimensional string, or
*parsing*, is essential in processing programs written in programming
languages in any flavor.  Not only compilers but also interpreters,
static analyzers, and automatic test generators parse their input
string.


Typically, a parser is divided into the following components:

- Lexer: tokenizing a string into a stream of syntactic units;

- Grammar: representing the structure of 2-dimensional objects of
  interest;

- Parser: matching the grammar to the stream of syntactic units.

Thus overall, an input string pass through lexing and then parsing
w.r.t. a given grammar, and a corresponding 2-dimensional object is
output.  In the remaining section, we will explain each component in
more detail.


## Lexer

TODO


## Grammar

TODO


## Parser

TODO

### LR(k) Algorithm

TODO

### LALR Algorithm

TODO
