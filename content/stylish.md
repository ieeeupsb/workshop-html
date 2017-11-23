# Make it *stylish*
You now know a few elements. Let's learn how to change them more pleasant to look at in a few different ways.
## The *Style* Attribute
The style of an HTML element can be set with the **style attribute**:
```XML
<tagname style="property: value;">
```
The **property** is a CSS property, associated with its CSS **value**. We'll talk about **CSS** later on.  
Some of the most used **properties** are:
 - **background-color** - used to change an element's background color
 - **color** - changes an element's text color
 - **font-family** - used to change the font
 - **font-size** - changes the size of the font
 - **text-align** - changes the text alignment (center, right, left,...)

```XML
<body style="background-color: Tomato; color: #fff; text-align: center;">

<h1 style="background-color: DodgerBlue;">
<p style="font-family: Verdana; font-size: 160%;">
```
Try changing those properties on your Web Page, see if that makes any difference...
> This is were "Inspect Element" will be particularly useful, as you can change properties and values in a fast and easy way. **Try it!**

## Formatting Text
When it comes to formatting text, you can use the style attribute, but there are also **special elements** that you should know about:
 - **``<b>``** - Bold
 - **``<i>``** - Italic
 - **``<small>``** - Smaller text
 - **``<sub>``** - Subscripted text
 - **``<sup>``** - Superscripted text

> You can also use **``<strong>``** to make text bold, and **``<em>``** to make it italic (emphasized). They have the same result as **``<b>``** and **``<i>``**, but they have add a different meaning: you use **strong** and **em** with "important text".

These elements do not start a new line, and they take only as much width as they need. These type of elements are called **Inline Elements**.  
There is an inline element that does this without adding any style - the **``<span>``** element.  
It will be useful when joined with the **style** attribute, like this:

```XML
<p>This is a paragraph with <b>bold text</b>...</p> 
<p>This is also a paragraph with <span style="font-weight: 600;">bold text</span></p>
<p>This is <span style="color: Red;">red text</span>!</p>
<span> </span>
```

## Colors
A big part of a Web Page's style is its color.  
You have seen multiple **color names**, like ``Tomato``, ``DodgerBlue``, or ``Red``.

*What color can I use, and what are their names?*  
There are [140 color names](https://www.w3schools.com/colors/colors_names.asp) recognized by all browsers. But these aren't the only colors you can use. In fact, you can use **any color**, in multiple notations: **HEX**, **HSL**, **RGB**, **RGBA**, **HSLA**.

For example, FEUP's official collor, as you can see [here](http://manualdeimagem.up.pt/index.php?/unidadeorganica/cores/), is:  
**R159 G45 B32**

## Introducing CSS

[Main Menu](../README.md)
