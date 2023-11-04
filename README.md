# go-ptr

## About

Trivial library to handle taking pointer for trivial cases

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

[Go Dev reference](https://pkg.go.dev/github.com/teran/go-ptr)
