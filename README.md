# mey-library

This repository is a collection of common libraries used in the mey project.
See [GoDoc](https://godoc.org/github.com/meycoin/mey-library) to get more detail descriptions and usages.

## config

Package config provides an easy way to create and manage configurations for mey projects written in go.

## db

Package db is an wrapper of database implementations. Currently, this supports [badgerdb](https://github.com/dgraph-io/badger).
More implementations (e.g. leveldb) will be updated in the future

## log

Package log is a global and configurable logger pkg, based on [zerolog](https://github.com/rs/zerolog)