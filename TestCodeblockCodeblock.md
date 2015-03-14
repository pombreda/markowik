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
Testing code blocks which contain GCW code block markers.

    Code
    {{{
    Block
    }}}

Nested in a list:

-   item with a nested code block

        Code
        {{{
            Block
        }}}

-   Tough nested, it's content must get dedented completely to look nice in GCW.
```

# <font color='darkred'>Wiki Source</font> #

```
Testing code blocks which contain GCW code block markers.

{{{
Code
{{{
Block
}}}
}}}

Nested in a list:

  * item with a nested code block
  {{{
Code
{{{
    Block
}}}
  }}}
  * Tough nested, it's content must get dedented completely to look nice in GCW.
```

# <font color='darkred'>Wiki View</font> #

Testing code blocks which contain GCW code block markers.

```
Code
{{{
Block
}}}
```

Nested in a list:

  * item with a nested code block
```
Code
{{{
    Block
}}}
```
  * Tough nested, it's content must get dedented completely to look nice in GCW.