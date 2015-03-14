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
Some more sophisticated links:

- this is [@link][1]
- another [&link][1]
- take [this \`link][1]
- another [{{{link}}}][1]
- [foo \] link][1]
- [an *emphasized \** \_nightmare][1]

[1]: http://daringfireball.net/projects/markdown
```

# <font color='darkred'>Wiki Source</font> #

```
Some more sophisticated links:

  * this is [http://daringfireball.net/projects/markdown @link]
  * another [http://daringfireball.net/projects/markdown &link]
  * take [http://daringfireball.net/projects/markdown this `link]
  * another [http://daringfireball.net/projects/markdown {{{link}}}]
  * <a href="http://daringfireball.net/projects/markdown">foo `]` link</a>
  * <a href="http://daringfireball.net/projects/markdown">an _emphasized `*`_ `_`nightmare</a>
```

# <font color='darkred'>Wiki View</font> #

Some more sophisticated links:

  * this is [@link](http://daringfireball.net/projects/markdown)
  * another [&link](http://daringfireball.net/projects/markdown)
  * take [this `link](http://daringfireball.net/projects/markdown)
  * another [{{{link}}}](http://daringfireball.net/projects/markdown)
  * <a href='http://daringfireball.net/projects/markdown'>foo <code>]</code> link</a>
  * <a href='http://daringfireball.net/projects/markdown'>an <i>emphasized <code>*</code></i> <code>_</code>nightmare</a>