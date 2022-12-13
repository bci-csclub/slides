---
theme: seriph
layout: cover
class: 'text-center'
background: ''
highlighter: shiki
---

# Intro To CSS

---

# Structure

- creating a personalized site
- as we learn we will add
  - features
  - interactivity
  - and _style_
- implement a project together
  - computer science club site
- today we will learn HTML

---
layout: fact
---

[where will write HTML and CSS today](https://stackblitz.com/edit/web-platform-7a31ff?file=index.css)

---

# CSS

- Cascading Style Sheets
- select html elements
- change there style

---
layout: better-center
---

# CSS Rule

::example::

```css {1,3|2}
h1 {
  color: lavendar;
}
```

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
    <link rel="stylesheet" href="index.css" />
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

# Element Selector

::example::

```css
p {
  color: blue;
}

p,
h1,
li {
  background-color: red;
}
```

::task::

### Task:

- style the paragraph and header a different color

---
layout: better-center
---

# ID Selector

::example::
```html
<h1 id="header">Header</h1>
```
```css
#header {
  color: green;
}
```

::task::

### Task:

- add an ID to one element
- style that element by it's ID

---
layout: better-center
---

# Class Selector

::example::

```html
<h1 class="header">Header</h1>
```
```css
.header {
  color: gray;
}
```

::task::

### Task:

- !TODO

---
layout: better-center
---

# Colours

::example::

```css
p {
  color: red; /* name */
  background-color: rgba(255, 255, 0, %50); /* yellow */
  border-color: #00FFFF /* #0FF cyan hex code */
}
```

::task::

### Task:

- change the text and background color of the header
---
layout: better-center
---

# Text and Fonts

::example::

```css
.small {
  font-height: 15px;
  font-style: italic;
  font-wheight: bold;
  font-family: "Fira Code";
}
```

::task::

### Task:

- make a large class
- apply it to a text element
- make the text large and bold 
- add a font from google fonts

---
layout: better-center
---

# Box Model

::example::
- block box
- inline box

```css
* {
  border: 1px solid red;
}
```

---
layout: better-center
---

# div and span

::example::

```html
<div></div>
<!-- divider(block) -->
<span></span>
<!-- inline -->
```

::task::

### Task:

- experiment with different elements
- what does there box look like
- what is the default padding
- how do they look nested

---
layout: better-center
---

# Borders

::example::

```css
.card {
  border-width: 1px;
  border-style: solid;
  border-colour: #39404f;
  border: 1px solid #3940f;
  border-radius: 5px;
}
```

::task::

### Task:

- go to the tasks.html file
- make each task a card

---
layout: better-center
---

# Margins

::example::

```css
.box {
  margin-top: 5px;
  margin-right: 5px;
  margin-bottom: 5px;
  margin-left: 5px;
  margin: 5px;
}
```

::task::

### Task:

- add a margin to only the top and bottom
---
layout: better-center
---

# Padding

::example::

```css
.padded {
  padding: 10px 5px 10px 5px;
}
```

::task::

### Task:

- add padding to you card 
---
layout: better-center
---

# Height and Width

::example::

- same for width
```css
.size {
  height: 50px;
  height: 50%;
  height: 100vh;
  max-height: 50px;
  min-height: 30px;
}
```

::task::

### Task:

- change the size of the cards
---
layout: better-center
---
# Flex Box

::example::

```

```

::task::

### Task:

- 
---
layout: better-center
---

# Grid

::example::

```

```

::task::

### Task:

- 
---
layout: better-center
---

# Animations

::example::

```

```

::task::

### Task:

- 
