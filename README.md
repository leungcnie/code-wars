# code-wars
Collection of katas I've personally worked through provided by the educational community platform [Codewars](https://www.codewars.com/).

## Learning Notes
JavaScript
* Use [RegExp](https://www.w3schools.com/js/js_regexp.asp) to replace characters in a string
* You can use [lastIndexOf()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/lastIndexOf) for duplicates questions (e.g. current index of "e" should equal the last index of "e" in a word if it's not a duplicate)
* JS built-in [sort()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort) function can be used to sort an array of objects. Custom sort compare functions can be written.
* [match()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match) works on a String and returns an array of all matching characters e.g. `str.match(/t/gi)` returns all instances of "t" (case-insensitive) in a String instance `str`