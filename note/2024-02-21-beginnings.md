# Beginnings

I was recently inspired by the project
[rustlings](https://github.com/rust-lang/rustlings) to create a game focused
around learning the fundamentals of algorithms and data structures. My idea for
making it into a game is primarily because I like games and that in itself might
make some of these algorithms and algorithm recognition stick.

The idea is basically you start out with a limited inventory of tools. Things
like `for`, `map`, `slice`, etc. These tools and their brute force application
will work at the beginning, but as you progress through the Algorinth you will
unlock new techniques and applications of those tools. The inventory, a json
file, will persist between play sessions and can be referenced through the CLI.
My idea of encounters and boss fights includes using go tests with specific
checks for time and space complexity. There is also the idea of having different
difficulties that would modify things like HP or a rogue-like mode that resets
your progress on death.
