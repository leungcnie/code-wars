# code-wars
Collection of katas I've personally worked through provided by the educational community platform [Codewars](https://www.codewars.com/).

## Learning Notes
JavaScript
* Use [RegExp](https://www.w3schools.com/js/js_regexp.asp) to replace characters in a string
* You can use [lastIndexOf()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/lastIndexOf) for duplicates questions (e.g. current index of "e" should equal the last index of "e" in a word if it's not a duplicate)
* JS built-in [sort()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort) function can be used to sort an array of objects. Custom sort compare functions can be written in this pattern:
>function compare(a, b) {  
if (a is less than b by some ordering criterion) {  
&nbsp;  return -1;  
  }  
  if (a is greater than b by the ordering criterion) {  
&nbsp;  return 1;  
  }
  // a must be equal to b  
&nbsp; return 0;  
}