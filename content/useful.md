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

## Lists


[Main Menu](../README.md)
