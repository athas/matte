# Colour library for Futhark [![CI](https://github.com/athas/matte/workflows/CI/badge.svg)](https://github.com/athas/matte/actions) [![Documentation](https://futhark-lang.org/pkgs/github.com/athas/matte/status.svg)](https://futhark-lang.org/pkgs/github.com/athas/matte/latest/)

Colour manipulation functions adapted from the
[Gloss](https://hackage.haskell.org/package/gloss) library by Ben
Lippmeier.

## Installation

```
$ futhark pkg add github.com/athas/matte
$ futhark pkg sync
```

## Usage example

```
$ futhark repl
> import "lib/github.com/athas/matte/colour"
> argb.mix 0.5 argb.white 0.5 argb.black
4290032820u32
```
