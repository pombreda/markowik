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
### Simple ###

Let's check some *markup*. This is `monospace`. Here are `several monospace
words`. What about *emphasized* and _emphasized_ and **bold** and __bold__?

Nested *markups **are** also **possible***.

    Markups *do not*
    apply in `code blocks`...

... nor in `monospace *text* parts`. Though, *emphasized `monospace` is
possible*.

### Empty lines and whitespace in verbatim environments ###

Repeating `whitespace  in  monospace` is not preserved as GCW ignores them.
This also applies when `monospace
   crosses multiples lines`.

    Empty lines in code blocks should be preserved.


    But PyMD compresses them to *one* empty line.

### Typefacing at Linebreaks ###

Here
*is FooBar*

*Here*
is FooBar

*Here
**is FooBar***.
```

# <font color='darkred'>Wiki Source</font> #

```
=== Simple ===

Let's check some _markup_. This is `monospace`. Here are `several monospace words`. What about _emphasized_ and _emphasized_ and *bold* and *bold*?

Nested _markups *are* also *possible*_.

{{{
Markups *do not*
apply in `code blocks`...
}}}

... nor in `monospace *text* parts`. Though, _emphasized `monospace` is possible_.

=== Empty lines and whitespace in verbatim environments ===

Repeating `whitespace in monospace` is not preserved as GCW ignores them. This also applies when `monospace crosses multiples lines`.

{{{
Empty lines in code blocks should be preserved.

But PyMD compresses them to *one* empty line.
}}}

=== Typefacing at Linebreaks ===

Here _is !FooBar_

_Here_ is !FooBar

_Here *is !FooBar*_.
```

# <font color='darkred'>Wiki View</font> #

### Simple ###

Let's check some _markup_. This is `monospace`. Here are `several monospace words`. What about _emphasized_ and _emphasized_ and **bold** and **bold**?

Nested _markups **are** also **possible**_.

```
Markups *do not*
apply in `code blocks`...
```

... nor in `monospace *text* parts`. Though, _emphasized `monospace` is possible_.

### Empty lines and whitespace in verbatim environments ###

Repeating `whitespace in monospace` is not preserved as GCW ignores them. This also applies when `monospace crosses multiples lines`.

```
Empty lines in code blocks should be preserved.

But PyMD compresses them to *one* empty line.
```

### Typefacing at Linebreaks ###

Here _is FooBar_

_Here_ is FooBar

_Here **is FooBar**_.