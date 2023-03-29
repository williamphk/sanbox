# Introduction to Markdown

## Paragraphs and Headers

This is a paragraph.

This is another paragaraph.
This text is not a new paragraph.

This text is *italics* and this text is **bold** and this text is both ***bold and italics***

## Lists

### Unordered lists

- Use a dash as a bullet
- No space before the dash
- One space after the dash
- If you have two lines in this list item

    Use four spaces to indent the next line

### Ordered Lists
1. Use numbers
2. A space after the number
3. If you have two lines in this list item

    Use four spaces to indent the next line

## Links

Here is a link to [my website](https://www.linkedin.com/in/williamphk).

Properly formatted URLs will be linked:

www.linkedin.com/in/williamphk

## Images

Images can be added by using a full URL

![Text Image](https://raw.githubusercontent.com/williamphk/sanbox/main/_readme/IMG-20170424-WA0002.jpg)

The URL can also be relative:

![Text Image](/_readme/IMG-20170424-WA0002.jpg)

You can use plain HTML in a README.md file

<img src="https://raw.githubusercontent.com/williamphk/sanbox/main/_readme/IMG-20170424-WA0002.jpg" width="50px">

## Code 

Use the `<html>` tag to start an HTML document.

``` javascript
console.log("Hello World!");
document.write("<h1>Hello World!</h1>")
```

## Tables

| First Heading | Second Heading |     | 
| ------------- | -------------- | -:  |
| Value 1       | Value 2        | 1.0 |
| Value 3       | Value 4        | 1.0 |

First Heading | Second Heading | #
---|---|---:
Value 1 | Value 2 | 1.0
Value 3 | Value 4 | 1.0
