Javascript 6/30 Type Ahead

What I learned:

RegExp Object
A regular expression is an object that describes a pattern of characters.

Regular expressions are used to perform pattern-matching and "search-and-replace" functions on text.

Fetch API will return a promise

const cities = [];

fetch(endpoint)
	.then(blob => blob.json())
	.then(data => console.log(...data)) //spread into push method, will return cities