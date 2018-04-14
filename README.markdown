# Markdown Editor Feature Evaluation Document
This document is created for evaluating the conformance of a Markdown Editor(/Viewer) for standard/non-standard features.  You may load this document in the Markdown application and see how it render the markups.

This document is released to the Public Domain with no copyright restrictions applied.

## Headings
### 3rd Level Heading
#### 4th Level Heading
##### 5th Level Heading
###### 6th Level Heading

## Line Breaks & Paragraphs
This is the first line  
This is the second line

This is the second paragraph.

## Horizontal Rules
---

## Blockquotes
> > This is good

> Yeah

No

## Code
### Indent Style
    #include <stdio.h>
    #include <stdlib.h>
    
    int main(int argc, char** argv){
        printf("%s\n", "Hello World!");
        return EXIT_SUCCESS;
    }

### Fence Style
```
#include <stdio.h>
#include <stdlib.h>

int main(int argc, char** argv){
    printf("%s\n", "Hello World!");
    return EXIT_SUCCESS;
}
```

## Direct Formatting
### Emphasis
Apply formatting *here*

### Strong Emphasis
Apply formatting **here**

### Raw HTML Elements
#### &lt;u&gt;: The Unarticulated Annotation (Underline) element
Apply formatting <u>here</u>

#### &lt;mark&gt;: The Mark Text element
Apply formatting <mark>here</mark>

## Hyperlinks
[Google](https://google.com)

## Images

## Extensions
### Striked-out Text Formatting
Apply formatting ~~here~~

### Tables
#### Centered
| Name | Value |
| :-: | :-: |
| Apple | 3 |
| Oranges | 5 |

### Checklists
* [ ] Apple
* [x] Orange

### Scientific Rendering
#### TEX-like
##### Legacy TEX Syntax
###### Inline
$\frac{2}{3}$

###### Independent
$$\frac{2}{3}$$

#### LaTeX Syntax
##### Inline
\\(\frac{2}{3} \\)

##### Independent
\\[ \frac{2}{3} \\]

### Code with Syntax Highlighting
```c
#include <stdio.h>
#include <stdlib.h>

int main(int argc, char** argv){
    printf("%s\n", "Hello World!");
    return EXIT_SUCCESS;
}
```
 
