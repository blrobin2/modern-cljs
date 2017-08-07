# ClojureScript Playground
Following these tutorials: https://github.com/magomimmo/modern-cljs

## Prerequisites
* Java 1.8
* [Boot](http://boot-clj.com/)

## How to get started
1. In shell, run `boot dev`
1. Once it resolves, in a separate shell run `boot repl -c`
1. Once in waiting state, go to localhost:3000
1. Second shell will indicate connection. Test this by running `(js/alert "Hello, Nurse!")`
1. In the browser, you should get a JS alert containing the text
1. Open the console, and you should see the JS console log from src/cljs/modern_cljs/core.cljs