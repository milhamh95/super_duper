# SuperDuper

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `super_duper` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:super_duper, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at <https://hexdocs.pm/super_duper>.

### Start and stop supervisor at will

```
// start elixir without supervisor
iex -S mix run --no-start

{:ok, pid} = SuperDuper.Application.start :duper, []
Supervisor.stop pid
```
