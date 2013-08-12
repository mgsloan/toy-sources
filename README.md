toy-sources
===========

This repository contains a `sources.txt` file in the format expected by
[cabal-meta](https://github.com/yesodweb/cabal-meta).  This allows you to build
and develop the most recent HEAD versions of the toy packages.

Usage
-----

```
git clone https://github.com/mgsloan/toy-sources.git
cd toy-sources
cabal-meta install
```

If all goes well, the HEAD versions of the toys packages will now be in the
`vendor/` directory, and be installed to your local cabal package database.

One possible source for build failure might be if these libraries depend on the
HEAD versions of diagrams packages.  While currently they build with the hackage
version of the diagrams packages (0.7), at some point in the future this might
not be the case.  If so, an easy way to install the HEAD versions of the
diagrams packages is to use
[diagrams-sources](https://github.com/diagrams/diagrams-sources).
