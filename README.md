# class-change.js

[![NPM](https://img.shields.io/npm/v/class-change.svg?style=flat-square)](https://www.npmjs.com/package/class-change)
[![Build Status](https://img.shields.io/travis/jhildenbiddle/class-change/master.svg?style=flat-square)](https://travis-ci.org/jhildenbiddle/class-change)
[![Codacy](https://img.shields.io/codacy/grade/ed39ed7fd6d842c1b2b13d20030d34f1.svg?style=flat-square)](https://www.codacy.com/app/jhildenbiddle/class-change?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=jhildenbiddle/class-change&amp;utm_campaign=Badge_Grade)
[![Codecov](https://img.shields.io/codecov/c/github/jhildenbiddle/class-change.svg?style=flat-square)](https://codecov.io/gh/jhildenbiddle/class-change)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://github.com/jhildenbiddle/class-change/blob/master/LICENSE)
[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?url=https%3A%2F%2Fgithub.com%2Fjhildenbiddle%2Fclass-change&hashtags=css,developers,frontend,javascript)

A versatile [Element.classList](https://developer.mozilla.org/en/DOM/element.classList) alternative for manipulating CSS class names, triggering change events using HTML data attributes, and creating class-related event listeners using a simple, declarative API.

- [Homepage](https://jhildenbiddle.github.io/class-change) - Documentation and usage examples

## Description

CSS class names change. A lot.

Yet the native methods for manipulating CSS class names remain rudimentary. [Element.classList](https://developer.mozilla.org/en/DOM/element.classList) provides a basic API for working with classes, but [some browsers](http://caniuse.com/#feat=classlist) suffer from an incomplete implementation (or lack support entirely), changes can only be applied to a single element, and separate event listeners must be created for each change event. The result is often polyfills or patches for legacy browsers, manual loops for applying changes to multiple elements, repeated boilerplate code for handling delegated events, and performance issues caused by a high volume of event listeners.

This micro-library aims to address these issues by reducing and simplifying the code required for CSS class changes and events.

## Contact & Support

- Create a [Github issue](https://github.com/jhildenbiddle/class-change/issues) for bug reports, feature requests, or questions
- Follow [@jhildenbiddle](https://twitter.com/jhildenbiddle) for announcements
- Add a [star on GitHub](https://github.com/jhildenbiddle/class-change) or [tweet](https://twitter.com/intent/tweet?url=https%3A%2F%2Fgithub.com%2Fjhildenbiddle%2Fclass-change&via=jhildenbiddle&hashtags=css,developers,frontend,javascript) to support the project!

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/jhildenbiddle/class-change/blob/master/LICENSE) for details.

Copyright (c) 2016 John Hildenbiddle ([@jhildenbiddle](https://twitter.com/jhildenbiddle))