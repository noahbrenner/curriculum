# Variables
author: alexjmackey

levels:

  - beginner

type: normal

inAlgoPool: false

category: must-know

standards:
  js.identify-syntax: 10

tags:
  - introduction
  - workout

---
## Content

Most programming languages have a concept called **Variables**, which are how we store references to data in memory in JavaScript. JavaScript has a number of rules about variables you should keep in mind:

**Case Sensitivity**

Everything in JavaScript is case sensitive.

**Reserved Keywords**

Like most languages there are a number of reserved words in JavaScript that you cannot use to name your functions and variables.

**Identifier naming rules**

When naming any function, property or variable, the first character must be a letter, $ sign or underscore.

After the first character you are free to use numbers, letters, dollar signs or underscores.

```javascript
var name = "Enki"; //valid
var 2Company = "Enki"; //not valid
```

**Variable Scope**

Variables are declared with the **`var`** operator which creates a variable in the *current scope*. You won't notice much of a difference when writing in the global scope, but once you're inside of a function, you have a new scope.

For example, if this is used inside a function then the variable will have that value only inside the function:

```
var company="evilcorp";
function hideout(){
   var company="enki";
}
```

If you omit the `var` keyword and are not in strict mode then a variable will still be declared, but it will be declared in global scope. When this occurs on a web page, global scope is the `window` object.

Always use `var` inside of a function, unless you mean to explicitly change a global value (which is a bad idea anyway).

---
## Revision

What operator is used to declare a variable in the *current scope*?

```
??? answer = 42;
```

* `var`
* `variable`
* `string`
* `int`
* `double`

---
## Revision

Is the following line of code **valid**?
```
var 777jackpot = "jackpot";
// line is ???
```

*`not valid`
*`valid`
