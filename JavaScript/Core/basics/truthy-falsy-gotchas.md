# Truthy Falsy Gotchas
author: alexjmackey

levels:

  - beginner

type: normal

inAlgoPool: false

category: must-know

tags:
  - introduction
  - workout

standards:
  js.identify-syntax: 5
  js.data-types-structures: 5
  js.write-expressions: 5
  js.evaluate-expressions: 5

links:

  - >-
    [Mozilla Developer
    Network](https://developer.mozilla.org/en/docs/Web/JavaScript/Equality_comparisons_and_sameness){website}

---
## Content

You should be aware that JavaScript has a complex set of rules that contain a few gotchas about how primitive values are compared that can lead to some unexpected comparisons.

For example:

```
false == "0" //true
false == "" //true
```
**Null**

Null is also one to beware of as behaves strangely:
```
null==false //false
```

*null* and *undefined* are special and not equal to anything but themselves. They can be _coerced_ to boolean values, but when _compared_ will behave differently.

..And there are many more of these strange cases so watch out!

---
## Revision

What will the following snippet evaluate to?
```
null == false
// ???
```
*`false`
*`true`
