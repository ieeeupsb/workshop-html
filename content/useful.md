# Make it useful
You now know the basics, but your page doesn't do anything usefull yet. In this section you will learn how to build links, how to deisplay images and how to make lists.

## Links

Links are found in almost every HTML page. HTML links are hyperlinks, you can click on a link and jump to another documen. When the mouse ponter is on top of the link it will turn into a little hand.
In HTML links are defined with the **`<a>`** tag.

### Syntax

The way you build the link is like this: `<a href="url">link text</a>`. So linking the word **Google** to the google page would look something like this

```html
<a href="https://www.google.pt/">Google</a>
```

### Target Attribute

The **target** atribute defines where to open the clicked link.

It can have one of the following values:

* _blank - Opens the linked document in a new window or tab
* _self - Opens the linked document in the same window/tab as it was clicked (this is default)
* _parent - Opens the linked document in the parent frame
* _top - Opens the linked document in the full body of the window
* framename - Opens the linked document in a named frame

To open the link google in a new tab, the syntax would be this:
 
 ```html
 <a href="https://www.google.pt/" target="_blank">Google</a>
```



### Links inside things

You can next links inside other elements! For example you want an image to be a link. You an put the image(the sintax to call an image will be on the next section) inside link tag and this image will have an image link! 
```html
<a href="https://www.google.pt/">
  <img src="http://tinyurl.com/yc3dd8mw" alt="Google">
</a>
```
## Images

Images improve the look and design of page. In your page it will be useful, for example, to display your profile page! The image tag is **`<img>`**.

### Syntax

It is really easy to display an image. The syntax is: **`<img src="url">`**. If that image is at the same folder as your HTML file and, for example, the image name is *myImage.jpeg* the call would be:

```html
<img src="myImage.jpg" alt="myImage">
```

### The *alt* Attribute

The alt attribute provides an alternative text for when the image is not avaible, for example if the user has bad connection or the **src** is broken. It is mandatory and it should describe the image!

### Image Size - Width and Height

This can be done in two ways:
1. Specifying with and *Width* and *Height*
```html
<img src="myImage.jpg" alt="myImage" width="500" height="600">
```
2. Using *Style*
```html
<img src="myImage.jpg" alt="myImage" style="width:500px;height:600px;">
```

**NOTE:** Beware when using *Style*. You cannot further modify your image in a css file! Also avoid hard coding pixels! Use dp (densiy pixels) instead!

### Images in Another Server

In the *srs* attribute you can specify an image link instead of a file name. The next example fetches a Google logo from a website!

```html
 <img src="http://tinyurl.com/yc3dd8mw" alt="Google">
```

## Lists

Everyone loves lists! In HTML you have two tipes of lists:
1. **Unordered Lists**, commonly known by bullet lists
2. **Ordered Lists**, normal number listing

### Unordered List

An **Unordered List** starts with the **`<ul>`** tag. Each item starts with the **`<li>`** tag. Note that **ul**- unordered list, **li**-list item.
Each list item will be marked with bullets by default. Example:

```html
<ul style="list-style-type:none">
  <li>Cofee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```
</ul>

### Ordered List

An **Ordered List** starts with the **`<ol>`** tag. Each item starts with the **`<li>`** tag. Note that **ol**- ordered list, **li**-list item.
Each list item will be numbered default. Example:

```html
<ol style="list-style-type:none">
  <li>Cofee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

### A different kind of list: Description List

A description list is a list of terms, with a description of each term.
The **`<dl>`** tag defines the description list, the **`<dt>`** tag defines the term (name), and the **`<dd>`** tag describes each term: 

```html
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
```

### The sky is the limit!

You can do almost everything with list items!
You can nest them:

```html
<ul>
  <li>Coffee</li>
  <li>Tea
    <ul>
      <li>Black tea</li>
      <li>Green tea</li>
    </ul>
  </li>
  <li>Milk</li>
</ul>
```

You can also make a link from the list item, put images as items, and many other things! Explore and have fun :smile:.
[Main Menu](../README.md)
