Original by Rob Pike:
```
I wanted to see how hard it was to implement this sort of thing in Go, with as nice an API as I could manage. It wasn't hard.

Having written it a couple of years ago, I haven't had occasion to use it once. Instead, I just use "for" loops.

You shouldn't use it either.
```

This example rewriten using `go2go` with [generics prototype](https://go.googlesource.com/proposal/+/refs/heads/master/design/go2draft-type-parameters.md).

To play with this example you should [install](https://github.com/golang/go/issues/39619) development version of go.

To run test `go tool go2go test` is just enough.
