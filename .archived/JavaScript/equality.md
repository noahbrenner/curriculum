# Equality
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

JavaScript supports two types of comparison operators: **loose** and **strict**.

We use two equal signs for **loose equality**, which will attempt to cast the second variable to the same type as the first.
```
1==1 //true

1=="1" //also true!
```

**Strict equality** will check that the values are of the same type, for this we use 3 equals signs.


```
1==="1" //false
1===1 //true
```

JavaScript also supports loose and strict not equal:
```
1!="1" //false
1!=="1" //true
```

---
## Practice

The following check will evaluate to:
```
42 !== "42"
// ???
```

* `true`
* `false`

---
## Revision

`===` is called ???

* strict equality
* loose equality
* triple equality
* not equal
