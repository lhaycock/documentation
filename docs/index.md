---
title: Markdown Tips
---



<a href="{{site.baseurl}}/Markdown.zip" download="Markdown.zip" target="_blank" >Download Markdown File</a> 

Open this in <a href="https://typora.io/" target="_blank">Typora</a>

This is where you can see what the markdown looks like and can toggle back and forth between markdown and code by using Ctrl + /

Add --- then hit enter- this is where front matter goes, for example the "title: ", which is case sensitive and needs a :  

You can also add weights if you would like the pages to show up in the sidebar in a certain order- 1 being first, etc:

weight: 1

### Headers

# Header

## Header

### Header

#### Header

##### Header

###You need to add a space after the #  #

### Adding Emphasis

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

### Creating Links

Use [ ] for text of the link, what people will see, ( ) for the actual link

[What you want to say here](url goes here)

[Go to Google!](https://www.google.com/)
[et-al page](http://etal.joewheaton.org/)

### Posting pictures

! [Image name goes here] (filepath of where the image is)

![JoeBridgeCreek]({{ site.baseurl }}/assets/images/JoeBridgeCreek.png)

If you want your image to have text appear other than the image name you can add " " after the file path and that will be what shows up when people hover over the image:

![JoeBridgeCreek]({{ site.baseurl }}/assets/images/JoeBridgeCreek.png "Here's Joe!")

The filepath of the image needs to be in the docs/assets/images folder in the repository you are working in on github.  If these don't exist you need to create them.  {{ site.baseurl }} references the docs folder in the repository you are in- pyBRAT, RCAT, etc.  The filepath is critical.

### Code

If you want to show code add ` around the code:

`print: "Hello World."`

### Videos

If you want to embed a youtube video (or Google Map or something else), you can go click on the share and then embed buttons, then copy the code and paste it:

<iframe width="560" height="315" src="https://www.youtube.com/embed/tgkB46xeQts" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>



[Here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#headers) is a markdown cheatsheet that has more information if you are looking for more.

