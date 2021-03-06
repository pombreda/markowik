GCW does not support subsequent nested paragraphs because the empty lines which
separate paragraphs stop the nesting environment (a list or a blockquote).
Markowik works around this issue by connecting nested paragraphs with the HTML
tag `<br/>` on a line of its own.

Lets check some nesting madness:

-   item 1
-   item 2 consists of

    two paragraphs

-   item 3 consists of

    > a blockquote with
    >
    > two paragraphs
    
    a paragraph
    
    > and a blockquote with
    >
    >   > a nested blockquote
    >   >
    >   > which has two paragraphs
    >
    > this is a paragraph in the second blockquote of list item 3
    >
    >   -   this is a list
    >   -   in the second blockquote of list item 3
    >
    >       PyMD 2.1 supports paragraphs in lists nested in blockquotes
    >
    >   -   well done!

3-level blockquote nesting:

>   level 1, paragraph 1
>
>   level 1, paragraph 2
>
>   >   level 2, paragraph 1
>   >
>   >   level 2, paragraph 2
>   >
>   >   >   level 3, paragraph 1
>   >   >
>   >   >   level 3, paragraph 2
>   >   >
>   >   >       a code block
>   >   >       in level 3

