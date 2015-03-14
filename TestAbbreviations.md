**Note**: The Markdown and wiki source shown here might not be displayed
perfectly. Especially code block markers `{{{` and `}}}` are always flushed
left completely. If in doubt, look at the source of this Wiki page or check the
original test files.

Converter command used for this test:

```
$ markowik MDFILE WIKIFILE --mx abbr
```

Markowik revision: [8ee66f314d22](http://code.google.com/p/markowik/source/browse/?r=8ee66f314d22)

# <font color='darkred'>Markdown Source</font> #

```
### Extension Example ###

The HTML specification
is maintained by the W3C.

*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium

### Special Characters ###

The abbreviation extension does not recognize abbreviations with non-ASCII
characters, e.g. FÖÖ. This one works: LOO. And THIS.

*[LÖÖ]: Two bugs in a box
*[LOO]: Two *blind* "bügs in a box"

*[THIS]: Mixing 'single' and "double" quotes

Do you see a need for more tricky tests?
```

# <font color='darkred'>Wiki Source</font> #

```
=== Extension Example ===

The <span title="Hyper Text Markup Language">HTML</span> specification is maintained by the <span title="World Wide Web Consortium">W3C</span>.

=== Special Characters ===

The abbreviation extension does not recognize abbreviations with non-ASCII characters, e.g. FÖÖ. This one works: <span title="Two *blind* ''bügs in a box''">LOO</span>. And <span title="Mixing 'single' and ''double'' quotes">THIS</span>.

Do you see a need for more tricky tests?
```

# <font color='darkred'>Wiki View</font> #

### Extension Example ###

The <span title='Hyper Text Markup Language'>HTML</span> specification is maintained by the <span title='World Wide Web Consortium'>W3C</span>.

### Special Characters ###

The abbreviation extension does not recognize abbreviations with non-ASCII characters, e.g. FÖÖ. This one works: <span title="Two *blind* ''bügs in a box''">LOO</span>. And <span title="Mixing 'single' and ''double'' quotes">THIS</span>.

Do you see a need for more tricky tests?