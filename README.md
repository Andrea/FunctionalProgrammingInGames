Functional Programming In Games
============================

## Some resources for Functional Programming in Games Resources

## Books

* [Game Programming in Haskell](https://leanpub.com/gameinhaskell)
* [Friendly F#](http://www.amazon.com/Friendly-Fun-game-programming-Book-ebook/dp/B005HHYIWC) Not totally about games but all examples are game related
* [Land of Lisp](http://landoflisp.com/)
* [Realm of Racket](http://realmofracket.com/)

### Tutorials


* [F# game tutorial series with Monogame](http://bruinbrown.wordpress.com/f-game-tutorial-series/)
* [Arcadia - Clojure on Unity3d](https://github.com/arcadia-unity/Arcadia)
* [Building flappy bird from scratch with Arcadia at November Clojure NYC Meetup](https://www.youtube.com/watch?v=tBvNIJzlWEI)
* [Writing a 2048 clone in elm](http://scrambledeggsontoast.github.io/2014/05/09/writing-2048-elm/)
* [Caves of Clojure](http://stevelosh.com/blog/2012/07/caves-of-clojure-01/) a blog series on how to develop a Roguelike in Clojure. [Code](https://github.com/sjl/caves/).
* [Game development in Clojure (with play-clj)](https://www.youtube.com/watch?v=9ilUe7Re-RA)

### Videos

* [A reactive game stack: Using Erlang, Lua and Voltdb to enable a nonsharded game world](https://www.youtube.com/watch?v=BiBvOGP-GNg)
* [Writing a game in Haskell](https://www.youtube.com/watch?v=1MNTerD8IuI)
* [F# in Social Gaming](https://www.youtube.com/watch?v=ZMfqNfAGZHg)
* [My adventures with Elm](https://vimeo.com/113703868)
* [Morgan Mullaney - Well I Wouldn't Want To Make a *Dys*functional Game](http://www.meetup.com/FunctionalKats/events/221966876/)
* [Games and 3D Graphics in Arcadia](https://www.youtube.com/watch?v=zmmdYyAQhmM)
* [CodeMesh 2014 - Arcadia: Functional Video Game Development](https://www.youtube.com/watch?v=lHz5A19h9Z8)
* [Making Games at Runtime with Clojure (with play-clj)](https://www.youtube.com/watch?v=0GzzFeS5cMc)

### Presentations

* [My adventure with Elm](http://www.slideshare.net/theburningmonk/my-adventure-with-elm-46396046)

### Papers

* [Monadic Scripting in F# for Computer Games](http://www.dsi.unive.it/~orsini/documenti/MonadicScripting2.pdf)
* [A Formal Specification for Casanova,a Language for Computer Games](http://www.dsi.unive.it/~orsini/documenti/SpecificationCasanova.pdf)

### Libraries and engines

#### Haskell
* [HELM](http://helm-engine.org/) An FRP game engine inspired by Elm. 
* [FunGEn](http://joyful.com/fungen/) A BSD licensed, cross platform non FRP game engine written in Haskell.* 
* [Haskell game related libraries](http://hackage.haskell.org/packages/#cat:game)
* [LambdaHack](https://github.com/LambdaHack/LambdaHack) Haskell game engine library for roguelike dungeon crawlers.

#### F &#35;

* [Duality Scripting](https://github.com/BraveSirAndrew/DualityScripting) Allows you to write F# on the Duality Game Engine (the compiler is integrated into the editor so you can write code on any editor you want). This plugin supports C# too.
* [Nu Game Engine](https://github.com/bryanedds/FPWorks) cross-platform F# 2D game engine. It encourages to use as the architecture a variation of FRP which he calls Iterative Functional Reactive Programming.

#### Clojure

* [play-clj](https://github.com/oakes/play-clj) A wrapper around [libGDX](http://libgdx.badlogicgames.com/). It supports pc, Android and iOS (through [RoboVM](http://robovm.com/)).
* [brute](https://github.com/markmandel/brute) An Entity Component System which supports both Clojure and ClojureScript. Some information on the thinking behind the implementation are on the author's [blog](http://www.compoundtheory.com/brute-entity-component-system-library-0-2-0-the-sequel/).
* [Arcadia](http://arcadia-unity.tumblr.com/) Clojure integrated into the Unity engine. It uses ClojureCLR. It has been used for interactive art installations and game jam games.

#### Shipped or in development commercial games made with FP languages
* [Onikira: Demon Killer](http://www.digitalfurnacegames.com/) is a 2D side scrolling beat ‘em up set in a fantasy feudal Japan. It's on Steam Early Access, written in F#.
* [Wayward Tide](http://blog.chucklefish.org/set-sail-for-wayward-tide/) A game in development, targeting pc and written in Haskell
* [Magic Cookies](http://keera.co.uk/blog/2015/03/19/magic-cookies-released-google-play/) Published on [iTunes](https://itunes.apple.com/us/app/magic-cookies/id1244709871) and [Google Play for Android](https://play.google.com/store/apps/details?id=uk.co.keera.games.magiccookies), it's written in Haskell.
* [Nikki and the Robots](https://github.com/nikki-and-the-robots/nikki) is a 2-dimensional platform game written in Haskell, now open source. It's published on Steam.
* [Asteroid Sharpshooter](http://marketplace.xbox.com/en-US/Product/Asteroid-Sharpshooter/66acd000-77fe-1000-9115-d80258550797) published on Xbox Live Indie Games, written in F#. [Slides on the development process](https://docs.google.com/presentation/d/1teGhBf-m7qRkMzsbCKvRcIEo-QLwdK9w8VOEWqu1qWQ/edit#slide=id.p). His [blog](http://sharp-gamedev.blogspot.co.uk/2011/03/asteroid-sharpshooter-post-mortem.html) has more information on how he made [F# work with XNA on Xbox 360](http://sharp-gamedev.blogspot.co.uk/search/label/xna).

#### Open Source Games
* [Haskanoid](https://github.com/ivanperez-keera/haskanoid) A breakout game in Haskell using SDL and FRP, with Wiimote and Kinect support. [Available on Google Play](https://play.google.com/store/apps/details?id=uk.co.keera.games.breakout.beta).
* [Allure of the Stars](https://github.com/AllureOfTheStars/Allure) is a near-future Sci-Fi roguelike and tactical squad game written in Haskell. 
* [Nikki and the Robots](https://github.com/nikki-and-the-robots/nikki) commercial game written in Haskell, now open source.

#### Game jam games
* [An Evening of Modern Dance](http://ludumdare.com/compo/ludum-dare-32/?action=preview&uid=1066) made with Arcadia (Clojure) for Ludum Dare 32. Source available.
* [Elm Flyer](http://jcollard.github.io/elm-flyer/) made with Elm. [Source](https://github.com/jcollard/elm-flyer-2014).
* [Castle of Elm](http://www.castleofelm.com/) 7DRL game made in Elm. [Source](https://github.com/doppioslash/CastleOfElm), [slides](http://slides.com/doppioslash/the-elm-language-livjavascriptug) on Elm and developing a game jam game with it.

##Note
Actually, I'm thinking that logic programming resources could also live here, perhaps we need to rename this? 
