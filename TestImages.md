**Note**: The Markdown and wiki source shown here might not be displayed
perfectly. Especially code block markers `{{{` and `}}}` are always flushed
left completely. If in doubt, look at the source of this Wiki page or check the
original test files.

Converter command used for this test:

```
$ markowik MDFILE WIKIFILE --image-baseurl http://wiki.markowik.googlecode.com/hg/images/
```

Markowik revision: [8ee66f314d22](http://code.google.com/p/markowik/source/browse/?r=8ee66f314d22)

# <font color='darkred'>Markdown Source</font> #

```
### Isloated Images ###

![Lost in GCW](http://is.gd/smooley)

![Lost in GCW](monkey.png "title also lost in GCW")

![Lost in GCW][img]

[img]: smiley.png "this title is lost in GCW"

### Relative and Absolute Image URLs ###

- absolute ![foo](http://is.gd/smooley)

- absolute ![foo](https://thereisnoimageat.this/location.png)

- absolute ![foo](ftp://thereisnoimageat.this/location.png)

- relative ![foo](smiley.png)

### In Text and Lists ###

This sentence has a ![monkey](monkey.png) inside.

-   item 1
-   item 2 has a nested image:

    ![alt][img]

-   item 3 has two nested images:

    ![alt][img]

    ![alt][img]

-   item 4

![monkey](monkey.png "monkey")
says hello.

Look, a
![monkey](monkey.png "monkey")

### In Links ###

A plain image link: [![smiley](smiley.png "foo")](http://tango.freedesktop.org/).

A link with [text and ![smiley](smiley.png
"foo")](http://tango.freedesktop.org/).
```

# <font color='darkred'>Wiki Source</font> #

```
=== Isloated Images ===

http://is.gd/smooley?x=x.png

http://wiki.markowik.googlecode.com/hg/images/monkey.png

http://wiki.markowik.googlecode.com/hg/images/smiley.png

=== Relative and Absolute Image URLs ===

  * absolute http://is.gd/smooley?x=x.png
  * absolute https://thereisnoimageat.this/location.png
  * absolute ftp://thereisnoimageat.this/location.png
  * relative http://wiki.markowik.googlecode.com/hg/images/smiley.png

=== In Text and Lists ===

This sentence has a http://wiki.markowik.googlecode.com/hg/images/monkey.png inside.

  * item 1
  * item 2 has a nested image:
  http://wiki.markowik.googlecode.com/hg/images/smiley.png
  * item 3 has two nested images:
  http://wiki.markowik.googlecode.com/hg/images/smiley.png
  <br/>
  http://wiki.markowik.googlecode.com/hg/images/smiley.png
  * item 4

http://wiki.markowik.googlecode.com/hg/images/monkey.png says hello.

Look, a http://wiki.markowik.googlecode.com/hg/images/monkey.png

=== In Links ===

A plain image link: [http://tango.freedesktop.org/ http://wiki.markowik.googlecode.com/hg/images/smiley.png]

A link with <a href="http://tango.freedesktop.org/">text and http://wiki.markowik.googlecode.com/hg/images/smiley.png</a>.
```

# <font color='darkred'>Wiki View</font> #

### Isloated Images ###

![http://is.gd/smooley?x=x.png](http://is.gd/smooley?x=x.png)

![http://wiki.markowik.googlecode.com/hg/images/monkey.png](http://wiki.markowik.googlecode.com/hg/images/monkey.png)

![http://wiki.markowik.googlecode.com/hg/images/smiley.png](http://wiki.markowik.googlecode.com/hg/images/smiley.png)

### Relative and Absolute Image URLs ###

  * absolute ![http://is.gd/smooley?x=x.png](http://is.gd/smooley?x=x.png)
  * absolute ![https://thereisnoimageat.this/location.png](https://thereisnoimageat.this/location.png)
  * absolute ![ftp://thereisnoimageat.this/location.png](ftp://thereisnoimageat.this/location.png)
  * relative ![http://wiki.markowik.googlecode.com/hg/images/smiley.png](http://wiki.markowik.googlecode.com/hg/images/smiley.png)

### In Text and Lists ###

This sentence has a ![http://wiki.markowik.googlecode.com/hg/images/monkey.png](http://wiki.markowik.googlecode.com/hg/images/monkey.png) inside.

  * item 1
  * item 2 has a nested image:
> ![http://wiki.markowik.googlecode.com/hg/images/smiley.png](http://wiki.markowik.googlecode.com/hg/images/smiley.png)
  * item 3 has two nested images:
> ![http://wiki.markowik.googlecode.com/hg/images/smiley.png](http://wiki.markowik.googlecode.com/hg/images/smiley.png)
> <br />
> ![http://wiki.markowik.googlecode.com/hg/images/smiley.png](http://wiki.markowik.googlecode.com/hg/images/smiley.png)
  * item 4

![http://wiki.markowik.googlecode.com/hg/images/monkey.png](http://wiki.markowik.googlecode.com/hg/images/monkey.png) says hello.

Look, a ![http://wiki.markowik.googlecode.com/hg/images/monkey.png](http://wiki.markowik.googlecode.com/hg/images/monkey.png)

### In Links ###

A plain image link: [![](http://wiki.markowik.googlecode.com/hg/images/smiley.png)](http://tango.freedesktop.org/)

A link with <a href='http://tango.freedesktop.org/'>text and <img src='http://wiki.markowik.googlecode.com/hg/images/smiley.png' /></a>.