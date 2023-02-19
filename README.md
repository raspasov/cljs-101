# How to start a ClojureScript Node REPL

### MacOS

1. Make sure you have node installed:
```
brew install node
```
2. Start the REPL:

``` clojure
clj -Sdeps '{:deps {org.clojure/clojurescript {:mvn/version "RELEASE"}}}' -M -m cljs.repl.node
```

### Windows

**WARNING**: Does not on MacOS. Use the command above.


Here we need to do some additional escaping like this:

``` clojure
clj -Sdeps '{:deps {org.clojure/clojurescript {:mvn/version \"RELEASE\"}}}' -M -m cljs.repl.node
```

