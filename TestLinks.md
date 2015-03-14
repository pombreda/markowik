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
A plain link <http://www.google.com> and  a [named link](http://python.org).

An link with typefacing: [the *link*](http://foo.bar) (converts to an HTML
link).

A link after a linebreak:
[the link](http://foo.bar).

A typefaced (i.e. HTML) link after a linebreak:
[the *link*](http://foo.bar).

Links in a list:

-   a [named link using a ref][ref]
-   the same *[link][ref] empahsized*
-   and with nested typefacing: [the `link`][ref] or [the *link*][ref] (both
    end up as HTML links)
-   a link after a linebreak:
    [the link](http://foo.bar)
-   a typefaced (i.e. HTML) link after a linebreak:
    [the *link*](http://foo.bar)

[ref]: http://xkcd.com/
```

# <font color='darkred'>Wiki Source</font> #

```
A plain link [http://www.google.com http://www.google.com] and a [http://python.org named link].

An link with typefacing: <a href="http://foo.bar">the _link_</a> (converts to an HTML link).

A link after a linebreak: [http://foo.bar the link].

A typefaced (i.e. HTML) link after a linebreak: <a href="http://foo.bar">the _link_</a>.

Links in a list:

  * a [http://xkcd.com/ named link using a ref]
  * the same _[http://xkcd.com/ link] empahsized_
  * and with nested typefacing: <a href="http://xkcd.com/">the `link`</a> or <a href="http://xkcd.com/">the _link_</a> (both end up as HTML links)
  * a link after a linebreak: [http://foo.bar the link]
  * a typefaced (i.e. HTML) link after a linebreak: <a href="http://foo.bar">the _link_</a>
```

# <font color='darkred'>Wiki View</font> #

A plain link [http://www.google.com](http://www.google.com) and a [named link](http://python.org).

An link with typefacing: <a href='http://foo.bar'>the <i>link</i></a> (converts to an HTML link).

A link after a linebreak: [the link](http://foo.bar).

A typefaced (i.e. HTML) link after a linebreak: <a href='http://foo.bar'>the <i>link</i></a>.

Links in a list:

  * a [named link using a ref](http://xkcd.com/)
  * the same _[link](http://xkcd.com/) empahsized_
  * and with nested typefacing: <a href='http://xkcd.com/'>the <code>link</code></a> or <a href='http://xkcd.com/'>the <i>link</i></a> (both end up as HTML links)
  * a link after a linebreak: [the link](http://foo.bar)
  * a typefaced (i.e. HTML) link after a linebreak: <a href='http://foo.bar'>the <i>link</i></a>