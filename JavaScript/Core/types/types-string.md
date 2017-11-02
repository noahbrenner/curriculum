# Types - String
author: alexjmackey

levels:

  - beginner

type: normal

inAlgoPool: false

tags:
  - introduction
  - workout

standards:
  js.evaluate-expressions: 10
  js.write-expressions: 10
  js.data-types-structures: 20
  js.identify-syntax: 10

category: must-know

---
## Content

You can declare a string value in JavaScript using either single or double quotes - JavaScript will accept either:
```
var company = "Enki";
var company = 'Enki';
```

If you have longer text you can combine multiple strings by using the + operator:

```
var longerText = "abc" +
		"def" +
		"ghi";
```

You can also use the backslash character to "escape" the line feed, to write on multiple lines (make sure nothing is after the backslash except the carriage return).

```
var longerText = "abc\
def\
ghi";
```

There are also special characters that can be used by preceding the character with a backslash. Here are some common ones:
```
\’ single quote
\" double quote
\\ backslash
\n new line
\r character return
\t tab
```

---
## Practice

What special character is used to add a `new line` to strings?

```javascript
var myString = 'this will ???
       be displayed on two lines';
```

*`\n`
*`+`
*`"`
*`\`
*`\r`
*`\t`

---
## Revision

Which one of the following is correct ?
```
var company = "Enki";
var company = 'Enki';
```

???

*both
*first
*second
*none
