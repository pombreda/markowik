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
Miscellaneous Tests
-------------------

Here comes a horizontal rule:

------

And here's another one:

***

-   item 1
-   item 2 with a nested ruler

    ---

    Nested paragraph.

-   item 3
```

# <font color='darkred'>Wiki Source</font> #

```
== Miscellaneous Tests ==

Here comes a horizontal rule:

----------

And here's another one:

----------

  * item 1
  * item 2 with a nested ruler
  ----------
  Nested paragraph.
  * item 3
```

# <font color='darkred'>Wiki View</font> #

## Miscellaneous Tests ##

Here comes a horizontal rule:


---


And here's another one:


---


  * item 1
  * item 2 with a nested ruler
> 
---

> Nested paragraph.
  * item 3