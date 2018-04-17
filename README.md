# Mini Linter

The Mini-linter app takes a short story about a bicycle trip, and cleans it up using array iterator methods.

## Iterator Methods

One of the most common tasks a developer translates into code, is looping over the contents of an array. Programmers often accomplish this with a **for** loop. Javascript has made this task easier using **ITERATOR METHODS**.

* **Iterator Methods** are called on each item in an array, processing it with a function.

* Iterator Syntax - .forEach()
  * the .forEach method is an array method, and therefore can only be called on an array.
  * any changes to the iterated array won't be updated in the original array.
  * the return value is undefined.

```
let players = ['Dwayne Wade', 'Kobe Bryant', 'Lebron James', 'Shaquille O'Niel', 'Larry Bird', 'Michael Jordan', 'Yao Ming'];

players.forEach(function(player)){
 console.log(player + ' is one of the greatest basketball players in NBA history.')
});
```

######### Note: the above example could have been abbreviated with the Arrow Function Syntax

* Iterator Syntax - .map()
  * the.map() iterator method returns a new array with elements that have been modified by the code in it's function block.

```
let numbers = [1,2,3,4,5];
let sqaureNumbers = numbers.map(function(number)){
 return number * number;
});
```

######### Note: the above example could have been abbreviated with the Arrow Function Syntax

* Iterator Syntax - .filter()
  * the .filter() method also returns a new array of elements, as long as those elements evaluate to truthy, based on the code in it's function block.

```
let things = ['book', 'dog', 10000, true, 'Yvonne'];
let onlyNumbers = things.filter(function(thing)){
 return typeof thing === 'number';
});
console.log(onlyNumbers);
```

######### Note: the above example could have been abbreviated with the Arrow Function Syntax

* Iterator Return Values -
* Iterator Documentation -

Questions:

When is it appropriate to use Iterator Methods vs. For Loops? Which types of situations most appropriately apply to each?
