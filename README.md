# souffle-haskell-example

This project serves 2 purposes:

1. Useful for checking (in CI) if a new souffle release works correctly with
   [souffle-haskell](https://github.com/luc-tielen/souffle-haskell)
2. Show how to use souffle-haskell from another cabal project.

## Getting started

```bash
$ nix develop
$ DATALOG_DIR=cbits/ cabal run
```

Note that `DATALOG_DIR` is only needed for interpreted mode, switching to
compiled mode makes this environment variable not needed.
