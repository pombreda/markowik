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
A plain image link: [![smiley](smiley.png "foo")](http://tango.freedesktop.org/).

A link with text and image: [smile ![smiley](smiley.png
"foo")](http://tango.freedesktop.org/).

A link with text and image: [smile ![smiley][img]](http://tango.freedesktop.org/).

[img]: smiley.png "title täxt"
```

# <font color='darkred'>Wiki Source</font> #

```
A plain image link: <a href="http://tango.freedesktop.org/"><img src="http://wiki.markowik.googlecode.com/hg/images/smiley.png" alt="smiley" title="foo" /></a>.

A link with text and image: <a href="http://tango.freedesktop.org/">smile <img src="http://wiki.markowik.googlecode.com/hg/images/smiley.png" alt="smiley" title="foo" /></a>.

A link with text and image: <a href="http://tango.freedesktop.org/">smile <img src="http://wiki.markowik.googlecode.com/hg/images/smiley.png" alt="smiley" title="title täxt" /></a>.
```

# <font color='darkred'>Wiki View</font> #

A plain image link: <a href='http://tango.freedesktop.org/'><img src='http://wiki.markowik.googlecode.com/hg/images/smiley.png' alt='smiley' title='foo' /></a>.

A link with text and image: <a href='http://tango.freedesktop.org/'>smile <img src='http://wiki.markowik.googlecode.com/hg/images/smiley.png' alt='smiley' title='foo' /></a>.

A link with text and image: <a href='http://tango.freedesktop.org/'>smile <img src='http://wiki.markowik.googlecode.com/hg/images/smiley.png' alt='smiley' title='title täxt' /></a>.