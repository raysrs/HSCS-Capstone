# CSS Margins & Padding

## positioning
- by default, `position: static;`
- relative positioning:
  - `position: relative;`
  - lets us use `top:` and `left:` properties to move object from initial (static) position
  - `bottom:` and `right:` can also be used
- absolute positioning:
  - `positionin:absolute`
  - relative to containing element (often body) rather than static position
  - almost as if object floating above page
- there are other kinds of positioning
  
## margins and padding
- space around & between html elements
- html elements tend to have default margins & padding
    ```css
    body{
    /* clears default margins & padding */
        margin: 0;
        padding: 0;
    }
    ```
- margin creates space on outside of element
- padding creates space on inside of element
- margin & padding can be different for different sides (top, left, etc.)
- setting margin to "auto" centers element

