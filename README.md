# ![Vela](https://raw.githubusercontent.com/am-kantox/vela/master/stuff/vela-48x48.png) Vela

**The tiny library to ease handling expiring invalidated cached series**

## Installation

```elixir
def deps do
  [
    {:vela, "~> 0.7"}
  ]
end
```

## Changelog

- **`0.9.3`** — allow `:atom` and `{GenServer, :on_start}` as type definition
- **`0.9.0`** — allow a precise type definition of each serie via `type: type()` keyword parameter
  a series keyword parameter
- **`0.8.0`** — allow a `corrector/2` callback to allow correction of rejected values as
  a series keyword parameter
- **`0.7.2`** — `Vela.put/3`
- **`0.7.0`** — exact type and behaviour for those using `Vela`
- **`0.6.3`** — fix `threshold` to use `compare_by/1` for cumbersome values
- **`0.6.1`** — use `threshold` to prevent adding outliers to series
- **`0.6.0`** — `Vela.δ/2` / `c:Vela.delta/2` returning a keyword `[{serie, {min, max}}]`

## [Documentation](https://hexdocs.pm/vela)
