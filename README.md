# syncpool
The `mkm.pub/syncpool` package provides a generic wrapper around the [sync.Pool](https://pkg.go.dev/sync#Pool) structure.

This package is just a thin wrapper around the underlying `interface{}` based implementation in the stdlib. 

It requires go1.18. If when you're reading this go1.18 is not released yet you can download [1.18beta](https://go.dev/blog/go1.18beta1) or just try with the latest [gotip](https://pkg.go.dev/golang.org/dl/gotip).

## Usage

```bash
go get mkm.pub/syncpool
```

