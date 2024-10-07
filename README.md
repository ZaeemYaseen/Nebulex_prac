# Introduction
In this directory, I will be practicing Nebulex, a dependency of Elixir. Nebulex is an in-memory and distributed caching framework for Elixir that allows for the temporary storage and retrieval of data in an Elixir application. Just as a computer system uses cache to store frequently accessed data for faster retrieval, Nebulex provides similar functionality within an Elixir application. This reduces the time and resources needed to fetch data from the database repeatedly. Instead, the most recent or frequently used data is stored in the cache (by Nebulex) and fetched from there, improving efficiency and response time.

# Nebulex

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `nebulex` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:nebulex, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at <https://hexdocs.pm/nebulex>.

