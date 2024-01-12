
Geekasd
====

[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](https://choosealicense.com/licenses/isc/)
[![GoDoc](https://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/kaspanet/kaspad)

Gekkasd is the reference full node Geekas implementation written in Go (golang).

## What is Geekas

Geekas is a proof-of-work cryptocurrency based on the wonderfull KASPA coin which is based on It is based on [the PHANTOM protocol](https://eprint.iacr.org/2018/104.pdf), a generalization of Nakamoto consensus. The difference of Geekas is that a portion of the transactions fees are reverted to social projects. We want crypto to be seen as something for everyone and that also benefits who is in need.

## Requirements

Go 1.18 or later.

## Installation

#### Build from Source

- Install Go according to the installation instructions here:
  http://golang.org/doc/install

- Ensure Go was installed properly and is a supported version:

```bash
$ go version
```

- Run the following commands to obtain and install geekasd including all dependencies:

```bash
$ git clone https://github.com/leogeeko/geekasd
$ cd geekasd
$ go install . ./cmd/...
```

- Geekasd (and utilities) should now be installed in `$(go env GOPATH)/bin`. If you did
  not already add the bin directory to your system path during Go installation,
  you are encouraged to do so now.


## Getting Started

Geekasd has several configuration options available to tweak how it runs, but all
of the basic operations work with zero configuration.

```bash
$ geekasd
```

## Discord
Join our discord server using the following link: [https://discord.gg/YNYnNN5Pf2](https://discord.gg/42XG28cR)

## Issue Tracker

The [integrated github issue tracker](https://github.com/leogeeko/geekasd/issues)
is used for this project.

## Documentation

The [documentation](https://github.com/leogeeko/docs) is a work-in-progress

## License

Gekkasd is licensed under the copyfree [ISC License](https://choosealicense.com/licenses/isc/).
