# CSS basics
"CSS allows us to change style attributes of HTML elements"

## using CSS:
1. create ".css" file
2. select tag
3. add property-value pairs
4. link .css file to html
    - `<link rel="stylesheet" href="filename.css">`

## ways to set colors:
1. by name
2. by rgb values
3. by hex code
4. by rgba values (a = transparency)
5. other colorspaces (hsv, oklab, etc.)

## example:
```css
/* select "h1" tag */
h1{
    /* add property-value pair; using predefined color */
    color:pink;
}

li{
    /* using red, green, and blue values (0 -> 255) */
    color: rgb(0, 128, 255);
}

p{
    /* using hex code (rgb but 00 -> FF) */
    color: #FF9900
}

```

