# TodoPlus

This is just an example application that follows a [Live Coding series][playlist]
on YouTube. This project builds out yet another Todo application using
React and Redux. We will *very* loosely follow the
[Redux Todo Example][example], but with one major twist. We will be defining our
state transitions using the [State ADT][state-docs] from the
[crocks ADT library][crocks].

## Using This Repository
In order to make things easy to follow along at home, this repo organizes the
sessions into branches. Each session will have its own branch, which is branched
off the previous session. As a viewer, you are able to check out a branch which
will be  available after each session. This allows you to check out the previous
branch and follow along, or diverge and experiment with your own ideas and
intuitions.

It is recommend that you clone this repository down to follow along on your
local environment. Once you have this project on your box, just pull down
the repo from `master` and checkout the branch you are interested in.

Below is a list of each of the sessions and their respective branches, including
a link to the video:

| session | branch | video |
| --- | --- | --- |
| Practical ADTs -- Todo+ (Part 0x00) | [0x00][code-00] | [YouTube][vid-00]

## Useful Commands

#### `yarn setup`
This app evolves over time with each session, and as such, dependencies may vary
greatly from branch to branch. For the viewers out there running `yarn` on a
POSIX(-ish) system like Linux or Mac OSX, using this setup command will clear
out the old dependencies and bring in the new ones.

**Note for Windows and non-yarn users**: There are many ways and workflows to
handle dependency management, each with their own reasons and opinions. Without
requiring people to install global modules to handle cross-platform concerns, we
just went with this setup for these lessons. So dependency management is
entirely up to you. Once all dependencies are installed, the rest of the
commands are cross platform.

#### `yarn start`
This is the bread and butter for development in this project. Running it will
compile all code (HTML, CSS, and JS) and setup watches for the various files.
Once everything is built and running, a BrowserSync web server serves up the
results on:
`http://localhost:1337/`.

[playlist]: https://www.youtube.com/playlist?list=PLjvgv-FpMo7XY8V1puB7TrMBt3r5W_zA6
[example]: https://redux.js.org/basics/example-todo-list
[state-docs]: https://evilsoft.github.io/crocks/docs/crocks/State.html
[crocks]: https://github.com/evilsoft/crocks

[code-00]: https://github.com/evilsoft/todo-plus/tree/0x00
[vid-00]: https://youtu.be/vaKD2-eG9-g