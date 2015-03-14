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

Here is <a href="http://www.python.org">an HTML *link*</a>.

This is <em>emphasized</em> as is *this*. Why would you want double
<em>*emphasizing*</em>?

Image: <img src="http://wiki.markowik.googlecode.com/hg/images/smiley.png" alt="Smiley"/>

In GCW this should be [an <em>HTML</em> link](http://foo.bar).

*Raw <b>bold</b> formatting within emphasized text.*

Raw HTML tags are not processed (except the content of span-level tags). This
means tags not supported in GCW nevertheless appear in the converted text, e.g.
<abbr title="Foo">*Bar*</abbr>.

### Linebreaks ###

<b>An HTML span-level tag after an empty line</b> followed by some text on the
same and a new line.

<b>An HTML span-level tag after an empty line</b>
followed by some text on a new line

An HTML <b>span-level tag followed by</b>
text on a new line.

Some text followed by
<b>an HTML span-level tag on a new line.</b>

Some text followed by
<b>an HTML span-level tag</b> on a newline.

Some text and an
<img src="http://wiki.markowik.googlecode.com/hg/images/smiley.png" />
HTML image.

### Blocks ###

<p>
This is a HTML paragraph

with an empty line.
</p>

<blockquote>
This is
a blockquote
</blockquote>

<pre>
verbatim
  text
</pre>

Blocks are easy.

### Tables ###

<table>
<tr>
<th>COL1</th>
<th align="right">COL2</th>
</tr>
<tr>
<td>CELL 1.1</td>
<td>CELL 2.1</td>
</tr>
<tr>
<td>CELL 1.2</td>
<td>*CELL* 2.2</td>
</tr>
</table>

From <http://daringfireball.net/projects/markdown/syntax#html>:

>   Note that Markdown formatting syntax is not processed within block-level
>   HTML tags. E.g., you can’t use Markdown-style *emphasis* inside an HTML
>   block.

This means markdown formatting in HTML tables end up literally in GCW where it
might have unexpected effects.

### Nested Tables ###

Forget it. From <http://daringfireball.net/projects/markdown/syntax#html>:

>   The only restrictions are that block-level HTML elements — e.g. `<div>`,
>   `<table>`, `<pre>`, `<p>`, etc. — must be separated from surrounding
>   content by blank lines, and **the start and end tags of the block should
>   not be indented with tabs or spaces**.
```

# <font color='darkred'>Wiki Source</font> #

```
=== Simple ===

Here is <a href="http://www.python.org">an HTML _link_</a>.

This is <em>emphasized</em> as is _this_. Why would you want double <em>_emphasizing_</em>?

Image: <img src="http://wiki.markowik.googlecode.com/hg/images/smiley.png" alt="Smiley"/>

In GCW this should be <a href="http://foo.bar">an <em>HTML</em> link</a>.

_Raw <b>bold</b> formatting within emphasized text._

Raw HTML tags are not processed (except the content of span-level tags). This means tags not supported in GCW nevertheless appear in the converted text, e.g. <abbr title="Foo">_Bar_</abbr>.

=== Linebreaks ===

<b>An HTML span-level tag after an empty line</b> followed by some text on the same and a new line.

<b>An HTML span-level tag after an empty line</b> followed by some text on a new line

An HTML <b>span-level tag followed by</b> text on a new line.

Some text followed by <b>an HTML span-level tag on a new line.</b>

Some text followed by <b>an HTML span-level tag</b> on a newline.

Some text and an <img src="http://wiki.markowik.googlecode.com/hg/images/smiley.png" /> HTML image.

=== Blocks ===

<p>
This is a HTML paragraph

with an empty line.
</p>

<blockquote>
This is
a blockquote
</blockquote>

<pre>
verbatim
  text
</pre>

Blocks are easy.

=== Tables ===

<table>
<tr>
<th>COL1</th>
<th align="right">COL2</th>
</tr>
<tr>
<td>CELL 1.1</td>
<td>CELL 2.1</td>
</tr>
<tr>
<td>CELL 1.2</td>
<td>*CELL* 2.2</td>
</tr>
</table>

From [http://daringfireball.net/projects/markdown/syntax#html http://daringfireball.net/projects/markdown/syntax#html]:

  Note that Markdown formatting syntax is not processed within block-level HTML tags. E.g., you can’t use Markdown-style _emphasis_ inside an HTML block.

This means markdown formatting in HTML tables end up literally in GCW where it might have unexpected effects.

=== Nested Tables ===

Forget it. From [http://daringfireball.net/projects/markdown/syntax#html http://daringfireball.net/projects/markdown/syntax#html]:

  The only restrictions are that block-level HTML elements — e.g. `<div>`, `<table>`, `<pre>`, `<p>`, etc. — must be separated from surrounding content by blank lines, and *the start and end tags of the block should not be indented with tabs or spaces*.
```

# <font color='darkred'>Wiki View</font> #

### Simple ###

Here is <a href='http://www.python.org'>an HTML <i>link</i></a>.

This is <em>emphasized</em> as is _this_. Why would you want double <em><i>emphasizing</i></em>?

Image: <img src='http://wiki.markowik.googlecode.com/hg/images/smiley.png' alt='Smiley' />

In GCW this should be <a href='http://foo.bar'>an <em>HTML</em> link</a>.

_Raw_<b>bold</b> formatting within emphasized text.

Raw HTML tags are not processed (except the content of span-level tags). This means tags not supported in GCW nevertheless appear in the converted text, e.g. 

&lt;abbr title="Foo"&gt;

_Bar_

&lt;/abbr&gt;

.

### Linebreaks ###

<b>An HTML span-level tag after an empty line</b> followed by some text on the same and a new line.

<b>An HTML span-level tag after an empty line</b> followed by some text on a new line

An HTML <b>span-level tag followed by</b> text on a new line.

Some text followed by <b>an HTML span-level tag on a new line.</b>

Some text followed by <b>an HTML span-level tag</b> on a newline.

Some text and an <img src='http://wiki.markowik.googlecode.com/hg/images/smiley.png' /> HTML image.

### Blocks ###

<p>
This is a HTML paragraph<br>
<br>
with an empty line.<br>
</p>

<blockquote>
This is<br>
a blockquote<br>
</blockquote>

<pre>
verbatim<br>
text<br>
</pre>

Blocks are easy.

### Tables ###

<table>
<tr>
<th>COL1</th>
<th align='right'>COL2</th>
</tr>
<tr>
<td>CELL 1.1</td>
<td>CELL 2.1</td>
</tr>
<tr>
<td>CELL 1.2</td>
<td><b>CELL</b> 2.2</td>
</tr>
</table>

From [http://daringfireball.net/projects/markdown/syntax#html](http://daringfireball.net/projects/markdown/syntax#html):

> Note that Markdown formatting syntax is not processed within block-level HTML tags. E.g., you can’t use Markdown-style _emphasis_ inside an HTML block.

This means markdown formatting in HTML tables end up literally in GCW where it might have unexpected effects.

### Nested Tables ###

Forget it. From [http://daringfireball.net/projects/markdown/syntax#html](http://daringfireball.net/projects/markdown/syntax#html):

> The only restrictions are that block-level HTML elements — e.g. `<div>`, `<table>`, `<pre>`, `<p>`, etc. — must be separated from surrounding content by blank lines, and **the start and end tags of the block should not be indented with tabs or spaces**.