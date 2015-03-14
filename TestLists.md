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
Let's test lists, nested lists, paragraphs in list items, ...

-   level 1, _item 1_
-   level 1, __item 2__

-   `level 1`, *item 3*
-   level 1, **item 4**
-   **level 1, _item5_**
    -   level 2, item 1
    -   level 2, item 2
        1.  level 3, item 1
        1.  level 3, item 2
-   level 1,
    item 5
-   level 1,
    item 6

    1.  level 2, item 1
    1.  level 2, item 2

            code block
            in level 2, item 2

    paragraph 1 in level 1, item 6

        code block
        in level 1, item 6

    paragraph 2 in level 1, item 6

    paragraph 3 in level 1, item 6

-   level 1, item 7

    paragraph 1 in level 1, item 7

    paragraph 2 in level 1, item 7

Out of list.

1.  level 1, item 1

    paragraph 1 in level 1, item 1

    paragraph 2 in level 1, item 1

1.  level 1, item 2
```

# <font color='darkred'>Wiki Source</font> #

```
Let's test lists, nested lists, paragraphs in list items, ...

  * level 1, _item 1_
  * level 1, *item 2*
  * `level 1`, _item 3_
  * level 1, *item 4*
  * *level 1, _item5_*
    * level 2, item 1
    * level 2, item 2
      # level 3, item 1
      # level 3, item 2
  * level 1, item 5
  * level 1, item 6
    # level 2, item 1
    # level 2, item 2
    {{{
code block
in level 2, item 2
    }}}
  paragraph 1 in level 1, item 6
  {{{
code block
in level 1, item 6
  }}}
  paragraph 2 in level 1, item 6
  <br/>
  paragraph 3 in level 1, item 6
  * level 1, item 7
  paragraph 1 in level 1, item 7
  <br/>
  paragraph 2 in level 1, item 7

Out of list.

  # level 1, item 1
  paragraph 1 in level 1, item 1
  <br/>
  paragraph 2 in level 1, item 1
  # level 1, item 2
```

# <font color='darkred'>Wiki View</font> #

Let's test lists, nested lists, paragraphs in list items, ...

  * level 1, _item 1_
  * level 1, **item 2**
  * `level 1`, _item 3_
  * level 1, **item 4**
  * **level 1, _item5_**
    * level 2, item 1
    * level 2, item 2
      1. level 3, item 1
      1. level 3, item 2
  * level 1, item 5
  * level 1, item 6
    1. level 2, item 1
    1. level 2, item 2
```
code block
in level 2, item 2
```
> paragraph 1 in level 1, item 6
```
code block
in level 1, item 6
```
> paragraph 2 in level 1, item 6
> <br />
> paragraph 3 in level 1, item 6
  * level 1, item 7
> paragraph 1 in level 1, item 7
> <br />
> paragraph 2 in level 1, item 7

Out of list.

  1. level 1, item 1
> paragraph 1 in level 1, item 1
> <br />
> paragraph 2 in level 1, item 1
  1. level 1, item 2