# Software Development

Compiler is a complex, carefully-written, and often a huge piece of
software, so it is strongly recommended to apply good coding practices
when doing your homework.  It is hard to define what is good and what
is bad: people disagree on what is the best practices, and indeed the
"best" practices differ case-by-case.  In this section we aim somewhat
lower: describing the minimal practices that most people agree on.

- Use a
  [version control system](https://en.wikipedia.org/wiki/Version_control).
  See [Git](git.md) for more detail.

- Use an
  [issue tracking system](https://en.wikipedia.org/wiki/Issue_tracking_system).
  The issue tracker accompanied by a GitHub repository would be
  sufficient for our purposes.  Track bugs, concerns, features to
  implement, or anything worth tracking in an issue tracking system.
  It helps you:

    + Never forget important issues.  Issues are recorded permanently.
      People forget what they knew.

    + Record relevant information on the issue.  Just by revisiting
      the issue you can easily recall everything related to the issue.

    + Easily discuss with collaborators, if any.

- Clearly define your task, and divide the task if necessary.

  [Feynman](https://en.wikipedia.org/wiki/Richard_Feynman) invented
  the Feynman algorithm to solve almost all the problems:

    + Write down the problem.
    + Think real hard.
    + Write down the solution.

  It seems nonsensical at first glance, but it contains an invaluable
  wisdom.  Writing down the problem you face is the beginning of
  problem solving, and often it is the most difficult step.  Also, the
  more clear the problems is described, the easier it is to solve the
  problem.  Furthermore, if the task is too big to think on it, then
  it is really helpful to properly divide the task into subtasks.

  Also, do not forget to register all the divided subtasks in an issue
  tracker.

- Properly test your software.  Fortunately, in this course we provide
  a set of C programs you can test your compiler on.  Find bugs in
  your compiler by extensively testing it with the given C programs.
  It is also recommended to write more C programs to test with.
