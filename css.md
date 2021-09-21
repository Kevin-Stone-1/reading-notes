# CSS
CSS stands for Cascading Style Sheets and what CSS allows you to do is make your website more stylish, prettier, and customized. After writing some HMTL all you see is the browser default styling. CSS allows us to put that extra touch on the page to draw eyes to where we want them to go and brings some clarification as well.

### Common CSS Styling
Some common CSS stylings include

1. text color
2. font-size
3. background-color
4. border-color


### CSS Syntax
The CSS syntax looks like this example below

```
h1 {
    color: purple;
    font-size: 2em;
}
```

This code snippet here is showing how to chenge the h1 heading in our HTML to purple color text and a 2em font-size.

## Ways to Apply Your CSS

1. External CSS - When you link a stylesheet in the "head" tag of your HTML with an "href" to the .css file
2. Inline CSS - When you apply your CSS directly into a tag for instance an "h1" tag or "p" tag.
3. Internal CSS - When you are in the "head" tag of the HTML file you create an openning and closing tag of "style" within the head and put your CSS there.

While creating the CSS code, if you make changes on the same "h1" tag, in multiple places, there is a heirarchy of which CSS code will be ran.

It starts with:

1. Inline Style
2. External and internal style sheets
3. Browser default

So, when there is an inline style that will be diplayed, but if that is not present then the external and internal style sheets will be displayed, and if there isn't either of those, the browser default will be displayed. This is like a "cascading" effect.

[Home](README.md)