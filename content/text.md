# Text - Headings & Paragraphs
From now on, let's get our hands dirty...  
Whenever you see something new, try "copy-pasting" it into your **index.html** file, save, and open it to see the result - you can reload the Web Page, or double-click the file to open it on your browser (not on your text editor).  

## Headings
Headings - section titles - are placed with the tags **``<h1>``** through **``<h6>``**:

```XML
<!DOCTYPE html>
<html>
  <body>

    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>

  </body>
</html>
```
**``<h1>``** is the bigger, most important heading. **``<h6>``** is the least important one.  
Headings are important, as search engines use them to index the content of your page. So use them to give some structure to your page: Use ``<h1>`` first, them ``<h2>``, and so on.
> Don't use headings to make the text bigger, or bold. Use them only for section titles.  
> As you might have noticed, your browser adds a small margin before and after your headings.

When you're changing topics, you might want to use an **horizontal rule**, a line to divide two sections - **``<hr>``** 
```XML
<h1>Main title</h1>
<h2>Section 1</h2>
<p>This is some text.</p>
<hr>
<h2>Section 2</h2>
<p>This is some other text.</p>
```

## Text
A **paragraph** is defined with the **``<p>``** element, as you've seen.  
Browsers will add white space (margins) before and after paragraphs.

```XML
<p>This is a paragraph!</p>
<p>This     is    another paragraph!</p>
<p>This  is    one more
  
  
  example
  
  paragraph!</p>
```
> Does this example create the expected result? **Test it!**

As you might have seen, the browser removes extra spaces and line breaks. To add new lines without starting a new paragraph, you can use the **line break**, and you have to insert a **``<br>``** element (hitting ``Enter`` isn't enough).

```XML
<p>This is a paragraph!</p>
<p>This<br>is<br>a<br>paragraph<br>
  with<br>
  multiple<br>
  lines!</p>
```

## Using your browser's tools
If you want to see the HTML Source Code of a certain page, you can right-click and **``View Source (Ctrl+U)``**.  
Also, if you want to see the code of a specific element, you can right-click it and **``Inspect``** or **``Inspect Element``**. This way, you can see how a certain element is defined, its HTML and CSS, and edit them on-the-fly.  
This is a very useful tool for Web Designing, and you'll be using it later!
> **Remember:** When you're editing an element in your browser by "inspecting" it, all the changes you make are temporary. They will disappear once you reload the page, so remember to save your changes in your code!

[Main Menu](../README.md)
