jQuery.ish 0.1
=========

A baseline feature set and jQuery compatible syntax for modern browsers. Use it as part of your toolset for page performance where the full version of jQuery is not desired.

## This project is to:

- include the parts of jQuery that we can't live without and use native js methods for everything else
- download size of less than 500 bytes minified and gzipped
- offer 100% jQuery compatible syntax
- full support for jQuery style chaining

## This project is NOT to:

- create a full featured jQuery alternative, checkout the [zepto][2] project if that is what you need
- create a plugin that is more than 500 bytes minified and gzipped

## Code Size

- Original Size:  1.7KB (576 bytes gzipped)
- Compiled Size:	1.23KB (483 bytes gzipped)

## Browser Support and Dependancy

Browser support dependencies:

- [querySelectorAll][1]
- [getComputedStyle][3]

## Supported Methods

- hasClass()
- addClass()
- toggleClass()
- removeClass()
- toggle()
- show()
- hide()




[1]: https://developer.mozilla.org/en/DOM/Document.querySelectorAll#Browser_compatibility
[2]: http://zeptojs.com
[3]: https://developer.mozilla.org/en/DOM/window.getComputedStyle