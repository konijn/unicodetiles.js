UnicodeTiles.js
===============

This JavaScript library provides a text character based tile engine for creating roguelike games etc. The bundled font (DejaVu Sans Mono) has good coverage of Unicode, providing monospace characters for various miscellaneous symbols that can be useful in creating fancy looking character based games and user interfaces.


Current features
----------------
* Viewport - _character grid display_
	- Colored characters
	- Colored character backgrounds
	- Arbitrary character viewport size
	- Character size customizable through CSS
	- Utilizes CSS3 Web Fonts (@font-face)
* Engine - _the tile engine_
	- Viewport updating according to player coordinates
	- Tile reading through a callback
	- Masking callback (for FOV etc.)
* Meta - _General meta stuff_
	- Comprehensive API documentation
		+ Generated with Natural Docs from source code comments
	- Static analysis frequently performed
		+ [JSHint](http://www.jshint.com/)
		+ [Google Closure Compiler](http://closure-compiler.appspot.com/)
	- Several examples / tutorials
		+ See examples/ subfolder
	- Minification toolchain through [Google Closure Compiler](http://closure-compiler.appspot.com/)

Usage
-----

See examples/ subdirectory.


License
-------

Copyright (c) 2012 Tapio Vierros
	
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
