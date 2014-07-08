## De-Compacted Version of HTML5 Reset CSS for Debugging

* Author: [John Dyer](http://johndyer.name/)
* License: GPLv2/MIT

### Purpose

HTML Reset, originally by [Eric Meyer](http://meyerweb.com/eric/tools/css/reset/)
and given HTML5 updates by folks like [Richard Clark](http://html5doctor.com/html-5-reset-stylesheet/), is awesome.

But it makes tools like Firebug, WebKit inspector, IE Developer Tools, and Opera Dragonfly hard to use.
HTML Reset *Debug* makes site development easier by listing each selector only once and explicitly defining all CSS properties and values.
Once your site is built, you should switch to a compacted, minified version of your choice.

### Examples

Here's a few elements and how they are defined.

	html {
		margin: 0;
		padding: 0;
		border: 0;
		outline: 0;
		font-size: 100%;
		vertical-align: baseline;
		background: transparent;
	}
	body {
		margin: 0;
		padding: 0;
		border: 0;
		outline: 0;
		font-size: 100%;
		vertical-align: baseline;
		background: transparent;
		line-height:1;
	}
	blockquote {
		margin: 0;
		padding: 0;
		border: 0;
		outline: 0;
		font-size: 100%;
		vertical-align: baseline;
		background: transparent;
		quotes: none;
	}
	blockquote:before {
		content: '';
		content: none;
	}
	blockquote:after {
		content: '';
		content: none;
	}
	ol {
		margin: 0;
		padding: 0;
		border: 0;
		outline: 0;
		font-size: 100%;
		vertical-align: baseline;
		background: transparent;
		list-style: none;
	}
	canvas {
		display:block;
		margin: 0;
		padding: 0;
		border: 0;
		outline: 0;
		font-size: 100%;
		vertical-align: baseline;
		background: transparent;
	}
