Markdown-Notes
===============
http://localhost/_Notes/Markdown-Notes.md

Just a small list of things I'd like to remember regarding Markdown(.md) Syntax


# This is an H1, includes a horizontal rule below  `#` 
## This is an H2, includes a horizontal rule below `##` 
### This is an H3 `###` includes a double space
#### This is an H4 `####`<br /><br />
##### This is an H5 `#####`<br /><br />
###### This is an H6 `######`<br /><br />


*Italic characters* `*` 

**Bold characters** `**` 

linebreak with double spaces at end of note `  `    
or html break tag `<br />`  
hit enter twice for a double space `↵ ↵`

[This is link](http://example.net/)...

1. ordered list item 1
    * indented unordered list item
        * indented unordered list item
2. ordered list item 2
3. ordered list item 3


* unordered list item 1
* unordered list item 2
* unordered list item 3

can also use an image as li bullet:  
![#f03c15](https://placehold.it/15/f03c15/000000?text=+) red  
![#c5f015](https://placehold.it/15/c5f015/000000?text=+) green  
![#1589F0](https://placehold.it/15/1589F0/000000?text=+) blue  
![#f7941d](https://placehold.it/15/f7941d/000000?text=+) orange  
![#662d91](https://placehold.it/15/662d91/000000?text=+) purple  


> \> Introducing my quote  
> break, for multline

```diff
```diff
+ this will be highlighted in green/yellow, but not always
- this will be dulled in red/grey, but not always
```


Use the backtick (\`) before and after to refer to a `function()` denote

Use double backticks (\`\`) ``to backtick (`) within a function denote``

Use \ to escape a backtick (\`) on a markdown note



```
use triple backticks(```) before and after a block
```

    Indent every line of the block by at least 4 spaces
    or 1 tab.






**table format** | `var` | `let` | `const`
:--- | ---: | ---: | ---:
_global scope_ | yes | no | no
_function scope_ | yes | yes | yes
_block scope_ | no | yes | yes

horizontal line
___
