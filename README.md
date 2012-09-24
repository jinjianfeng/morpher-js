# MorpherJS

MorpherJS is an JavaScript image morphing library. It uses HTML 5 canvas element.

MorpherJS comes along with [GUI] which helps you to configure your own Morpher instance (add images, define geometry, etc.).

# Features

* Unlimited images count &mdash; use as many as you need,
* Custom blend functions,
* Animation with jQuery easing support.

# Usage

* Use [GUI] to configure your own morpher,
* Export JSON code with your configuration,
* Include [morpher.js] file on your page,
* Create Morpher instance:

  var json = {}; // the code you've exported from GUI
  var morpher = new Morpher(json);

* Add morpher's canvas to the DOM:

  document.body.appendChild(morpher.canvas);

* Animate it!

  morpher.set([1, 0]);
  morpher.animate([0, 1], 200);

Check out [demos page] for an inspiration.

# License

Copyright (c) 2012 Paweł Bator. MIT License, see [LICENSE] for details.

[LICENSE]: https://github.com/jembezmamy/morpher-js/blob/master/LICENSE