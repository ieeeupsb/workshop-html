# My "final" Web Page!
Now we know (almost) everything we need to create our Web Page.
We'll do it step by step, introducing some new concepts along the way...

## Adding structure
We should start by making the HTML document, and adding the HTML document structure...
```XML
<!DOCTYPE html>
<html>
<head>
  <title>My Name - Home Page</title>
</head>

<body>

</body>
</html>
```

So far, our body is empty, and our head has nothing related to styling. Let's work on that.  
To do that, let's take a look at the **typical Web Page structure**, which looks a little like a **magazine** or **newspapper**:

![HTML5 Structure](http://www.freshnigeriajobs.com/wp-content/uploads/2016/10/HTML5.jpg)  

These are new elements to help you with your layout:
 - **``<header>``** defines a header for a document or a section
 - **``<nav>``** is a container for navigation links
 - **``<section>``** is a section in the document
 - **``<aside>``** defines content aside from the content (like a sidebar)
 - **``<footer>``** is for a footer for a document or a section

We'll add these elements to our **body**:
```XML
  <header>
  </header>

  <nav>
  </nav>

  <section>
  </section>

  <section>
  </section>

  <section>
  </section>

  <section>
  </section>

  <footer>
  </footer>
```
> **Comments in HTML** are added like this: **``<!-- THIS IS A COMMENT -->``**  
> Keep that it mind, as it might be useful to keep your content organized.

We added **4 sections** - **About me**, **Experience**, **Education** and **Contact me**. We should find a way of distinguishing them, so we'll use **Classes** and **IDs**.

### Classes & IDs
A **``class``** is an attribute where you can specify one or multiple class names to a certain element.  
Then, with CSS, you can preform certain actions to **all the elements of the same class**.

An **``id``** specifies a unique name for an element. You can use this to scroll to a certain part of the page (where that element is), or to preform certain actions to **one specific element**.

```XML
<style>
.city {
  background-color: DodgerBlue;
  color: white;
  padding: 10px;
} 
#porto {
  color: black;
}
</style>

<p class="city portugal">Lisbon</p>
<p class="city portugal" id="porto">Porto</p>
<p class="city spain">Madrid</p>
```




[Main Menu](../README.md)
