# A Tour of Go Notebook

[A tour of go](https://go-tour-jp.appspot.com/list) in Jupyter notebook using [gophernotes](https://github.com/gopherdata/gophernotes)

## Setup

- for MacOS

``` shell
$ brew install zmq
$ go get github.com/gopherdata/gophernotes
$ mkdir -p ~/Library/Jupyter/kernels/gophernotes
$ cp $GOPATH/src/github.com/gopherdata/gophernotes/kernel/* ~/Library/Jupyter/kernels/gophernotes
```
