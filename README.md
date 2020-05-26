following https://clojurescript.org/guides/quick-start

Some commands

Compile
```
clj --main cljs.main --compile hello-world.core --repl
```

Compile for node
```
clj -m cljs.main --target node --output-to main.js -c hello-world.core
```

On a REPL based dev workflow in cljs https://figwheel.org/tutorial#working-at-the-repl
