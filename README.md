# Awesome FP JS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome functional programming in JavaScript


## Table of Contents

* [Libraries](#libraries)
  * [Data Structures](#data-structures)
  * [Algebraic Data Types](#algebraic-data-types)
  * [Lenses](#lenses)
* [Functional Languages that Compile to JavaScript](#functional-languages-that-compile-to-javascript)
* [Resources](#resources)
  * [Books](#books)
  * [Articles](#articles)
  * [Videos](#videos)
  * [Examples and Exercises](#examples-and-exercises)
* [Community](#community)
* [Contribution](#contribution)

## Libraries

* [Ramda](https://github.com/ramda/ramda) – A practical functional library for JavaScript that is designed specifically for a functional programming style. A style that makes it easy to create functional pipelines and never mutates user data.
* [Folktale](http://folktalejs.org/) – Folktale is a suite of libraries for generic functional programming that allows you to write elegant modular applications with fewer bugs and more reuse.
* [lodash/fp](https://github.com/lodash/lodash/wiki/FP-Guide) – An instance of [Lodash](https://github.com/lodash/lodash) with its methods wrapped to produce immutable, auto-curried, iteratee-first, data-last methods.
* [functional.js](http://functionaljs.com) – A lightweight functional JavaScript library that facilitates currying and point-free / tacit programming.
* [101](https://github.com/tjmehta/101) – A modern and modular JavaScript utility library made to work well with vanilla JavaScript methods.
* [fnuc](https://github.com/algesten/fnuc) – A functional library for CoffeeScript (and JavaScript) to facilitate functional composition and higher order functions.
* [barely-functional](https://github.com/cullophid/barely-functional) – A tiny (2.7kb) functional programming library using native ES5/6 operations.
* [prelude.ls](http://gkz.github.io/prelude-ls/) – A functionally oriented utility library somewhat based off of Haskell's Prelude module.
* [allong.es](http://allong.es/) – A collection of functions to facilitate writing JavaScript with functions as first-class values, designed to complement libraries like Underscore, not compete with them.
* [1-liners](https://github.com/1-liners/1-liners) – Functional tools that couldn’t be simpler. A dead simple functional utility belt, hand-crafted with love and attention.
* [fn-curry](https://github.com/thunklife/fn-curry) – A simple function to curry a function.
* [curry](https://github.com/thisables/curry) – Curry your functions using function bind syntax.
* [compose-function](https://github.com/stoeffel/compose-function) – Compose a new function from smaller functions.
* [functionize](https://github.com/paldepind/functionize) – A collection of functions which aid in making non-functional libraries functional.
* [lambdajs](https://github.com/loop-recur/lambdajs) – The full ECMAScript API done a functional way.
* [fp-dom](https://github.com/fp-dom/) – Making the DOM functional.
* [trifl](https://github.com/algesten/trifl) – A functional user interface library with unidirectional dataflow and a virtual dom.
* [funcy](https://github.com/bramstein/funcy) – An experiment in adding functional pattern matching to JavaScript. _Experimental_  :triangular_flag_on_post:
* [date-fp](https://github.com/cullophid/date-fp) – A functional utility library for working with JavaScript dates. All functions in date-fp are pure, autocurried and will not mutate the date objects they are applied to.
* [\_part\_](https://github.com/AutoSponge/_part_) – A micro library that encourages functional programming by making native methods available as partially applied functions.
* [claire](https://github.com/robotlolita/claire) – A property-based testing library for clearly specifying code invariants and behaviour.

### Data Structures

Write performant functional code by using the right data structures for the task.

* [Immutable.js](https://github.com/facebook/immutable-js) – Immutable persistent data collections.
* [Mori](https://github.com/swannodette/mori) – ClojureScript’s persistent data structures and supporting API from the comfort of vanilla JavaScript.
* [immutable-sequence.js](https://github.com/qiao/immutable-sequence.js) –  High performance implementation of Immutable Sequence in JavaScript, based on [Finger Trees](https://github.com/qiao/fingertree.js).
* [Timm](http://guigrpa.github.io/timm/) – Immutability helpers with fast reads and acceptable writes.
* [Lazy.js](https://github.com/dtao/lazy.js) – A utility library with a lazy engine under the hood that strives to do as little work as possible while being as flexible as possible.

### Algebraic Data Types

Use the laws of math instead of always reinventing your own thing. Algebraic!

* [FantasyLand](https://github.com/fantasyland/fantasy-land) – Not a library, but a specification of the Monad laws for libraries to follow.
* [daggy](https://github.com/puffnfresh/daggy) – Library for creating tagged constructors.
* [Sanctuary](https://github.com/plaid/sanctuary) – Sanctuary makes it possible to write safe code without null checks.
* [ramda-fantasy](https://github.com/ramda/ramda-fantasy) – Fantasy-Land compatible types for easy integration with Ramda.js.
* [monet.js](http://cwmyers.github.io/monet.js/) – A library that assists functional programming by providing a rich set of Monads and other useful functions.
* [union-type](https://github.com/paldepind/union-type) – A small JavaScript library for defining and using union types.
* [freeky](https://github.com/DrBoolean/freeky) – A collection of Free monads.
* [Fluture](https://github.com/Avaq/Fluture) – A Future library with included control utilities, high performance and great error messages.
* [fantasy-combinators](https://github.com/fantasyland/fantasy-combinators) – Common combinators.
* [fantasy-birds](https://github.com/fantasyland/fantasy-birds) – Port of the Haskell package Data.Aviary.Birds. Everything for your combinatory needs.

### Lenses

* [lenses](https://github.com/DrBoolean/lenses) – Composable [kmett](https://github.com/ekmett/lens) style lenses.
* [optics](https://github.com/flunc/optics) – Profunctor optics (Lens, Prism, iso).
* [ramda-lens](https://github.com/ramda/ramda-lens) – :ram: :mag_right: Lens library built on Ramda.
* [fantasy-lenses](https://github.com/fantasyland/fantasy-lenses) – Composable, immutable getters and setters. (Profunctor lenses WIP)
* [nanoscope](https://github.com/5outh/nanoscope) – Lenses with dotty support.
* [partial.lenses](https://github.com/calmm-js/partial.lenses) – Ramda compatible partial lenses. View, insert and update optional data.

## Functional Languages that Compile to JavaScript

* [ClojureScript](https://github.com/clojure/clojurescript) – Compiles [Clojure](http://clojure.org/), a hosted Lisp with immutable persistent data structures, to JavaScript.
* [Elm](http://elm-lang.org/) – A type-safe functional programming language for declaratively creating web browser-based graphical user interfaces. Implemented in Haskell.
* [PureScript](http://www.purescript.org/) – A small strongly typed programming language that compiles to JavaScript.
* [Idris](http://www.idris-lang.org/) – A general purpose pure functional programming language with dependent types.
* [GHCJS](https://github.com/ghcjs/ghcjs) – [Haskell](https://www.haskell.org/) to JavaScript compiler, based on GHC.
* [ElixirScript](https://github.com/bryanjos/elixirscript) – Compiles a subset of [Elixir](http://elixir-lang.org/), a dynamic, functional language designed for building scalable and maintainable applications, to JavaScript.
* [Js\_of\_ocaml](http://ocsigen.org/js_of_ocaml/) – Compiles [OCaml](http://ocaml.org/) bytecode to JavaScript, making it possible to run OCaml programs in the browser.
* [BuckleScript](https://bloomberg.github.io/bucklescript/) – JavaScript backend for [the OCaml compiler](https://ocaml.org/).
* [Scala.js](http://www.scala-js.org/) – Compiles [Scala](http://www.scala-lang.org/) to JavaScript.
* [LiveScript](http://gkz.github.io/LiveScript/) – LiveScript has a straightforward mapping to JavaScript and allows you to write expressive code devoid of repetitive boilerplate.

## Resources

### Books

* [Professor Frisby’s Mostly Adequate Guide to Functional Programming](https://github.com/MostlyAdequate/mostly-adequate-guide) – This is a book on the functional paradigm in general using the world’s most popular functional programming language: JavaScript. By [Brian Lonsdorf](https://twitter.com/drboolean) (2016)
* [JavaScript Allongé](https://leanpub.com/javascriptallongesix), the “Six” edition by [Reginald  Braithwaite](https://github.com/raganwald) (2016)
* [Functional Programming in JavaScript](https://www.manning.com/books/functional-programming-in-javascript) by Luis Atencio (2016)
* [Eloquent JavaScript](http://eloquentjavascript.net/) by Marijn Haverbeke (2014)
* [Functional JavaScript](http://shop.oreilly.com/product/0636920028857.do) by [Michael Fogus](https://github.com/fogus) (2013)

### Articles

* [The Two Pillars of JavaScript Pt 2: Functional Programming](https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4)
* [FP Concepts in JavaScript](https://medium.com/@collardeau/intro-to-functional-programming-concepts-in-javascript-b0650773139c) – An Intro to Functional Programming Concepts in JavaScript
* [Functional programming with JavaScript](http://stephen-young.me.uk/2013/01/20/functional-programming-with-javascript.html)
* [Why Curry Helps](https://hughfdjackson.com/javascript/why-curry-helps/)
* [Favoring Curry](http://fr.umio.us/favoring-curry/)
* [JavaScript and Type Thinking](https://medium.com/@yelouafi/javascript-and-type-thinking-735edddc388d)
* [Lazy, composable, and modular JavaScript](https://codewords.recurse.com/issues/four/lazy-composable-and-modular-javascript)
* [Why Ramda](http://fr.umio.us/why-ramda/) – Introduction to the principles of ramda. 
* [A Monad in Practicality: First-Class Failures](http://robotlolita.me/2013/12/08/a-monad-in-practicality-first-class-failures.html) – Introduction to Either.
* [A Monad in Practicality: Controlling Time](http://robotlolita.me/2014/03/20/a-monad-in-practicality-controlling-time.html) – Introduction to Futures.
* [A gentle introduction to functional JavaScript](jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-intro/) – A four-part series introduction functional programming in JavaScript.
* [Functional programming](https://glebbahmutov.com/blog/tags/functional/) – Many articles on various aspects of functional programming in JavaScript by Gleb Bahmutov.
* [Functional Programming Jargon](https://github.com/hemanth/functional-programming-jargon) – Jargon from the functional programming world explained in JavaScript.

### Videos

* [Classroom Coding with Prof. Frisby](https://www.youtube.com/watch?v=h_tkIpwbsxY&list=PLK_hdtAJ4KqX0JOs_KMAmUNTNMRYhWEaC) – A series that builds a “practical” web application with React and functional programming in JavaScript.
* [Hey Underscore, You're Doing It Wrong!](https://www.youtube.com/watch?v=m3svKOdZijA) – Underscore.js claims to be a functional programming library, but is it really?
* [Functional programming patterns for the non-mathematician](https://www.youtube.com/watch?v=AvgwKjTPMmM)
* [Pure JavaScript](https://vimeo.com/49384334)
* [Pure, functional JavaScript](https://vimeo.com/43382919)

### Examples and Exercises

* [FPJS-Class](https://github.com/loop-recur/FPJS-Class) – Functional Programming learned through JS
* [functional-javascript-workshop](https://github.com/timoxley/functional-javascript-workshop) – Teaching fundamental functional programming features of JavaScript
* [functional-frontend-architecture](https://github.com/paldepind/functional-frontend-architecture) – A functional frontend framework. Based on Ramda + union-type-js + Flyd + Snabbdom
* [cube-composer](https://github.com/sharkdp/cube-composer) – A puzzle game inspired by functional programming.
* [FP Youtube Search](https://github.com/jaysoo/example-fp-youtube-search) – YouTube search app with ReactJS, Redux, and FP concepts
* [Hardcore Functional Programming in JavaScript](https://frontendmasters.com/courses/functional-javascript/) – Learn to apply techniques from the forefront of computer science research to solve practical problems in Javascript. Discover functional programming and see it demonstrated step-by-step with how to build an example web app using abstract interfaces like Monads, Functors, Monoids and Applicatives. (_commercial_)

## Community

### Related Lists

* [Awesome FRP JS](https://github.com/stoeffel/awesome-frp-js) – A curated list of awesome (functional) reactive programming stuff in JavaScript.
* [lucasviola/Awesome Functional Programming](https://github.com/lucasviola/awesome-functional-programming) – Awesome resources on functional programming theory and learning materials.
* [xgrommx/Awesome Functional Programming](https://github.com/xgrommx/awesome-functional-programming) – A ton of articles on functional programming, as well as a huge list of functional libraries for many programming languages.
* [Functional Programming Resources In JavaScript](https://github.com/busypeoples/functional-programming-javascript)

### Talk

* [Functional Programming Slack channel](https://functionalprogramming.slack.com/) – Community with a friendly channel for JavaScript as well as many other channels about functional programming in general.

### People

* [Becky Conning](https://twitter.com/BeckyConning)
* [Bodil Stokke](https://twitter.com/bodil)
* [Buzz de Cafe](https://twitter.com/buzzdecafe)
* [Brian Lonsdorf](https://twitter.com/drboolean)
* [Brian McKenna](https://twitter.com/puffnfresh)
* [David Chambers](https://twitter.com/davidchambers)
* [Elise Huard](https://twitter.com/elise_huard)
* [Gleb Bahmutov](https://twitter.com/bahmutov)
* [John A. De Goes](https://twitter.com/jdegoes)
* [Joseph Abrahamson](https://twitter.com/sdbo)
* [Katie Ots](http://www.codemiller.com/)
* [Quildreen Motta](https://twitter.com/robotlolita)
* [Reginald Braithwaite](https://twitter.com/raganwald)
* [Scott Christopher](https://twitter.com/_schristo)
* [Scott Sauyet](https://twitter.com/scott_sauyet)
* [Simon Richardson](https://twitter.com/simonrichardson)

## Contribution

:star: Suggestions and PRs are welcome! :star:

Please read the [contribution guidelines](./contributing.md) to get started.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Christoph Hermann](http://stoeffel.github.io/) has waived all copyright and related or neighboring rights to this work.
