---
theme: seriph
layout: cover
class: 'text-center'
background: ''
highlighter: shiki
---

# JavaScript

---

# JavaScript History

- web was static
- netscape wanted interactivity
- either sun's Java or Scheme
- Not Java
- created new language in 10 days

---
layout: fact
---

[where will write HTML and CSS today](https://stackblitz.com/edit/web-platform-grnnot?file=index.js)

---

# What can you do with it?

- Interact with browser APIs
- Fetch data for your site
- General programming/scripting

---
layout: better-center
class: "example-small"
---

# Adding to HTML

::example::

```html {6}
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width" />
    <script src="index.js"></script>
    <title>Template</title>
  </head>
  <body>
    <h1>Template</h1>
  </body>
</html>
```

---
layout: better-center
---

# Variables

::example::

```js{1|2|3}
let variable = "hello";
const aNumber = 1;
var aVariable = true;
```

---
layout: better-center
---

# String

::example::

```js{1|2}
let string = "string";
string = 'string';

```

---
layout: better-center
---

# Number

::example::

```js{1|2}
let number = 100;
number = 3.14;
```
---
layout: better-center
---

# Boolean

::example::

```js{1|2}
let boolean = true;
boolean = false;
```

---
layout: better-center
---

# Array

::example::

```js{1|2}
const array = [1, "2", true];
let number = array[0];

```
---
layout: better-center
---

# Object

::example::

```js{1|2}
const object  = {};
let anotherObject = "everything";
```
---
layout: better-center
---

# Funtions

::example::

```js{1,2,3|4}
function plusOne(argument) {
  return argument + 1;
}
const functionTwo = (x) => plusOne(x);
```
---
layout: better-center
---

# Comment

::example::

```js{1|3,4,5}
// line comment

/*
block comment
*/
```
---
layout: better-center
---

# Math

::example::

```js{1|2|3|4}
const add = 1 + 1;
const multiply = 5 * 5;
const divide = 10 / 2;
const subtract = 100-1;
```
---
layout: better-center
---

# Conditionals

::example::

```js{1,2|3,4|5,6|7,8,9}
if (1===0) {
  console.log(1);
} else if (1<0 || 1!=1) {
  console.log(0);
} else if (1 > 1 && 1 <= -1) {
  console.log(-1);
} else {
  console.log("this");
}
```

---
layout: better-center
---

# Control

::example::

```js
const nums = [1, 2, 3, 4]
for (const num of nums) {
  console.log(num);
}
```
---
layout: better-center
---

# Document API

::example::

```js
document.querySelector(".class");
```
