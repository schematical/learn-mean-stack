###Step 1 - Setting up:

Open a text editor on your computer. You can use the default but I recommend one of the following:

* [Notepad++](http://notepad-plus-plus.org/)
* [Sublime](http://www.sublimetext.com/)

_NOTE: I use [WebStorm](https://www.jetbrains.com/webstorm/?ref=shiporgetoffthepot.com) but that is a bit advanced for this early in the learning process_

On your desktop create a file called **index.html**

Copy and paste the following into **index.html**

```
<html>
   <head>
       <title>My test web app</title>

   </head>
   <body>
       <h1>Hello World</h1>
   </body>
</html>
```

Save the file then open the file in your browser of choice.

_I strongly recomend [Chrome](http://www.google.com/chrome/)_

####What is HTML:
A long time ago when the internet was first starting out and no one ever dreamed we would have fancy realtime updating applications like Facebook, Youtube, and Twitter developers just wanted a way to create and share documents through the browser.

They took an existing language [XML or EXtensible Markup Language](http://www.w3schools.com/xml/
) and created a specialized version of it to run in these ne# learn-mean-stackw things called browsers. That specialized form of XML was [HTML or Hypertext Markup Language](http://www.w3schools.com/html/).

#####XML:
XML is merely a syntax. Computers are not incredibly smart so you have to give it very specific directions.

I would NOT bother to go through the tutorials on W3 but I would make it a point to understand how XML works.



#####HTML:

There is acuatlly a pretty good graphic of how HTML is pretty much laid out from a programatical standpoint later on in the [Document Object Model Section](http://www.w3schools.com/js/js_htmldom.asp)


The DOM - A living breathing thing
HTML is just a blueprint


####Notes on "paths":

Say for example you are editing the following web page: `http://mywebsite.com/dir1/dir2/page.html`

`<img src="image.jpg">` Would open `http://mywebsite.com/dir1/dir2/page.html`

`<img src="/image.jpg">` Would open `http://mywebsite.com/page.html`

`<img src="/dir3/image.jpg">` Would open `http://mywebsite.com/dir3/page.html`

`<img src="http://otherwebiste.com/image.jpg">` Would open `http://otherwebiste.com/image.jpg`

Now assuming you are on an https `<img src="//otherwebiste.com/image.jpg">` Would open `https//otherwebiste.com/image.jpg` . It will look at the protocol that the currently loaded web page is on and use that.