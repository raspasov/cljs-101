# Clojure(Script) 101

### Start a ClojureScript Node REPL:

``` clojure
clj -Sdeps '{:deps {org.clojure/clojurescript {:mvn/version "RELEASE"}}}' -M -m cljs.repl.node
```

At the repl you should be able to:

``` clojure
(require ’foo.core)
(in-ns ’foo.core)
```

``` clojure
(my-add 3 3)
;=> 6
```
