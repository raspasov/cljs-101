# Clojure(Script) 101

## Start a ClojureScript Node REPL

### On Linux and Mac

``` clojure
clj -Sdeps '{:deps {org.clojure/clojurescript {:mvn/version "RELEASE"}}}' -M -m cljs.repl.node
```

### On Windows

Here we need to do some additional escaping like this:

``` clojure
clj -Sdeps '{:deps {org.clojure/clojurescript {:mvn/version \"RELEASE\"}}}' -M -m cljs.repl.node
```

At the repl you should be able to:

``` clojure
(require 'foo.core)
(in-ns 'foo.core)
```

``` clojure
(my-add 3 3)
;=> 6
```
