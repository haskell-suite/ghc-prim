To compile ghc-prim with haskell-names, do something like this:

    cabal configure -w gen-iface --haskell-suite -finclude-ghc-prim
    cabal build
    cabal install --only
