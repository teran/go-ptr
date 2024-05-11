# go-ptr

## About

![Test & Build status](https://github.com/teran/go-ptr/actions/workflows/go.yml/badge.svg)
[![Go Report Card](https://goreportcard.com/badge/github.com/teran/go-ptr)](https://goreportcard.com/report/github.com/teran/go-ptr)
[![Go Reference](https://pkg.go.dev/badge/github.com/teran/go-ptr.svg)](https://pkg.go.dev/github.com/teran/go-ptr)

Trivial and clean library to handle taking pointers just not to repeat the same stuff in every project.

## Usage

```golang
package example

import (
    ptr "github.com/teran/go-ptr"
)

func main() {
    v := 123.0

    fmt.Printf("%#v\n", ptr.Float64(v))
}
```
