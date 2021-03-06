# pangu.ex

[![Build Status](https://travis-ci.org/cataska/pangu.ex.svg?branch=master)](https://travis-ci.org/cataska/pangu.ex)
[![hex.pm version](https://img.shields.io/hexpm/v/pangu.svg)](https://hex.pm/packages/pangu)

Paranoid text spacing for good readability, to automatically insert whitespace between CJK (Chinese, Japanese, Korean) and half-width characters (alphabetical letters, numerical digits and symbols).

- [pangu.clj](https://github.com/coldnew/pangu.clj) (Clojure)
- [pangu.go](https://github.com/vinta/pangu) (Go)
- [pangu.java](https://github.com/vinta/pangu.java) (Java)
- [pangu.js](https://github.com/vinta/pangu.js) (JavaScript, both Node.js and Browser)
- [pangu.objective-c](https://github.com/Cee/pangu.objective-c) (Objective-C)
- [pangu.php](https://github.com/Kunr/pangu.php) (PHP)
- [pangu.py](https://github.com/vinta/pangu.py) (Python)
- [pangu.rb](https://github.com/dlackty/pangu.rb) (Ruby)

## Installation

Add pangu to your `mix.exs` dependencies:

```elixir
def deps do
  [{:pangu, "~> 0.1.0"}]
end
```

and run `$ mix deps.get`.

## Usage

```elixir
require Pangu
Pangu.spacing("Sephiroth見他這等神情,也是悚然一驚:不知我這Ultimate Destructive Magic是否對付得了?")
# output: Sephiroth 見他這等神情, 也是悚然一驚: 不知我這 Ultimate Destructive Magic 是否對付得了?
```

## License

Released under the [MIT License](http://opensource.org/licenses/MIT).
