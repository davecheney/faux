faux
====

A clone of the cmd/go tool

installation
------------

 * you need `gccgo` 4.9 or later, preferably from trunk, [http://golang.org/doc/install/gccgo](http://golang.org/doc/install/gccgo)
 * `go install -compiler gccgo github.com/davecheney/faux` will install a version of `faux` built with `gccgo`
 * `faux` will now default to `-compiler gccgo`, use it as you would `go`.
