# Colour library for Futhark

Colour manipulation functions adapted from the
[Gloss](https://hackage.haskell.org/package/gloss) library by Ben
Lippmeier.

## Installation

```
$ futhark-pkg add github.com/athas/matte
$ futhark-pkg sync
```

## Usage example

```
$ futharki
> import "lib/github.com/athas/matte/colour"
> argb.mix 0.5 argb.white 0.5 argb.black
-4934476i32
```
