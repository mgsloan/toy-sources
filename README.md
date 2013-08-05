toy-sources
===========

This package contains a `sources.txt` file in the format expected by
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
