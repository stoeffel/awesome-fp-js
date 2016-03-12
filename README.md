# Awesome FP JS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome functional programming stuff in JavaScript

Inspired by the [Awesome](https://github.com/sindresorhus/awesome) list thing.

## Libraries

* [Ramda](https://github.com/ramda/ramda) - A practical functional library for JavaScript that is designed specifically for a functional programming style, one that makes it easy to create functional pipelines, one that never mutates user data.
* [Folktale](http://folktalejs.org/) - Folktale is a suite of libraries for generic functional programming that allows you to write elegant modular applications with fewer bugs, and more reuse.
* [lodash/fp](https://github.com/lodash/lodash/wiki/FP-Guide) - An instance of [Lodash](https://github.com/lodash/lodash) with its methods wrapped to produce immutable auto-curried iteratee-first data-last methods.
* [functional.js](http://functionaljs.com) - A lightweight functional JavaScript library that facilitates currying and point-free / tacit programming.
* [101](https://github.com/tjmehta/101) - A modern and modular JavaScript utility library made to work well with vanilla JavaScript methods.
* [fnuc](https://github.com/algesten/fnuc) - A functional library for CoffeeScript (and JavaScript) to facilitate functional composition and higher order functions.
* [barely-functional](https://github.com/cullophid/barely-functional) - A tiny (2.7kb) functional programming library using native ES5/6 operations.
* [prelude.ls](http://gkz.github.io/prelude-ls/) - A functionally oriented utility library somewhat based off of Haskell's Prelude module.
* [allong.es](http://allong.es/) - A collection of functions to facilitate writing JavaScript with functions as first-class values, designed to complement libraries like Underscore, not compete with them.
* [1-liners](https://github.com/1-liners/1-liners) - Functional tools that couldn’t be simpler. A dead simple functional utility belt, hand-crafted with love and attention.
* [fn-curry](https://github.com/wilhelmson/fn-curry) - A simple function to curry a function.
* [curry](https://github.com/thisables/curry) - Curry your functions using function bind syntax.
* [compose-function](https://github.com/stoeffel/compose-function) - Compose a new function from smaller functions.
* [functionize](https://github.com/paldepind/functionize) - A collection of functions which aid in making non-functional libraries functional.
* [lambdajs](https://github.com/loop-recur/lambdajs) - The full ECMAScript API done a functional way.
* [fp-dom](https://github.com/fp-dom/) - Making the DOM functional.
* [trifl](https://github.com/algesten/trifl) - A functional user interface library with unidirectional dataflow and a virtual dom.
* [funcy](https://github.com/bramstein/funcy) - An experiment in adding functional pattern matching to JavaScript. _Experimental_  :triangular_flag_on_post:
* [date-fp](http://github.com/cullophid/date-fp) - A functional utility library for working with JavaScript dates. All functions in date-fp are pure, autocurried and will not mutate the date objects they are applied to.
* [claire](https://github.com/robotlolita/claire) – A property-based testing library for clearly specifying code invariants and behaviour.
* [\_part\_](https://github.com/AutoSponge/_part_) - A micro library that encourages functional programming by making native methods available as partially applied functions.
* [fantasy-combinators](https://github.com/fantasyland/fantasy-combinators) – Common combinators.
* [fantasy-birds](https://github.com/fantasyland/fantasy-birds) – Port of the Haskell package Data.Aviary.Birds. Everything for your combinatory needs.

### Data Structures

Write performant functional code by using data structures that are suited for this task.

* [Immutable.js](https://github.com/facebook/immutable-js) - Immutable persistent data collections.
* [Mori](https://github.com/swannodette/mori) - ClojureScript’s persistent data structures and supporting API from the comfort of vanilla JavaScript.
* [immutable-sequence.js](https://github.com/qiao/immutable-sequence.js) –  High performance implementation of Immutable Sequence in JavaScript, based on [Finger Trees](https://github.com/qiao/fingertree.js).
* [Timm](http://guigrpa.github.io/timm/) – Immutability helpers with fast reads and acceptable writes.
* [Lazy.js](https://github.com/dtao/lazy.js) – A utility library with a lazy engine under the hood that strives to do as little work as possible while being as flexible as possible.

### Algebraic Data Types

Types formed by composing other types.

* [FantasyLand](https://github.com/fantasyland/fantasy-land) - :rainbow: Not a library but a specification of the Monad laws for libraries to follow.
* [daggy](https://github.com/puffnfresh/daggy) - Library for creating tagged constructors.
* [Sanctuary](https://github.com/plaid/sanctuary) - Sanctuary makes it possible to write safe code without null checks.
* [ramda-fantasy](https://github.com/ramda/ramda-fantasy) – Fantasy-Land compatible types for easy integration with Ramda.js.
* [monet.js](http://cwmyers.github.io/monet.js/) - A library that assists functional programming by providing a rich set of Monads and other useful functions.
* [union-type](https://github.com/paldepind/union-type) – A small JavaScript library for defining and using union types.
* [freeky](https://github.com/DrBoolean/freeky) – A collection of Free monads.

### Lenses
* [lenses](https://github.com/DrBoolean/lenses) - Composable kmett style lenses
* [optics](https://github.com/flunc/optics) - profunctor optics (Lens, Prism, iso)
* [ramda-lens](https://github.com/ramda/ramda-lens) - :ram: :mag_right: Lens library built on ramda
* [fantasy-lenses](https://github.com/fantasyland/fantasy-lenses) - Composable, immutable getters and setters. (profunctor lenses WIP)
* [nanoscope](https://github.com/5outh/nanoscope) - Lenses with dotty support

## Books

* [JavaScript Allongé](https://leanpub.com/javascriptallongesix), the “Six” edition by [Reg  Braithwaite](https://github.com/raganwald) (2016)
* [Functional Programming in JavaScript](https://www.manning.com/books/functional-programming-in-javascript) by Luis Atencio (2016)
* [Eloquent JavaScript](http://eloquentjavascript.net/) by Marijn Haverbeke (2014)
* [Functional JavaScript](http://shop.oreilly.com/product/0636920028857.do) by [Michael Fogus](https://github.com/fogus) (2013)

## Functional Languages that Compile to JavaScript

* [ClojureScript](https://github.com/clojure/clojurescript) - compiles Clojure, a hosted Lisp with immutable persistent data structures, to JavaScript
* [Elm](http://elm-lang.org/) - type-safe functional programming language for declaratively creating web browser-based graphical user interfaces, implemented in Haskell
* [PureScript](http://www.purescript.org/) - a small strongly typed programming language that compiles to JavaScript
* [ElixirScript](https://github.com/bryanjos/elixirscript)
* [Idris](http://www.idris-lang.org/) - A general purpose pure functional programming language with dependent types.
* [Scala.js](http://www.scala-js.org/)
* [Js\_of\_ocaml](http://ocsigen.org/js_of_ocaml/)
* [GHCJS](https://github.com/ghcjs/ghcjs)
* [LiveScript](http://gkz.github.io/LiveScript/) - LiveScript has a straightforward mapping to JavaScript and allows you to write expressive code devoid of repetitive boilerplate.

## Resources

* [Classroom Coding Pt1](https://www.youtube.com/watch?v=h_tkIpwbsxY) - Classroom Coding with Prof. Frisby Pt1
* [Classroom Coding Pt2](https://www.youtube.com/watch?v=oZ6C9h49bu8) - Classroom Coding with Prof. Frisby Pt2
* [Classroom Coding Pt3](https://www.youtube.com/watch?v=mMCgJA8HScA) - Classroom Coding with Prof. Frisby Pt3
* [Hey Underscore, You're Doing It Wrong!](https://www.youtube.com/watch?v=m3svKOdZijA) - Underscore.js claims to be a functional programming language, but how true is that?
* [Functional programming patterns for the non-mathematician](https://www.youtube.com/watch?v=AvgwKjTPMmM)
* [Pure JavaScript](https://vimeo.com/49384334)
* [Pure, functional JavaScript](https://vimeo.com/43382919)
* [functional-javascript-workshop](https://github.com/timoxley/functional-javascript-workshop) - Teaching fundamental functional programming features of JavaScript
* [mostly-adequate-guide](https://github.com/DrBoolean/mostly-adequate-guide) - Mostly adequate guide to FP (in JavaScript)
* [functional-frontend-architecture](https://github.com/paldepind/functional-frontend-architecture) - A functional frontend framework. Based on Ramda + union-type-js + Flyd + Snabbdom
* [cube-composer](https://github.com/sharkdp/cube-composer) - A puzzle game inspired by functional programming.
* [Functional Programming Jargon](https://github.com/hemanth/functional-programming-jargon) - Jargon from the functional programming world explained in JavaScript.
* [FPJS-Class](https://github.com/loop-recur/FPJS-Class) - Functional Programming learned through JS
* [FP Concepts in JavaScript](https://medium.com/@collardeau/intro-to-functional-programming-concepts-in-javascript-b0650773139c) - An Intro to Functional Programming Concepts in JavaScript
* [Hardcore Functional Programming in JavaScript](https://frontendmasters.com/courses/functional-javascript/) - Learn to apply techniques from the forefront of computer science research to solve practical problems in Javascript. Discover functional programming and see it demonstrated step-by-step with how to build an example web app using abstract interfaces like Monads, Functors, Monoids and Applicatives. (_commercial_)
* [The Two Pillars of JavaScript Pt 2: Functional Programming](https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4#.pjv8bau0g)
* [Functional programming with JavaScript](http://stephen-young.me.uk/2013/01/20/functional-programming-with-javascript.html)
* [Why Curry Helps](https://hughfdjackson.com/javascript/why-curry-helps/)
* [JavaScript and Type Thinking](https://medium.com/@yelouafi/javascript-and-type-thinking-735edddc388d#.ugioiqp2a)
* [Lazy, composable, and modular JavaScript](https://codewords.recurse.com/issues/four/lazy-composable-and-modular-javascript)
* [Why Ramda](http://fr.umio.us/why-ramda/)
* [Favoring Curry](http://fr.umio.us/favoring-curry/)
* [A Monad in Practicality: First-Class Failures](http://robotlolita.me/2013/12/08/a-monad-in-practicality-first-class-failures.html)
* [A Monad in Practicality: Controlling Time](http://robotlolita.me/2014/03/20/a-monad-in-practicality-controlling-time.html)
* [FP Youtube Search](https://github.com/jaysoo/example-fp-youtube-search) - YouTube search app with ReactJS, Redux, and FP concepts
* [A gentle introduction to functional JavaScript](jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-intro/) – A four-part series introduction functional programming in JavaScript.
* [Functional programming](https://glebbahmutov.com/blog/tags/functional/) – Many articles on various aspects of functional programming in JavaScript by Gleb Bahmutov.

## Related Lists

* [Awesome FRP JS](https://github.com/stoeffel/awesome-frp-js) - A curated list of awesome (functional) reactive programming stuff in JavaScript.
* [Awesome Functional Programming](https://github.com/lucasviola/awesome-functional-programming) - Awesome resources on functional programming theory and learning materials.
* [Functional Programming Resources In JavaScript](https://github.com/busypeoples/functional-programming-javascript)

## People

* [Becky Conning](https://twitter.com/BeckyConning)
* [Bodil Stokke](https://twitter.com/bodil)
* [Buzz de Cafe](https://twitter.com/buzzdecafe)
* [Brian Lonsdorf](https://twitter.com/drboolean)
* [Brian McKenna](https://twitter.com/puffnfresh)
* [Elise Huard](https://twitter.com/elise_huard)
* [Gleb Bahmutov](https://twitter.com/bahmutov)
* [John A. De Goes](https://twitter.com/jdegoes)
* [Joseph Abrahamson](https://twitter.com/sdbo)
* [Katie Ots](http://www.codemiller.com/)
* [Quildreen Motta](https://twitter.com/robotlolita)
* [Reginald Braithwaite](https://twitter.com/raganwald)
* [Scott Sauyet](https://twitter.com/scott_sauyet)
* [Simon Richardson](https://twitter.com/simonrichardson)

## Contribution

:star: Suggestions and PRs are welcome! :star:

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Christoph Hermann](http://stoeffel.github.io/) has waived all copyright and related or neighboring rights to this work.
