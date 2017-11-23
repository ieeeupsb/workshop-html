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
This color can be represented in RGB: **``rgb(159,45,32)``**, HEX: **``#9f2d20``** or HSL **``hsl(6, 66%, 37%)``**.

 - **RGB** stands for Red, Blue and Green, and the values are presented in **0-255**.  
 - In **HEX** notation, you also use Red, Green and Blue from 0 to 255, but you convert the numbers to hexadecimal (which becomes **2 characters** for each color, like ``9F``), and then you join them, like this: **``#RRGGBB``**.  
 - **HSL** stands for Hue, Saturation and Light, another way of expressing colors.

There are multiple tools online to convert colors between different notations, like [this one](https://www.w3schools.com/colors/colors_converter.asp).

```XML
<h1 style="color: #FFFFFF; background-color: #9F2D20;">Title in FEUP's color</h1>
<p style="color: #FFFFFF; background-color: #FF0000;">This is red!</p>
<p style="color: #FFFFFF; background-color: rgb(255,0,0);">This is the same red!</p>
<p style="color: #FFFFFF; background-color: rgba(255,0,0,0.5);">This is the red with 50% opacity...</p><br>
<p style="color: #FFFFFF; background-color: #ffa500;">This is yellow!</p>
<p style="color: #FFFFFF; background-color: #3cb371;">This is green!</p>
```
> Use your "Inspect element" once again to try different colors!  
Try your own color combinations here: [https://color.adobe.com/pt/create/color-wheel/](https://color.adobe.com/pt/create/color-wheel/)  
Find more examples here: [https://www.w3schools.com/colors/colors_trends.asp](https://www.w3schools.com/colors/colors_trends.asp)

## Introducing CSS
So far, Web Design is seeming pretty *tedious*, right?  
In the same example above, you have to write **``color: #FFFFFF``** 6 times, to make the text color of 6 different elements **white**. Besides, your code is starting to get bigger and more difficult to read. How can we avoid this?

One way, would be to apply the style **``color: #FFFFFF``** to the **body** element, and then you only have to specify it once!  
All the text inside the **body** element would turn white. But now, the text with white background becomes invisible.

Another way is using **CSS**. CSS will make your code smaller and easier to understand, while solving a few problems.  
There are three ways of adding CSS to your HTML document:
 - **Inline** - this is what you have been doing, with the **``sytle``** attribute
 - **Internal** - using a **``<style>``** element in your **``<head>``**
 - **External** - using an external CSS file, that you can edit seperatly and use for multiple pages
 
Let's try **Internal CSS**:  
```XML
<!DOCTYPE html>
<html>
<head>
 <style>
 body {
  background-color: #9f2d20;
 }
 h1 {
  background-color: #fff;
  color: #000;
 }
 p {
  font-weight: 600;
 }
 </style>
</head>
<body>

<h1>This is my title</h1>
<p>This is a paragraph...</p>
<p>This is another paragraph...</p>

</body>
</html>
```
We'll learn how to use CSS a little better with a few examples...

[Main Menu](../README.md)
