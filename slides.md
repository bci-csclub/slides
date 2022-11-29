---
theme: seriph
layout: cover
class: 'text-center'
highlighter: shiki
colorSchema: "dark"
---

# Intro To Web Development

---

# Structure

- creating a personalized site
- as we learn we will add
  - features
  - interactivity
  - and *style*
- implement a project together
  - computer science club site
- today we will learn HTML

---
layout: fact
---

[where will write HTML today](https://stackblitz.com/edit/web-platform-zj7ksv?file=index.html)

---

# What is the "Web"

- a metaphorical web
- composed of computers around the world that talk to each other
- computers can find each other with ip addresses
- ip addresses are hard to remember so we have urls
- web is composed of websites
- which are composed of webpages
  - file is HTML
  - can include both CSS and Javascript we will go over that in the next lessons

---

# State of the web

- early web was just html, css and js
- communicating with a server and database
- modern web frameworks
  - react
  - vue
  - angular
  - svelte
- typescript

---

# HTML
- markup language
- structure your content
- browsers reads "markup"
- renders to your screen
---
layout: better-center
---

# HTML Element

::example::
```html
  <p>Hello world</p>
  
  <p
  class="small">
  Hello world
  </p>
```
---
layout: better-center
class: "example-small"
---

# Structure of HTML
::example::
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width" />
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

# Headers

::example::

```html
<h1>Hello world</h1>
<h2>Hello world</h2>
<h3>Etc</h3>
```
::task::
### Task:

- create an `h1` with your name in it
---
layout: better-center
---

# Paragraphs
::example::
```html
<p>smaller text goes here</p>
```
::task::
### Task:
- write one short thing about yourself under the title
---
layout: better-center
---

# Images
::example::
```html
<img 
src="https://example.com/image.png"
alt="This is the description of an image">
```
::task::
### Task:
- find an image online
- add it to your site
---
layout: better-center
---

# Lists
::example::
```html
  <ul>
    <li>An item</li>
    <li>Another item</li>
  </ul>
  <ol>
    <li>Item one</li>
    <li>Item two</li>
  </ol>
```
::task::
### Task:
- create a rank of fruits
- create a list of programming languages
---
layout: better-center
---

# Links
::example::
```html
  <a href="https://example.com">
  Example link
  </a>
  <a href="/" target="_blank">
  Root of the site
  </a>
```
::task::
### Task:
- in a list
  - add a link to the mdn docs
  - and w3schools site
  - hint: look them up on google


---

# Next up
- CSS
- javascript
- developing on your own computer
- git and github
- web frameworks
  - mini project
- maybe a whole club project
