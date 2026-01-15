# CSS selectors: divs and spans

## commenting: 
- good for descriptions of functions and debugging
- ignored by computer
- `/* this is a comment */`

## `<div>` tag:
- good for styling only certain portions of website
- "container element"
- stretches entire width of page
  - tiles vertically
  - `display: block;` by default

## `<span>` tag:
- good for styling phrases within paragraphs
- "container element"
- only stretches length of text
  - tiles horizontally
  - `display: inline;` by default

## example 1:
```css
    /* style.css */
    div{
        background: pink;
        border: red 10px dashed;
    }
    span{
        background: lightblue;
        color: black;
    }
```
```html
    <!-- index.html -->
    <head>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <p>paragraph outside of div</p>
        <div>
        <p>...inside of div</p>
        <p>...inside of div...<span>in a span!</span></p>
        </div>
    </body>
```
## classes:
- container tags can be defined with a parent class...
  - `<span class="greentext">this text is green!</span>`
- ...who can be referenced when styling in css...
  - `.greentext{ color: green }`
