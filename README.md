# simplesmoothscroll
A module to simply scroll to an element on the page in a buttery smooth fashion

## What is it?
Simple smooth scroll takes in a dom element as a param and scrolls to that element in an ease-in-out fashion. It can work on elements that are above the current window position or below the current window position

## Installation
`npm install simplesmoothscroll --save`


## Usage
```js
var smoothScroll = require("simplesmoothscroll");

var myHeader = document.querySelector("h2");

smoothScroll(myHeader);

// You can also include an offset so there is some room between
// the window position and the element

smoothScroll(myHeader, 10);
```

## Contributing
Pull requests are much appreciated and accepted.


## License
Released under the [MIT License](http://www.opensource.org/licenses/MIT)
