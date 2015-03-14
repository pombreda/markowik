**Note**: The Markdown and wiki source shown here might not be displayed
perfectly. Especially code block markers `{{{` and `}}}` are always flushed
left completely. If in doubt, look at the source of this Wiki page or check the
original test files.

Converter command used for this test:

```
$ markowik MDFILE WIKIFILE 
```

Markowik revision: [8ee66f314d22](http://code.google.com/p/markowik/source/browse/?r=8ee66f314d22)

# <font color='darkred'>Markdown Source</font> #

```
Detecting and appending image file type extensions: 

![x](http://is.gd/smooley)

![x](http://is.gd/smooley?x=x.svg)

![x](http://is.gd/smooley?x=x.jpg)

![x](http://is.gd/smooley?x=x.jpeg)

![x](http://is.gd/smooley?x=x.foo)
```

# <font color='darkred'>Wiki Source</font> #

```
Detecting and appending image file type extensions: 

http://is.gd/smooley?x=x.png

http://is.gd/smooley?x=x.svg

http://is.gd/smooley?x=x.jpg

http://is.gd/smooley?x=x.jpeg

http://is.gd/smooley?x=x.foo&x=x.png
```

# <font color='darkred'>Wiki View</font> #

Detecting and appending image file type extensions:

![http://is.gd/smooley?x=x.png](http://is.gd/smooley?x=x.png)

![http://is.gd/smooley?x=x.svg](http://is.gd/smooley?x=x.svg)

![http://is.gd/smooley?x=x.jpg](http://is.gd/smooley?x=x.jpg)

![http://is.gd/smooley?x=x.jpeg](http://is.gd/smooley?x=x.jpeg)

![http://is.gd/smooley?x=x.foo&x=x.png](http://is.gd/smooley?x=x.foo&x=x.png)