# Get a random item from an Array
author: AlexYancey

levels:

  - basic

  - beginner

type: normal

category: how to

standards:
  js.data-types-structures: 20
  js.standard-library: 20
  js.write-expressions: 20


notes: ''

---
## Content

Given the array:

```
var food = ["Sushi", "Pizza", "Tacos"];
```

Select an item using `Math.random()` with a range of `food.length`.
```
var randIndex =
  Math.floor(Math.random() * food.length);
```

Now, print out the result.
```
console.log("Let's get " + food[randIndex]);
```

---
## Practice

If you have an array:
```
var fruits =[oranges, apples, banana];


How would you select a fruit at random
from the array fruits?

var index =
Math.???(Math.random()*
    fruits.length);

console.log("the random fruit is"
  +fruits[index]);
```
* floor
* ceil
* wall

---
## Revision

If you have an array:
```
var fruits =[oranges, apples, banana];
```

How would you select a fruit at random
from the array `fruits`?
```
var index =
Math.???(Math.???()*
   fruits.???);

console.log("the random fruit is"
  +fruits[index]);
```

* `floor`
* `random`
* `length`
* `ceil`
* `wall`
