
Generting and compiling this openapi.yaml with oapi-codegen 1.12.4 works fine; that's
the old/ dir.

But with 1.13.2:
```
$ go build ./new
new/api.gen.1.13.2.go:336:29: undefined: Misc400Error
new/api.gen.1.13.2.go:337:29: undefined: Misc404Error
new/api.gen.1.13.2.go:380:12: undefined: Misc400Error
new/api.gen.1.13.2.go:387:12: undefined: Misc404Error
```
