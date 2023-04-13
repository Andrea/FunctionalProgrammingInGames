Functional Programming In Games
============================

Welcome to this page! Hope you find what you are looking for

I don't know you, but when I was learning how to do funcitonal programming I wanted to program fun things, or something other than a "website for your cat(tm)" so I was looking for FP in games and there wasn't much around at the time... so I created this list.


**Please note: this list is not complete. If you find something missing or incorrect, please send a PR or create an issue specifying the problem.**



Thanks

## Some resources for Functional Programming in Games Resources

## Books

* Haskell: [Game Programming in Haskell](https://leanpub.com/gameinhaskell)
* F#: [Friendly F#](http://www.amazon.com/Friendly-Fun-game-programming-Book-ebook/dp/B005HHYIWC) Not totally about games but all examples are game related
* Lisp: [Land of Lisp](http://landoflisp.com/)
* Racket: [Realm of Racket](http://realmofracket.com/)
* Rust:
    * [Learn game development in Rust](https://sunjay.dev/learn-game-dev/getting-started.html)
    * [Hands-on Rust- Effective Learning through 2D Game Development and Play](https://pragprog.com/titles/hwrust/hands-on-rust/)
    * [arewegameyet.rs](https://arewegameyet.rs/#resources) links to 5+ books, and there are also tutorials, videos, etc.

### Tutorials

* [F# game tutorial series with Monogame](http://bruinbrown.wordpress.com/f-game-tutorial-series/)
* [Arcadia - Clojure on Unity3d](https://github.com/arcadia-unity/Arcadia)
* [Building flappy bird from scratch with Arcadia at November Clojure NYC Meetup](https://www.youtube.com/watch?v=tBvNIJzlWEI)
* [Writing a 2048 clone in elm](http://scrambledeggsontoast.github.io/2014/05/09/writing-2048-elm/)
* [Caves of Clojure](http://stevelosh.com/blog/2012/07/caves-of-clojure-01/) a blog series on how to develop a Roguelike in Clojure. [Code](https://github.com/sjl/caves/).
* [Game development in Clojure (with play-clj)](https://www.youtube.com/watch?v=9ilUe7Re-RA)

### Videos

* [Building a platform game from the ground up with F# and MonoGame](https://www.youtube.com/playlist?list=PLIH3o_QrxxcfNMC3TjZ5NlHnB1AmcyaiV)
* [A reactive game stack: Using Erlang, Lua and Voltdb to enable a nonsharded game world](https://www.youtube.com/watch?v=BiBvOGP-GNg)
* [Writing a game in Haskell](https://www.youtube.com/watch?v=1MNTerD8IuI)
* [F# in Social Gaming](https://www.youtube.com/watch?v=ZMfqNfAGZHg)
* [My adventures with Elm](https://vimeo.com/113703868)
* [Morgan Mullaney - Well I Wouldn't Want To Make a *Dys*functional Game](http://www.meetup.com/FunctionalKats/events/221966876/)
* [Games and 3D Graphics in Arcadia](https://www.youtube.com/watch?v=zmmdYyAQhmM)
* [CodeMesh 2014 - Arcadia: Functional Video Game Development](https://www.youtube.com/watch?v=lHz5A19h9Z8)
* [Making Games at Runtime with Clojure (with play-clj)](https://www.youtube.com/watch?v=0GzzFeS5cMc)
* [RustConf 2018 - Closing Keynote - Using Rust For Game Development by Catherine West](https://www.youtube.com/watch?v=aKLntZcp27M)
* [Rust Linz, 2021 - Herbert Wolverson - Learning Rust with Game Development](https://www.youtube.com/watch?v=79GyLlXAk-0) - this video is by the author of [Hands-On Rust](https://pragprog.com/titles/hwrust/hands-on-rust/)

### Presentations

* [My adventure with Elm - Yan Cui](http://www.slideshare.net/theburningmonk/my-adventure-with-elm-46396046)

### Papers

* [Monadic Scripting in F# for Computer Games](http://www.dsi.unive.it/~orsini/documenti/MonadicScripting2.pdf)
* [A Formal Specification for Casanova,a Language for Computer Games](http://www.dsi.unive.it/~orsini/documenti/SpecificationCasanova.pdf)

### Libraries and engines

#### Haskell
* [HELM](https://hackage.haskell.org/package/helm) An FRP game engine inspired by Elm. 
* [FunGEn](http://joyful.com/fungen/) A BSD licensed, cross platform non FRP game engine written in Haskell.* 
* [Haskell game related libraries](http://hackage.haskell.org/packages/#cat:game)
* [LambdaHack](https://github.com/LambdaHack/LambdaHack) Haskell game engine library for roguelike dungeon crawlers.

#### F &#35;

* [Duality Scripting](https://github.com/BraveSirAndrew/DualityScripting) Allows you to write F# on the Duality Game Engine (the compiler is integrated into the editor so you can write code on any editor you want). This plugin supports C# too.
* [Nu Game Engine](https://github.com/bryanedds/FPWorks) cross-platform F# 2D game engine. It encourages to use as the architecture a variation of FRP which he calls Iterative Functional Reactive Programming.
* Unity 3D can be used with F#. There are multiple examples in the internet, for example [this one](https://github.com/Thorium/Roll-a-ball-FSharp).
* [Godot](https://godotengine.org/) can be scripted with F#. Setup guides for [Godot 3](https://hamy.xyz/labs/2022-11-godot-script-with-fsharp) and [Godot 4](https://hamy.xyz/labs/2023-04-godot-4-script-fsharp).

#### Clojure

* [play-clj](https://github.com/oakes/play-clj) A wrapper around [libGDX](http://libgdx.badlogicgames.com/). It supports pc, Android and iOS (through [RoboVM](http://robovm.com/)).
* [brute](https://github.com/markmandel/brute) An Entity Component System which supports both Clojure and ClojureScript. Some information on the thinking behind the implementation are on the author's [blog](http://www.compoundtheory.com/brute-entity-component-system-library-0-2-0-the-sequel/).
* [Arcadia](http://arcadia-unity.tumblr.com/) Clojure integrated into the Unity engine. It uses ClojureCLR. It has been used for interactive art installations and game jam games.

#### Scala

* [Indigo](https://indigoengine.io/): A Scala 3 / Scala.js 2D game engine built specifically for functional programmers.
* [SGL](https://github.com/regb/scala-game-library): Scala Game Library (SGL) is a library for developing cross-platform 2D video games in Scala. It provides a high-level API for building games, and can export games to the Desktop, Android, and the web. More platforms, including iOS and consoles, are on the roadmap.

#### Awesome Gamedev Repositories

* OCaml: [Awesome OCaml Gamedev](https://github.com/fccm/awesome-gamedev-ocaml)

#### Games

##### Shipped or in development commercial games made with FP languages
* [Onikira: Demon Killer](https://store.steampowered.com/app/310850/Onikira__Demon_Killer/) is a 2D side scrolling beat ‘em up set in a fantasy feudal Japan. It's on Steam (tho unsupported), parts of it written in F#.
* [Wayward Tide](http://blog.chucklefish.org/set-sail-for-wayward-tide/) A game in development, targeting pc and written in Haskell
* [Magic Cookies](http://keera.co.uk/blog/2015/03/19/magic-cookies-released-google-play/) Published on [iTunes](https://itunes.apple.com/us/app/magic-cookies/id1244709871) and [Google Play for Android](https://play.google.com/store/apps/details?id=uk.co.keera.games.magiccookies), it's written in Haskell.
* [Nikki and the Robots](https://github.com/nikki-and-the-robots/nikki) is a 2-dimensional platform game written in Haskell, now open source. It's published on Steam.
* [Asteroid Sharpshooter] published on Xbox Live Indie Games, written in F#. [Slides on the development process](https://docs.google.com/presentation/d/1teGhBf-m7qRkMzsbCKvRcIEo-QLwdK9w8VOEWqu1qWQ/edit#slide=id.p). His [blog](http://sharp-gamedev.blogspot.co.uk/2011/03/asteroid-sharpshooter-post-mortem.html) has more information on how he made [F# work with XNA on Xbox 360](http://sharp-gamedev.blogspot.co.uk/search/label/xna).

##### Open source

* Game jam games
    * [An Evening of Modern Dance](http://ludumdare.com/compo/ludum-dare-32/?action=preview&uid=1066) made with Arcadia (Clojure) for Ludum Dare 32. Source available.
    * [Elm Flyer](http://jcollard.github.io/elm-flyer/) made with Elm. [Source](https://github.com/jcollard/elm-flyer-2014).
    * [Castle of Elm](http://www.castleofelm.com/) 7DRL game made in Elm. [Source](https://github.com/doppioslash/CastleOfElm), [slides](http://slides.com/doppioslash/the-elm-language-livjavascriptug) on Elm and developing a game jam game with it.

* More open source games, by language
    * Haskell
        * [Haskanoid](https://github.com/ivanperez-keera/haskanoid) A breakout game in Haskell using SDL and FRP, with Wiimote and Kinect support. [Available on Google Play](https://play.google.com/store/apps/details?id=uk.co.keera.games.breakout.beta).
        * [Allure of the Stars](https://github.com/AllureOfTheStars/Allure) is a near-future Sci-Fi roguelike and tactical squad game written in Haskell. 
        * [Nikki and the Robots](https://github.com/nikki-and-the-robots/nikki) commercial game written in Haskell, now open source.

* **Meta - games that teach functional programming concepts in-game**
    * [cube-composer](https://github.com/sharkdp/cube-composer)
        * "A puzzle game inspired by functional programming, written in [PureScript](https://github.com/purescript/purescript)."
    * [lambda-lantern](https://github.com/lettier/lambda-lantern)
        * You collect functional programming patterns and use them to solve puzzles and escape a dungeon.
        * "Lambda Lantern is a game made with PureScript, PureScript Native, and Panda3D." ("One of the purposes of Lambda Lantern is to demonstrate binding PureScript to C++.")
    * **[functional](https://store.steampowered.com/app/1636730/functional/)** - on [Steam]((https://store.steampowered.com/app/1636730/functional/)) and [open source](https://github.com/yancouto/functional), implemented in Rust
        * **"functional is a puzzle game about math and abstraction."**
