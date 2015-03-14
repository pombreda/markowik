**Note**: The Markdown and wiki source shown here might not be displayed
perfectly. Especially code block markers `{{{` and `}}}` are always flushed
left completely. If in doubt, look at the source of this Wiki page or check the
original test files.

Converter command used for this test:

```
$ markowik MDFILE WIKIFILE --image-baseurl http://wiki.markowik.googlecode.com/hg/images/ --html-images
```

Markowik revision: [8ee66f314d22](http://code.google.com/p/markowik/source/browse/?r=8ee66f314d22)

# <font color='darkred'>Markdown Source</font> #

```
![alternative text](http://is.gd/smooley "title text")

![alternative text](monkey.png)

![älternative text][img]

![monkey](monkey.png)
This is an image followed by a *newline* and some text.

This is some text followed by a *newline* and an image
![monkey](monkey.png "monkey")

[img]: smiley.png "title text"
```

# <font color='darkred'>Wiki Source</font> #

```
<img src="http://is.gd/smooley?x=x.png" alt="alternative text" title="title text" />

<img src="http://wiki.markowik.googlecode.com/hg/images/monkey.png" alt="alternative text" />

<img src="http://wiki.markowik.googlecode.com/hg/images/smiley.png" alt="älternative text" title="title text" />

<img src="http://wiki.markowik.googlecode.com/hg/images/monkey.png" alt="monkey" /> This is an image followed by a _newline_ and some text.

This is some text followed by a _newline_ and an image <img src="http://wiki.markowik.googlecode.com/hg/images/monkey.png" alt="monkey" title="monkey" />
```

# <font color='darkred'>Wiki View</font> #

<img src='http://is.gd/smooley?x=x.png' alt='alternative text' title='title text' />

<img src='http://wiki.markowik.googlecode.com/hg/images/monkey.png' alt='alternative text' />

<img src='http://wiki.markowik.googlecode.com/hg/images/smiley.png' alt='älternative text' title='title text' />

<img src='http://wiki.markowik.googlecode.com/hg/images/monkey.png' alt='monkey' /> This is an image followed by a _newline_ and some text.

This is some text followed by a _newline_ and an image <img src='http://wiki.markowik.googlecode.com/hg/images/monkey.png' alt='monkey' title='monkey' />