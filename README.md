# Example

## Prerequisite

Make sure `libsodium` & `libsystemd` are installed. 

A sample installation on Ubuntu is:

```sh
sudo apt update && sudo apt install libsodium-dev libsystemd-dev
```

## Build

```sh
cabal build
```

## Run

```sh
cabal run simple-setup
```

## Development

We can utilize a repl for rapid development.

``` sh
cabal repl
:l Main
```
