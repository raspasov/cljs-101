# How to start a ClojureScript Node REPL

## MacOS

1. Make sure you have node installed:
``` bash
brew install node
```
2. Start the REPL:

``` bash
clj -Sdeps '{:deps {org.clojure/clojurescript {:mvn/version "RELEASE"}}}' -M -m cljs.repl.node
```

## Windows

**WARNING**: **Do not use on MacOS.** Use the command above.


Here we need to do some additional escaping like this:

``` bash
clj -Sdeps '{:deps {org.clojure/clojurescript {:mvn/version \"RELEASE\"}}}' -M -m cljs.repl.node
```

