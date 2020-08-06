# Identicon

This project was created while following along with Stephen Grider's course, [The Complete Elixir and Phoenix Bootcamp](https://www.udemy.com/course/the-complete-elixir-and-phoenix-bootcamp-and-tutorial/). It generates an identicon as a `.png` file.

## Installation

```elixir
mix deps.get
```

## Run

```elixir
# open the interactive shell
iex -S mix

# generate an identicon
Identicon.main("banana")
```