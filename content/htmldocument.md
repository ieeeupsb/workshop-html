# The HTML document
The structure of an HTML document is easy to understand if you also understand English.

```XML
<!DOCTYPE html>
<html>
  <head>
    <title>This is the title!</title>
  </head>
  
  <body>
    <h1>This is the heading...</h1>
    <p>This is a paragraph!</p>
  </body>

</html>
```
- The HTML documents must start with a document type declaration: **`<!DOCTYPE html>`**.  
- After the declaration, the document itself starts with **`<html>`** and ends with **`</html>`** - this is the root **element** of every HTML page.  
- The **`<head>`** element contains information about the document (that isn't necessarily shown to the user).
- The **`<title>`** defines the document's title, that shows up in the title bar.
- The part inside the **`<body>`** element is the content displayed in a browser - **this is what the user sees!**

## Elements
An **element** in HTML is something with a **start tag**, and **end tag**, and content in between:
```XML
<tagname>Content in between...</tagname>
```

There are also **empty elements**, like **`<br>`** (the line break). Empty elements don't have content, so they don't need an end tag. As such, you can close them in the opening tag, like this: **`<br />`**. For every other element, you should always place the **end tag**.  

Sometimes your page looks correct even if you forget the end tag:
```XML
<html>
<body>

  <p>This paragraph is not "closed"
  <p>This is another paragraph

</body>
</html>
```
But we should't rely on this. **Always place the end tag to avoid unexpected results.**

The example above only works because the **``p``** element is closed when another one begins, but this doesn't happen with other types of elements.  
As you might have noticed, you can have certain elements inside others - **Nested Elements**. All HTML documents have nested elements (there's a big **``html``** element that has many other elements inside it, and so on), so keep an eye out for them.  

## Attributes
An important part of an element is its **attributes**:
```XML
<element attributeA="123" attributeB="10%">This is an example...</element>
```
Attributes provide **aditional information** about a certain element.  
They are always specified in the **start tag**, and they usually come in name/value pairs, like **``name="value"``**.

[Main Menu](../README.md)
