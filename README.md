# Rust Guessing Game

My journey into Rust started now and this is my first Rust code from Chapter 2 of [The Rust Programming Language](https://doc.rust-lang.org/stable/book/) book. 
I am planning to add as many as possible features to this project parallel by the learning process.


## Things I learned and used in this project

### Cargo
Package system for Rust. You can build and run Rust programs with the `cargo` command.
It's built in dependency manager.
You can easily manage your dependencies with it and publish your own packages to crates.io.
Equivalent to npm.

### `main` function

Rust program starts by running main function. Functions are defined with the `fn` keyword.

### `println!` macro

For now, I learned that names ends with `!` are macros, and they are working a bit different from regular functions.

### `mut` keyword

In Rust all variables are immutable by default. You can change the value of a variable with the `mut` keyword.

### `let`, `match`, `expect`

`let` is used to declare a variable. `match` is used to match a value against a pattern. 
`expect` method of `Result` type is used to check if the value is `Ok` or `Err` and panics if it is `Err`.
Another way to check if the value is `Ok` or `Err` is with the `match` expression. 
Its works like `switch` statement in Javascript.

### `loop`, `break`, `continue`

`loop` keyword is used to infinite loop through a block of code. 
`break` keyword is used to break out of the loop.
`continue` is used to skip the current iteration of the loop.


## TODO

Publishing this code here inspired by [GitSquared/guessing_game](https://github.com/GitSquared/guessing_game) and i will implement features which i like from there.
Maybe I will expand this list in the future.

- [ ] Attempt Count
- [ ] Colored console output
- [ ] CSPRNG implementation
- [ ] Icons
- [ ] More features
