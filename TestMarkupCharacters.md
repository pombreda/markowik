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
Characters used for markup in Markdown and/or GCW.

Normal: []{}()#+-.!

Escaped: \\, \`, \*, \_, \[, \], \{, \}, \(, \), \#, \+, \-, \., \!

In a code block:

    Code block
    \`*_[]{}()#+-.!
    \\, \`, \*, \_, ,\[, \], \{, \}, \(, \), \#, \+, \-, \., \!

- monospace normal ``\`*_[]{}()#+-.!``
- monospace escaped ``\\, \`, \*, \_, ,\[, \], \{, \}, \(, \), \#, \+, \-, \., \!``

GCW code markers: {{{ foo }}} bar \`{{{\`}}}
```

# <font color='darkred'>Wiki Source</font> #

```
Characters used for markup in Markdown and/or GCW.

Normal: `[``]`{}()#+-.!

Escaped: \, {{{`}}}, `*`, `_`, `[`, `]`, {, }, (, ), #, +, -, ., !

In a code block:

{{{
Code block
\`*_[]{}()#+-.!
\\, \`, \*, \_, ,\[, \], \{, \}, \(, \), \#, \+, \-, \., \!
}}}

  * monospace normal {{{\`*_[]{}()#+-.!}}}
  * monospace escaped {{{\\, \`, \*, \_, ,\[, \], \{, \}, \(, \), \#, \+, \-, \., \!}}}

GCW code markers: `{{{` foo `}}}` bar {{{`}}}`{{{`{{{`}}}`}}}`
```

# <font color='darkred'>Wiki View</font> #

Characters used for markup in Markdown and/or GCW.

Normal: `[``]`{}()#+-.!

Escaped: \, `````, `*`, `_`, `[`, `]`, {, }, (, ), #, +, -, ., !

In a code block:

```
Code block
\`*_[]{}()#+-.!
\\, \`, \*, \_, ,\[, \], \{, \}, \(, \), \#, \+, \-, \., \!
```

  * monospace normal ``\`*_[]{}()#+-.!``
  * monospace escaped ``\\, \`, \*, \_, ,\[, \], \{, \}, \(, \), \#, \+, \-, \., \!``

GCW code markers: `{{{` foo `}}}` bar ``````{{{```````}}}`