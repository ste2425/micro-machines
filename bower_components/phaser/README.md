![div](http://www.phaser.io/images/github/welcome-div2.png)

# Phaser

<img src="http://phaser.io/images/github/jump.jpg" align="right">

Phaser is a fast, free and fun open source HTML5 game framework. It uses [Pixi.js](https://github.com/GoodBoyDigital/pixi.js/) for WebGL and Canvas rendering across desktop and mobile web browsers. Games can be compiled to iOS and Android apps via 3rd party tools.

Along with the fantastic open source community Phaser is actively developed and maintained by [Photon Storm Limited](http://www.photonstorm.com). As a result of rapid support and a developer friendly API Phaser is currently one of the [most starred](https://github.com/showcases/javascript-game-engines) game frameworks on Github.

Thousands of developers worldwide use it. From indies and multi-national digital agencies to schools and Universities. Each creating their own incredible games. Grab the source and join in the fun!

* **Visit:** The [Phaser website](http://phaser.io) and follow on [Twitter](https://twitter.com/photonstorm) (#phaserjs)
* **Learn:** [API Documentation](http://phaser.io/docs), [Support Forum][forum] and [StackOverflow](http://stackoverflow.com/questions/tagged/phaser-framework)
* **Code:** 550+ [Source Examples](http://phaser.io/examples) (also available in this [git repo][examples])
* **Read:** Subscribe to the [Newsletter](https://confirmsubscription.com/h/r/369DE48E3E86AF1E) and grab our [Phaser Books](http://phaser.io/shop)
* **Chat:** [#phaserio IRC channel](http://www.html5gamedevs.com/topic/4470-official-phaserio-irc-channel-phaserio-on-freenode/) on freenode
* **Extend:** With [Phaser Plugins](https://github.com/photonstorm/phaser-plugins)
* **Be awesome:** Support the future of Phaser on [Patreon](https://www.patreon.com/photonstorm) or by buying our [books](http://phaser.io/shop/books) and [plugins](http://phaser.io/shop/plugins)

![div](http://www.phaser.io/images/github/div.png)

## Index

- [What's New?](#whats-new)
- [Support Phaser](#patreon)
- [Download Phaser](#download)
- [Getting Started](#getting-started)
- [Using Phaser](#using-phaser)
- [Games made with Phaser](#games)
- [Requirements](#requirements)
- [Road Map](#road-map)
- [Change Log](#change-log)
- [Contributing](#contributing)

![div](http://www.phaser.io/images/github/div.png)

<a name="whats-new"></a>
## What's new in Phaser 2.4.3

<div align="center"><img src="http://phaser.io/images/github/news.jpg"></div>

> 24th August 2015

The release of Phaser 2.4.3 continues our work with bug fixes, new features and continued optimizations. As before it's a point-release, making it a safe upgrade for anyone using a previous 2.4 build.

As well as working on this release we've also been busily writing tutorials for the first issue of [Interphase](http://phaser.io/interphase/), our new publication for Phaser developers. Packed full of exclusive content we've been coding games, writing tutorials and authoring deep-dive articles for the first issue. It's been a blast so far and I'm excited for it's release in early September - and if you [pre-order now](http://phaser.io/interphase) with the discount code 'earlybird' you can save 15% on the cover price.

Finally we'd be extremely grateful if you could get involved with our [Phaser Patreon campaign](https://www.patreon.com/photonstorm). The uptake so far has been fantastic. Thank you to everyone who now supports Phaser development and shares our belief in the future of HTML5 gaming and Phasers role in that.

Happy coding everyone! See you on the forums.

Cheers,

Rich - [@photonstorm](https://twitter.com/photonstorm)

![boogie](http://www.phaser.io/images/spacedancer.gif)

![div](http://www.phaser.io/images/github/div.png)

<a name="patreon"></a>
## Support Phaser on Patreon

![patreon](http://www.phaser.io/images/patreon.png)

Please help support the future development of Phaser through our [Patreon campaign](https://www.patreon.com/photonstorm). We've some exciting plans and there's so much we'd like to do. Let's see if we can all work together to make this possible.

### Phaser Sponsors

Phaser is [sponsored](https://www.patreon.com/photonstorm) by the following great companies:

![qici](http://www.phaser.io/images/sponsors/qici-100.png)

QICI Engine: [A powerful one-stop integrated Phaser game editor](http://www.qiciengine.com/)

![zenva](http://www.phaser.io/images/sponsors/zenva-100.png)

Zenva Academy: [Online courses on Phaser, HTML5 and native app development](https://academy.zenva.com/?zva_src=phaserpatreon)

<a name="download"></a>
## Download Phaser

Phaser is [hosted on Github][phaser]. There are a number of ways to download it:

* Clone the git repository via [https][clone-http], [ssh][clone-ssh] or with the Github [Windows][clone-ghwin] or [Mac][clone-ghmac] clients.
* Download as [zip][get-zip] or [tar.gz][get-tgz]
* Download just the build files: [phaser.js][get-js] and [phaser.min.js][get-minjs]
* Checkout with [svn][clone-svn]

### Bower / npm

Install via [bower](http://bower.io)

`bower install phaser`

Install via [npm](https://www.npmjs.com)

`npm install phaser`

### CDN

[jsDelivr](http://www.jsdelivr.com/#!phaser) is a "super-fast CDN for developers". Include the following in your html:

`<script src="//cdn.jsdelivr.net/phaser/2.4.3/phaser.js"></script>`

or the minified version:

`<script src="//cdn.jsdelivr.net/phaser/2.4.3/phaser.min.js"></script>`

[cdnjs.com](https://cdnjs.com/libraries/phaser) also offers a free CDN service. They have all versions of Phaser and even the custom builds:

`<script src="https://cdnjs.cloudflare.com/ajax/libs/phaser/2.4.3/phaser.js"></script>`

### Phaser Sandbox

If you'd like to try coding in Phaser right now, with nothing more than your web browser then you can head over to the [Phaser Sandbox](http://phaser.io/sandbox). You'll find Quick Start templates and a user-friendly editor filled with handy code-completion features.

### Koding

Want to try Phaser without downloading anything? The site [Koding](https://koding.com) offer a complete browser-based virtual machine to work in, allowing you to clone the Phaser repo and start work immediately.

### License

Phaser is released under the [MIT License](http://opensource.org/licenses/MIT).

![div](http://www.phaser.io/images/github/div.png)

<a name="getting-started"></a>
## Getting Started

<img src="http://phaser.io/images/github/learn.jpg" align="right">

We have a [Getting Started Guide](http://phaser.io/tutorials/getting-started) which covers all you need to begin developing games with Phaser. From setting up a web server, to picking an IDE and coding your first game.

Prefer **videos** to reading? Lynda.com have published a free course: [HTML5 Game Development with Phaser](http://www.lynda.com/Phaser-tutorials/HTML5-Game-Development-Phaser/163641-2.html)

The single biggest Phaser resource is the new [Phaser web site](http://phaser.io/news). It has hundreds of tutorials listed and fresh ones are added every week, so keep coming back to see what's new!

Using Phaser with **TypeScript**? Check out this great series of [Game From Scratch](http://www.gamefromscratch.com/page/Adventures-in-Phaser-with-TypeScript-tutorial-series.aspx) tutorials.

### Source Code Examples

Ever since we started Phaser we've been growing and expanding our extensive set of source code examples. Currently there are over 500 of them!

Browse the [Phaser Examples](http://phaser.io/examples) or clone the [examples repo][examples] and eat your heart out!

### Phaser Books

<div align="center"><img src="http://phaser.io/images/github/books.jpg"></div>

We've been busy writing books about Phaser. Available now:

* [A Guide to the Phaser Tween Manager](https://leanpub.com/phasertweenmanager) Book + Code Bundle
* [A Guide to the Phaser Scale Manager](https://leanpub.com/phaserscalemanager)

With more on the way. [Vote on the next title](http://www.html5gamedevs.com/topic/10962-which-phaser-book-would-you-like-to-see-next/) to be written.

### Game Mechanic Explorer

The [Game Mechanic Explorer](http://gamemechanicexplorer.com) is a great interactive way to learn how to develop specific game mechanics in Phaser. Well worth exploring once you've got your dev environment set-up.

### Mighty Editor - Visual Game Editor

[MightyEditor](http://mightyfingers.com/) is a browser-based visual Phaser game editor. Create your maps with ease, position objects and share them in seconds. It also exports to native Phaser code. Excellent for quickly setting-up levels and scenes.

![div](http://www.phaser.io/images/github/div.png)

<a name="using-phaser"></a>
## Using Phaser

Phaser is provided ready compiled in the `build` folder of the repository. There are both plain and minified versions. The plain version is for use during development and the minified version for production.

### Custom Builds

Starting from Phaser 2.3.0 we now include a brand new build system which allows you to strip out lots of additional features you may not require, saving hundreds of KB in the process. Don't use any Sound in your game? Then you can now exclude the entire sound system. Don't need Keyboard support? That can be stripped out too.

As a result of this work the minimum build size of Phaser is now just 80KB minified and gzipped.

See the [Creating a Custom Phaser Build](http://phaser.io/tutorials/creating-custom-phaser-builds) tutorial for details.

### Building from source

Should you wish to build Phaser from source you can take advantage of the provided [Grunt](http://gruntjs.com/) scripts. Ensure you have the required packages by running `npm install` first.

Run `grunt` to perform a default build to the `dist` folder.

![div](http://www.phaser.io/images/github/div.png)

<a name="games"></a>
## Games made with Phaser

Thousands of games have been made in Phaser. From game jam entries to titles by some of the largest entertainment brands in the world. Here is a tiny sample:

[![Game](http://phaser.io/images/github/241/bubble-academy.png)][game10]
[![Game](http://phaser.io/images/github/241/woodventure.png)][game11]
[![Game](http://phaser.io/images/github/241/hopsop.png)][game12]
[![Game](http://phaser.io/images/github/241/banana-mania.png)][game13]
[![Game](http://phaser.io/images/github/241/salazar.png)][game14]
[![Game](http://phaser.io/images/github/241/phaser-shmup.png)][game15]
[![Game](http://phaser.io/images/github/241/trappy-trap.png)][game16]
[![Game](http://phaser.io/images/github/241/runaway-ruins.png)][game17]
[![Game](http://phaser.io/images/github/241/ananias.png)][game18]
[![Game](http://phaser.io/images/github/shot1a.jpg)][game1]
[![Game](http://phaser.io/images/github/shot2a.jpg)][game2]
[![Game](http://phaser.io/images/github/shot3a.jpg)][game3]
[![Game](http://phaser.io/images/github/shot4a.jpg)][game4]
[![Game](http://phaser.io/images/github/shot5b.jpg)][game5]
[![Game](http://phaser.io/images/github/shot6b.jpg)][game6]
[![Game](http://phaser.io/images/github/shot7b.jpg)][game7]
[![Game](http://phaser.io/images/github/shot8.jpg)][game8]
[![Game](http://phaser.io/images/github/shot9.jpg)][game9]

Artwork copyright their respective owners.

We add [new games](http://phaser.io/news/category/game) to the Phaser site weekly, so be sure to send us yours when it's finished!

![div](http://www.phaser.io/images/github/div.png)

<a name="requirements"></a>
## Requirements

Phaser requires a web browser that supports the [canvas tag](http://caniuse.com/#feat=canvas). This includes Internet Explorer 9+, Firefox, Chrome, Safari and Opera on desktop. iOS Safari, Android Browser and Chrome for Android are supported on mobile.

While Phaser does its best to ensure a consistent cross-platform experience always be aware of browser and device limitations. This is especially important with regard to memory and GPU limitations on mobile, and legacy browser HTML5 compatibility.

### IE9

If you need to support IE9 / Android 2.x **and** use P2 physics then you must use the polyfill in the `resources/IE9 Polyfill` folder. If you don't use P2 (or don't care about IE9!) you can skip this.

### JavaScript and TypeScript

Phaser is developed in JavaScript. We've made no assumptions about how you like to code and were careful not to impose a strict structure upon you. You won't find Phaser split into modules, requiring a build step, or making you use a class / inheritance OOP approach. That doesn't mean you can't do so, it just means we don't *force* you to. It's your choice.

If you code with [TypeScript](http://www.typescriptlang.org/) there are comprehensive definition files in the `typescript` folder. They are for TypeScript 1.4+.

![div](http://www.phaser.io/images/github/div.png)

<a name="road-map"></a>
## Road Map

All Phaser development is now taking place on the Phaser 3 project. The Phaser 2 branch will still be supported and issues fixed, but roadmap features have been migrated over to Phaser 3.

<a name="phaser3"></a>
## Phaser 3

We're now a good way in to development of Phaser 3. We've been working hard on creating a brand new and extremely powerful renderer. Progress reports are posted to the [web site](http://phaser.io/labs) and [Phaser 3 repo](https://github.com/photonstorm/phaser3).

There is still plenty of time to add your suggestions and feedback in [this forum thread](http://www.html5gamedevs.com/topic/7949-the-phaser-3-wishlist-thread/).

If you are an exceptional JavaScript developer and would like to join the Phaser 3 development team then let us know. We have a limited budget available to pay towards your time.

![div](http://www.phaser.io/images/github/div.png)

<a name="change-log"></a>
## Change Log

## Version 2.4.3 - "Coramen" - 24th August 2014

### New Features

* Loader.images is a new method that allows you to pass an array of image keys, and optionally the URLs to the Loader and have them all added to the load queue in one go.
* TweenManager.frameBased allows you to control if all newly created Tweens update based on the physics step (i.e. frame based) or the system clock (time based). A frame based tween will use the physics elapsed timer when updating. This means it will retain the same consistent frame rate, regardless of the speed of the device. The duration value given should be given in frames. If the Tween uses a time based update (which is the default) then the duration is given in milliseconds. In this situation a 2000ms tween will last exactly 2 seconds, regardless of the device and how many visual updates the tween has actually been through.
* Tween.frameBased does the same as TweenManager.frameBased but allows you to set the value on a per-tween basis.
* BitmapText.smoothed is a new boolean property that allows you to set texture smoothing on a bitmap font or not. By default smoothing is always on, but you can turn it off which helps for bitmap fonts created from pixel art style character sets.
* Text.addFontStyle and Text.addFontWeight allow you to apply font weights and styles to specific characters in a Text object. For example you can now include bold or italics within single Text objects (thanks @jdnichollsc #1950)
* PIXI.CanvasPool is a new static global created to deal with the issue of resource leaks and continuous DOM node build-up when creating lots of Text or BitmapData objects, or when calling `generateTexture` on any display object. The CanvasPool will do its best to re-use out dated canvas elements rather than filling up the DOM with new ones.
* Sprite.setTexture has a new `destroyBase` parameter - set this to `true` if you know the base used a generated texture that isn't being used by any other sprites. This will free-up the canvas for further re-use by other calls to `generateTexture` or Text objects.
* Line.midPoint will return a Point object where the `x` and `y` values correspond to the center (or midpoint) of the Line segment.
* Line.rotateAround allows you to rotate a Line around the given coordinates (in world space)
* Line.centerOn will position the Line so that its midpoint lays on the coordinates given.
* BitmapData.line draws a line to the BitmapData in the color and thickness specified.
* BitmapData.op is a handy short-code to get and set the canvas global composite operator.
* BitmapData.drawFull draws the given Game Object or Group to a BitmapData and then recursively iterates through all of its children, including children of Game Objects and Groups. It can draw Text, BitmapText, Sprites, Images, Emitters and Graphics objects. It's perfectly valid to pass in `game.world` as the parent object, and it will iterate through the entire display list.
* Phaser.TilemapParser.INSERT_NULL is a new boolean that controls what happens when the parser encounters an empty tile: When scanning the Tiled map data the TilemapParser can either insert a null value (true) or a `Phaser.Tile` instance with an index of -1 (false, the default). Depending on your game type depends how this should be configured. If you've a large sparsely populated map and the tile data doesn't need to change then setting this value to `true` will help with memory consumption. However if your map is small, or you need to update the tiles (perhaps the map dynamically changes during the game) then leave the default value set (thanks #1982)

### Updates

* TypeScript definitions fixes and updates (thanks @clark-stevenson @vrecluse @yahiko00 @cloakedninjas @qdrj)
* JSDoc typo fixes (thanks @Cowa @yahiko00 @qdrj @STuFF)
* VideoStream.active = false is used if the browser supports it, otherwise it falls back to VideoStream.stop.
* Text can now accept `undefined` or `null` as the `text` argument in the constructor and will cast it as an empty string.
* Point.rotate uses a faster and simpler rotation function when no distance argument is specified.
* Setting a P2.Body from Static or Kinematic to Dynamic will now automatically adjust the Body.mass to be 1 (thanks @wayfu #2005)
* Pointer.withinGame is no longer automatically set to `false` in the `Pointer.stop` method. Instead it will check if the Pointer actually is within the stage bounds and only set `withinGame` to `false` if it's outside the bounds.
* MSPointer now has an `onPointerUpGlobal` handler for when the pointer is released outside of the canvas, but still within the browser window. This means that in IE11 a Sprites `onInputUp` event will now trigger even when outside the canvas (thanks @bvargish #2000)
* MSPointer now has handlers for the pointer being over and outside of the canvas element, which sets the `Pointer.withinGame` booleans accordingly. It also triggers the `Mouse.mouseOutCallback` and `Mouse.mouseOverCallback` callbacks respectively.
* The MSPointer event listeners have been renamed to all lower-case, i.e. 'pointerDown' is now 'pointerdown'.

### Bug Fixes

* Pointer.isDown was reset before the `Input.onUp` event, meaning you couldn't get the Pointer duration from within the event.
* Pointer.isDown was reset before the Input tap calculations, meaning `onTap` wouldn't dispatch (thanks @stovenator #1953)
* InputHandler.pointerOver would get stuck in an 'isOver' state if the Sprite changed its visibility during an `onUp` callback (thanks @Cristy94 #1955)
* If you override the P2 mpx functions, to define your own px to meters values, the P2 Debug Bodies would ignore it (thanks @vrecluse #1957)
* ArrayUtils.numberArrayStep would return an empty array if a single parameter was given, instead of a single step array (thanks @pooya72 #1958)
* Text with tints applied wouldn't update properly in Canvas mode.
* Removed use of the deprecated `enterFullScreen` and `leaveFullScreen` signals from the Scale Manager (thanks @mmanlod #1972)
* BitmapText with tints applied wouldn't update properly in Canvas mode (thanks @Pajamaman #1969)
* Group.cacheAsBitmap would be incorrectly offset in Canvas mode (thanks @mkristo #1925)
* Text.setTextBounds didn't add the x and y values to the width and height offsets.
* Line.rotate used a calculation method which resulted in the line growing (or shrinking) in length over time the more it was rotated. The new method never changes the lines length.
* BitmapText.font failed to pull the new font from the Phaser Cache, stopping it from updating properly (thanks @AbrahamAlcaina #2001)
* Video.stop now removes the 'playing' event listener, which stop Videos set to loop from throwing errors after being destroyed.
* Tilemap.createFromObjects has been strengthened so that will only create Sprites for matching gids/ids/names. It also only sets the Sprite width and height values if they are present in the Tiled data (thanks @pparke #2012)
* TilingSprite._renderCanvas wasn't correctly allowing for pixel rounding (thanks @ximop #2022)
* Cache.addSpriteSheet didn't include default values for the `frameMax`, `margin` and `spacing` arguments (thanks @vladkens #2017 #2018)
* Tilemap.shuffle was calling the deprecated Phaser.Utils.shuffle, which has now moved to Phaser.ArrayUtils.shuffle.
* Enabling a filter on a display object that had a multiply blend mode set would cause the object to become invisible. The two cannot be combined, so when you set a filter on a display object it now automatically resets the blend mode to `NORMAL`. The same does not happen in reverse however, so if you've got a filter set and then change the blend mode to multiply it will still break. Be careful to capture this yourself (thanks @wayfu #1994)

For changes in previous releases please see the extensive [Version History](https://github.com/photonstorm/phaser/blob/master/CHANGELOG.md).

![div](http://www.phaser.io/images/github/div.png)

<a name="contributing"></a>
## Contributing

Please read the [Contributors Guide][contribute] for full details on helping with Phaser, but the main points are:

- Found a bug? Report it on [GitHub Issues][issues] and include a code sample.

- Pull Requests should only be made against the `dev` branch. *Never* against `master`.

- Before submitting a Pull Request run your code through [JSHint](http://www.jshint.com/) using our [config](https://github.com/photonstorm/phaser/blob/master/.jshintrc).

- Before contributing please read the [code of conduct](https://github.com/photonstorm/phaser/blob/master/CODE_OF_CONDUCT.md).

Written something cool that shows Phaser in use? Please tell us about it in our [forum][forum] or email: support@phaser.io

[![Build Status](https://travis-ci.org/photonstorm/phaser.png?branch=dev)](https://travis-ci.org/photonstorm/phaser)

![div](http://www.phaser.io/images/github/div.png)

![storm](http://www.phaser.io/images/github/photonstorm-x2.png)

Phaser is a [Photon Storm](http://www.photonstorm.com) production.

Created by [Richard Davey](mailto:rich@photonstorm.com). Powered by coffee, anime, pixels and love.

The Phaser logo and characters are &copy; 2015 Photon Storm Limited.

All rights reserved.

"Above all, video games are meant to be just one thing: fun. Fun for everyone." - Satoru Iwata

[![Analytics](https://ga-beacon.appspot.com/UA-44006568-2/phaser/index)](https://github.com/igrigorik/ga-beacon)

[get-js]: https://github.com/photonstorm/phaser/releases/download/v2.4.3/phaser.js
[get-minjs]: https://github.com/photonstorm/phaser/releases/download/v2.4.3/phaser.min.js
[get-zip]: https://github.com/photonstorm/phaser/archive/v2.4.3.zip
[get-tgz]: https://github.com/photonstorm/phaser/archive/v2.4.3.tar.gz
[clone-http]: https://github.com/photonstorm/phaser.git
[clone-ssh]: git@github.com:photonstorm/phaser.git
[clone-svn]: https://github.com/photonstorm/phaser
[clone-ghwin]: github-windows://openRepo/https://github.com/photonstorm/phaser
[clone-ghmac]: github-mac://openRepo/https://github.com/photonstorm/phaser
[phaser]: https://github.com/photonstorm/phaser
[issues]: https://github.com/photonstorm/phaser/issues
[examples]: https://github.com/photonstorm/phaser-examples
[contribute]: https://github.com/photonstorm/phaser/blob/master/CONTRIBUTING.md
[forum]: http://www.html5gamedevs.com/forum/14-phaser/

[game1]: https://www.prodigygame.com/Fun-Math-Games/
[game2]: http://www.bbc.co.uk/cbbc/games/deadly-defenders-game
[game3]: http://www.defiantfew.com/
[game4]: http://www.pawpatrol.com/fun.php
[game5]: http://www.fyretale.com/
[game6]: http://www.pocoyo.com/juegos-ninos/caramelos
[game7]: http://www.html5gamedevs.com/topic/11179-phaser-cocoonjs-tap-tap-submarine/
[game8]: http://www.gamepix.com/project/footchinko/
[game9]: http://orcattack.thehobbit.com
[game10]: http://phaser.io/news/2015/06/bubble-academy
[game11]: http://phaser.io/news/2015/07/woodventure
[game12]: http://phaser.io/news/2015/04/hopsop-journey-to-the-top
[game13]: http://phaser.io/news/2015/05/banana-mania
[game14]: http://phaser.io/news/2015/06/salazar-the-alchemist
[game15]: http://phaser.io/news/2015/05/phaser-shmup
[game16]: http://phaser.io/news/2015/05/trappy-trap
[game17]: http://phaser.io/news/2015/04/runaway-ruins
[game18]: http://phaser.io/news/2015/04/ananias
