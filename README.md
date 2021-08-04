# Awesome Elm PLTD [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://github.com/elm/elm-lang.org/raw/master/static/assets/logos/elm.png" align="right" width="150">](https://elm-lang.org)

> Useful resources for programming language theory & development in Elm.

Elm is a statically typed, pure, functional programming language for creating Web applications. Why use Elm for PL development then? Maybe you're more familiar with Elm, or you want your language to be available anywhere JavaScript is, or maybe you don't want to learn about monads and burritos.

Whatever the reason, there are at least a few of us playing with PL development in Elm so why not have an awesome list to show off that work?

**Come join the `#language-implementation` channel on the [Elm slack](https://elmlang.herokuapp.com) for more discussion!**

## About This List

Over the last year or so I've noticed a number of projects and discussions pop up on the Elm slack and discourse around programming language development in Elm. Some are toy or learning projects, while others are more serious endeavours like [Stabel](https://fossils.stabel-lang.org/compiler/home) or [funkLang](https://github.com/funk-team/funkLang). The ephemeral nature of Slack chat means a lot of information gets lost over time and we traditionally haven't had a place to organise or consolodate that knowledge.

Hopefully this list can rectify that! **At the moment** this list is a largely uncurated collection of PL-related projects in Elm with the intention that we have a starting point for sharing, learning, and discussion. **In time**, this list will become more heavily curated to show off the best or most interesting examples of PL dev in Elm.

## Contents

- [Languages](#languages)
  - [Compilers](#compilers)
  - [Interpreters](#interpreters)
  - [Markup Languages](#markup-languages)
- [Packages](#packages)
  - [Parsing](#parsing)
  - [Code Generation](#code-generation)

## Languages

### Compilers

- [elm-in-elm](https://github.com/elm-in-elm/compiler/) - Elm compiler written in Elm
- [stabel](https://fossils.stabel-lang.org/compiler/home) - Stabel is a pure, concatenative and statically typed programming language.
- [ren](https://github.com/ren-lang/compiler/) - Cleaner, clearer JavaScript. A functional scripting language for the Web.
- [funkLang](https://github.com/funk-team/funkLang) - funkLang is a Visual FrontEnd Framework where you can design, develop and deploy complex web applications using both visual and code workflows.

### Interpreters

- [schelme](https://github.com/bburdette/schelme/) - A minimal scheme-esque language written in Elm.
- [elm-eexl](https://github.com/ccapndave/elm-eexl/) - Elm Expression Language: Simple context-based expression parser and evaluator.
- [microkanren](https://github.com/dvberkel/microkanren/) - An Elm implementation of the μKanren language.
- [lisa](https://github.com/chicode/lisa/) - A Lisp dialect designed for coding workshops
- [ulmus](https://github.com/uzimaru0000/ulmus/) - Ulmus is a Lisp implementation made with Elm.

### Markup Languages

- [elm-markup](https://github.com/mdgriffith/elm-markup/) - Elm Markup is a markup language that integrates closely with Elm.
- [L1](https://github.com/jxxcarlson/L1) - A toy language demo for a fault-tolerant parser.
- [CaYaTeX](https://github.com/jxxcarlson/cayatex) - CaYaTeX is an experimental markup language that compiles to LaTeX, Html, and (indirectly) PDF.

## Packages

### Parsing

- [elm/parser](https://github.com/elm/parser/) - A parsing library, focused on simplicity and great error messages.
- [dmy/elm-pratt-parser](https://github.com/dmy/elm-pratt-parser/) - Pratt / Top-Down Operator Precedence parsing for `elm/parser`.


### Code Generation

- [the-sett/elm-pretty-printer](https://github.com/the-sett/elm-pretty-printer/) - A pretty printing library based on 'A Prettier Printer' by Philip Wadler.
- [the-sett/salix](https://github.com/the-sett/salix/) - Salix is a data modelling language that is designed to support code generation across many different situations.
