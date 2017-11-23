# Getting Started

## What is HTML?
*What exactly is HTML? And why should I care?*  
**HTML**, Hypertext Markup Language, is the standard markup language for creating **Web Pages** and **Web Applications**. It is usually not considered a programming language but rather (as the name indicates) a markup language, i.e. it describes the structure of a Web Page using **markup**.

*And what is Markup?*  
A **markup language** is a way of annotating a document - this way, the HTML code tells the software (browser) to preform certain actions (make the text smaller, change its color, add a link, etc.) but those instructions are omitted from what the user sees.  
In fact, if you want to see the HTML behind a page like this one you're reading right now, right-click a blank space on the page, and select `View Source` (on most browsers, you could also use `Ctrl + U`). You will see a lot of structured text - this text is interpreted by your browser, and turns into the Web Page that you usually see.

## What are the required tools?
### Text editor
Any text editor will be enough to get started with HTML (*yes, even the simple `notepad`*). But, for the sake of your sanity, we recommend you use a text editor with more extras - like code highlighting or auto-complete.

A few examples are: [Notepad++](https://notepad-plus-plus.org/download/), [Visual Studio Code](https://code.visualstudio.com/), [Brackets](http://brackets.io/), [Atom](http://atom.io/),...  

Install one that seems good for you. You can always install another one later if you don't like your first choice.

### Browser
Once again, every browser is capable of interpreting HTML. That's their job after all.  
We recommend you use **Chrome** or **Firefox**, as they come equipped with tools that will be useful later on.

## Using FEUP's Web Pages
We'll be using the Web Hosting that FEUP has for every member of the community - you can check out yours at [http://fe.up.pt/~login](http://fe.up.pt/~login) (where `login` should be replaced with your username, usually `up201xxxxxx`).  
If you have never edited your page, you should see a **Welcome** page, saying that the owner hasn't created any content. We'll show you how to change that...

### Editing at FEUP's computers
When you're using a computer at FEUP, open the **File Explorer > This PC** and, under **Network Locations**, you should see a network drive with your **username** (if you don't find it, simply try typing `z:` into the adress bar and hitting `Enter`). Inside this network driver, there's a folder named **public_html**, and that's where your Web Page's files are located.

### Editing at home *(or during this workshop)*
When you're at home, you could use an FTP program (like [FileZilla](https://filezilla-project.org/)) to access your files folder remotely. Simply download this program, install it, and use your credentials to log into the server `homes.fe.up.pt`, port `21`.

For more information, go to https://homes.fe.up.pt/

Next, you should find, among others, a folder named **public_html** - that's where your Web Page's files are.  
So far, you only find the **index.html** file, the default page that is shown when somebody opens [http://fe.up.pt/~yourusername](http://fe.up.pt/~yourusername) (you can test this by going to [http://fe.up.pt/~yourusername/index.html](http://fe.up.pt/~yourusername/index.html) - you'll notice that it is the exact same page).  

We'll be creating **index.html** from scratch, so just change this one's name to **old.html**.  
After renaming the file, try accessing your page again. You should see an error message.

Now open your text editor, and save an empty document (anywhere you'd like) with the name **index.html**.  
Drag this file to the **public_html** folder in Filezilla, refresh your browser, and the error message should disappear.

**If you need any help, call a monitor!**

[Main Menu](../README.md)
