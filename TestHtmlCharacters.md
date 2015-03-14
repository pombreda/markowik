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
HTML special characters: < & > %

In a code block:

    < & > %

    &amp;

This &amp; becomes &, while this `&amp;` won't change. Does anyone see a
problem here?
```

# <font color='darkred'>Wiki Source</font> #

```
HTML special characters: < & > %

In a code block:

{{{
< & > %

&amp;
}}}

This & becomes &, while this `&amp;` won't change. Does anyone see a problem here?
```

# <font color='darkred'>Wiki View</font> #

HTML special characters: < & > %

In a code block:

```
< & > %

&amp;
```

This & becomes &, while this `&amp;` won't change. Does anyone see a problem here?