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
[TOC 2]

# A

Testing table of contents.

## A.1

`[TOC X]` markers (with a preceding and subsequent empty line) will be replaced
by `<wiki:toc max_depth="X" />`.

# B

...

## B.1

A depth of 1 is used when X is not given:

[TOC]

### B.1.1

A deep TOC:

[TOC5]
```

# <font color='darkred'>Wiki Source</font> #

```
<wiki:toc max_depth="2" />

= A =

Testing table of contents.

== A.1 ==

`[TOC X]` markers (with a preceding and subsequent empty line) will be replaced by `<wiki:toc max_depth="X" />`.

= B =

...

== B.1 ==

A depth of 1 is used when X is not given:

<wiki:toc max_depth="1" />

=== B.1.1 ===

A deep TOC:

<wiki:toc max_depth="5" />
```

# <font color='darkred'>Wiki View</font> #



# A #

Testing table of contents.

## A.1 ##

`[TOC X]` markers (with a preceding and subsequent empty line) will be replaced by `<wiki:toc max_depth="X" />`.

# B #

...

## B.1 ##

A depth of 1 is used when X is not given:



### B.1.1 ###

A deep TOC:

