**Note**: The Markdown and wiki source shown here might not be displayed
perfectly. Especially code block markers `{{{` and `}}}` are always flushed
left completely. If in doubt, look at the source of this Wiki page or check the
original test files.

Converter command used for this test:

```
$ markowik MDFILE WIKIFILE --mx def_list
```

Markowik revision: [8ee66f314d22](http://code.google.com/p/markowik/source/browse/?r=8ee66f314d22)

# <font color='darkred'>Markdown Source</font> #

```
### Simple Definitions ###

This example is from the extension's documentation:

Apple
:   Pomaceous fruit of plants of the genus Malus in 
    the family Rosaceae.

Orange
:   The fruit of an evergreen tree of the genus Citrus.

### Alternative Formats ###

item 1 with two descriptions
:   desc 1.1
:   desc 1.2

item 2
item 3
:   description for two items (2 and 3)

This stops the definition list. It's is a new paragraph.

item 1

:   This description has its own paragraph.

item 2

:   This description has

    two paragraphs.

item 3
:   Another description with

    two paragraphs.

### Nested Definition Lists ###

-   item 1
-   item 2 with a definition list

    Markdown
    :   This is markdown.
        Yes, it is.
    reST
    :   This is *something different*. Read [this][1].
    
    Foo
    :   This still belongs to the same definition list.

    Just want to add another paragraph to item 2.

-   item 3 with paragraphed definition lists

    item 3.1
    :   desc 3.1
    
        This is supposed to be a paragraph of desc 3.1 but it ends up as a code
        
        block in item 3.1.
    :   A second description for item 3.1.
    
    item 3.2
    
    :   desc 3.2 (only one line, but a paragraph nevertheless)
    
    item 3.3
    
    :   desc 3.3.1
    
        This will be a code block in item 3.3 (not a paragraph of desc 3.3.1).
        
    :   desc 3.3.2
    
       This breaks the definition list and is a paragraph in item 3.

Got it? Descriptions of nested definition lists cannot have multiple
paragraphs.

[1]: http://docutils.sourceforge.net/rst.html
```

# <font color='darkred'>Wiki Source</font> #

```
=== Simple Definitions ===

This example is from the extension's documentation:

<dl>
<dt>Apple</dt>
<dd>Pomaceous fruit of plants of the genus Malus in the family Rosaceae.</dd>
<dt>Orange</dt>
<dd>The fruit of an evergreen tree of the genus Citrus.</dd>
</dl>

=== Alternative Formats ===

<dl>
<dt>item 1 with two descriptions</dt>
<dd>desc 1.1</dd>
<dd>desc 1.2</dd>
<dt>item 2</dt>
<dt>item 3</dt>
<dd>description for two items (2 and 3)</dd>
</dl>

This stops the definition list. It's is a new paragraph.

<dl>
<dt>item 1</dt>
<dd>This description has its own paragraph.</dd>
<dt>item 2</dt>
<dd>This description has

two paragraphs.</dd>
<dt>item 3</dt>
<dd>Another description with

two paragraphs.</dd>
</dl>

=== Nested Definition Lists ===

  * item 1
  * item 2 with a definition list
  <dl>
  <dt>Markdown</dt>
  <dd>This is markdown. Yes, it is.</dd>
  <dt>reST</dt>
  <dd>This is _something different_. Read [http://docutils.sourceforge.net/rst.html this].</dd>
  <dt>Foo</dt>
  <dd>This still belongs to the same definition list.</dd>
  </dl>
  Just want to add another paragraph to item 2.
  * item 3 with paragraphed definition lists
  <dl>
  <dt>item 3.1</dt>
  <dd>desc 3.1</dd>
  </dl>
  {{{
This is supposed to be a paragraph of desc 3.1 but it ends up as a code

block in item 3.1.
  }}}
  <dl>
  <dd>A second description for item 3.1.</dd>
  <dt>item 3.2</dt>
  <dd>desc 3.2 (only one line, but a paragraph nevertheless)</dd>
  <dt>item 3.3</dt>
  <dd>desc 3.3.1</dd>
  </dl>
  {{{
This will be a code block in item 3.3 (not a paragraph of desc 3.3.1).
  }}}
  <dl>
  <dd>desc 3.3.2</dd>
  </dl>
  This breaks the definition list and is a paragraph in item 3.

Got it? Descriptions of nested definition lists cannot have multiple paragraphs.
```

# <font color='darkred'>Wiki View</font> #

### Simple Definitions ###

This example is from the extension's documentation:

<dl>
<dt>Apple</dt>
<dd>Pomaceous fruit of plants of the genus Malus in the family Rosaceae.</dd>
<dt>Orange</dt>
<dd>The fruit of an evergreen tree of the genus Citrus.</dd>
</dl>

### Alternative Formats ###

<dl>
<dt>item 1 with two descriptions</dt>
<dd>desc 1.1</dd>
<dd>desc 1.2</dd>
<dt>item 2</dt>
<dt>item 3</dt>
<dd>description for two items (2 and 3)</dd>
</dl>

This stops the definition list. It's is a new paragraph.

<dl>
<dt>item 1</dt>
<dd>This description has its own paragraph.</dd>
<dt>item 2</dt>
<dd>This description has<br>
<br>
two paragraphs.</dd>
<dt>item 3</dt>
<dd>Another description with<br>
<br>
two paragraphs.</dd>
</dl>

### Nested Definition Lists ###

  * item 1
  * item 2 with a definition list
> <dl>
<blockquote><dt>Markdown</dt>
<dd>This is markdown. Yes, it is.</dd>
<dt>reST</dt>
<dd>This is <i>something different</i>. Read <a href='http://docutils.sourceforge.net/rst.html'>this</a>.</dd>
<dt>Foo</dt>
<dd>This still belongs to the same definition list.</dd>
</dl>
Just want to add another paragraph to item 2.<br>
</blockquote>  * item 3 with paragraphed definition lists
> <dl>
<blockquote><dt>item 3.1</dt>
<dd>desc 3.1</dd>
</dl>
<pre><code>This is supposed to be a paragraph of desc 3.1 but it ends up as a code<br>
<br>
block in item 3.1.<br>
</code></pre>
<dl>
<dd>A second description for item 3.1.</dd>
<dt>item 3.2</dt>
<dd>desc 3.2 (only one line, but a paragraph nevertheless)</dd>
<dt>item 3.3</dt>
<dd>desc 3.3.1</dd>
</dl>
<pre><code>This will be a code block in item 3.3 (not a paragraph of desc 3.3.1).<br>
</code></pre>
<dl>
<dd>desc 3.3.2</dd>
</dl>
This breaks the definition list and is a paragraph in item 3.</blockquote>

Got it? Descriptions of nested definition lists cannot have multiple paragraphs.