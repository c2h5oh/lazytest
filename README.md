# Lazytest

[![Go Report Card Badge](http://goreportcard.com/badge/c2h5oh/lazytest)](http://goreportcard.com/report/c2h5oh/lazytest)

A continuous test runner for Go.

Once started, it will listen for file changes in a given directory. If a file change is detected, only the tests affected by that file change will be re-run.

### Instalation:
````
go get github.com/c2h5oh/lazytest/cmd/lazytest
````


### Usage:
````
  -exclude string
      exclude paths (default "/vendor/")
  -extensions string
      file extensions to watch (default "go,tpl,html")
  -root string
      watch root (default ".")
````
