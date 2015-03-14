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
Here is a WikiWord which should be escaped.

In links, [WikiWords][1] must not be escaped.

This will end up as an HTML link, i.e. FooBar must be escaped: [Here *is
FooBar*][1]. As in this link: <a href="http://foo.bar">CheckThis</a>.

*WikiWords* may be emphasized.

`A WikiWord in MonoSpace` does not need to be escaped.

All these must be escaped: WikiWord,FooBar:DingDong/HansPeter#BarFoo?HeyHo!DuDa

[1]: http://foo.bar
```

# <font color='darkred'>Wiki Source</font> #

```
Here is a !WikiWord which should be escaped.

In links, [http://foo.bar WikiWords] must not be escaped.

This will end up as an HTML link, i.e. !FooBar must be escaped: <a href="http://foo.bar">Here _is !FooBar_</a>. As in this link: <a href="http://foo.bar">!CheckThis</a>.

_!WikiWords_ may be emphasized.

`A WikiWord in MonoSpace` does not need to be escaped.

All these must be escaped: !WikiWord,!FooBar:!DingDong/!HansPeter#!BarFoo?!HeyHo!!DuDa
```

# <font color='darkred'>Wiki View</font> #

Here is a WikiWord which should be escaped.

In links, [WikiWords](http://foo.bar) must not be escaped.

This will end up as an HTML link, i.e. FooBar must be escaped: <a href='http://foo.bar'>Here <i>is FooBar</i></a>. As in this link: <a href='http://foo.bar'>CheckThis</a>.

_WikiWords_ may be emphasized.

`A WikiWord in MonoSpace` does not need to be escaped.

All these must be escaped: WikiWord,FooBar:DingDong/HansPeter#BarFoo?HeyHo!DuDa