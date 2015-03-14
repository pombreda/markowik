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
> here is
> a blockquote

Another one:

> here is
> a blockquote
>
> consisting of several paragraphs

In a list:

-   item 1
-   item 1

    -   item 2.1
    -   item 2.2 with
        a blockquote

        > This is a blockquote within list item 2.2.
        >
        > It contains multiple paragraphs.

    -   item 2.3

-   item 3

    > A blockquote in
    > item 3

    Followed by paragraph.

-   item 4

That's it.
```

# <font color='darkred'>Wiki Source</font> #

```
  here is a blockquote

Another one:

  here is a blockquote
  <br/>
  consisting of several paragraphs

In a list:

  * item 1
  * item 1
    * item 2.1
    * item 2.2 with a blockquote
      This is a blockquote within list item 2.2.
      <br/>
      It contains multiple paragraphs.
    * item 2.3
  * item 3
    A blockquote in item 3
  Followed by paragraph.
  * item 4

That's it.
```

# <font color='darkred'>Wiki View</font> #

> here is a blockquote

Another one:

> here is a blockquote
> <br />
> consisting of several paragraphs

In a list:

  * item 1
  * item 1
    * item 2.1
    * item 2.2 with a blockquote
> > > This is a blockquote within list item 2.2.
> > > <br />
> > > It contains multiple paragraphs.
    * item 2.3
  * item 3

> > A blockquote in item 3

> Followed by paragraph.
  * item 4

That's it.