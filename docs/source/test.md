# GitHub Flavored Markdown Syntax

## 1. Headers

###  Use  ``` # ``` from level-1 to level-6 for headers of different size. 
```
# H1
## H2
### H3
#### H4
##### H5
##### H6
```

## 2. Emphasis
*Emphasis, aka italics,* with asterisks or underscores. { ``` *Text* ```} 

**Strong emphasis, aka bold,** with asterisks or underscores. { ``` **Text** ``` or  ``` __Text__ ```} 

**Combined _emphasis_** with asterisks and underscores. { ``` **bold and _italics_** ```}

Strikethrough uses two tildes. ~~Scratch this.~~ { ``` ~~Text~~ ```} 

## 3. Lists
Unordered list can use 

- asterisks {*}
- Or minuses {-}
- Or pluses {+}

For ordered lists use numbers 

1. First ordered list item
2. Another item

## 4. Links
``` [I'm an inline-style link for Google](https://www.google.com)```

[I'm an inline-style link for Google](https://www.google.com) 

## 5. Images
``` Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

<img src="image_url_here" 
style="background-color: white">

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
```

Inline-style:

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style:

![alt text][logo]
[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2" 

## 6. Add color text
``` 
Note: use color latex command and  ``` \ ``` for space. 
```

``` $\color{name} Text \ Sample$ ``` or

``` $\textsf{\color{name} Text sample}$ ``` 

$\textsf{\color{red} Text in Red}$

$\textsf{\color{cyan} Text in cyan}$

$\textsf{\color{blueviolet} Text in blueviolet}$

$\textsf{\color{orange} Text in orange}$

$\textsf{\color{yellow} Text in yellow}$

$\textsf{\color{lime} Text in lime}$

$\textsf{\color{magenta} Text in magenta}$

## 7. Maths
Use $ or $$ 
This is inline math equation $ y = x^2 $ using ``` $equation$ ```.

This is centered block math equation $$ y= x^2 $$ using  ``` $$equation$$ ``` 
## 8. Collapsed Sections

``` 
<details>
<summary>Tips for collapsed sections</summary>
### You can add a header
You can add text within a collapsed section. 
You can add an image or a code block, too.
</details>
 ```

<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

 You can add text within a collapsed section. 

 You can add an image or a code block, too.

</details>

## 9. Code and Syntax Highlighting
 Use triple ticks ``` Code ``` for multiline and single ticks `Code` for inline codes. 

`import os`

``` 
import numpy as np
import pandas as pd
```

Use ```diff for highlighting. 

```diff
- text in red

+ text in green
```

## 10. Tables

``` Colons can be used to align columns.
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


## 11. Blockquotes

Use > Text 
 
> This is the text within Blockquotes 


## 12. Horizontal Rule

Use three Hypens --- 

Paragraph 1 

---
Paragraph 2 

## 13. Subscript and Superscript
 Use _ and ^ within $ or  ``` <sub> Text </sub> ``` and  ``` <sup> Text </sup> ``` 
 
$x^{superscript}$ and  $x_{underscript}$
 
 X<sub>underscript</sub> and X<sup>superscript</sup> 

## 14. Alerts

```
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

```

> [!NOTE]
> Useful information that users should know, even when skimming content. 

> [!TIP]
> Helpful advice for doing things better or more easily. 

> [!IMPORTANT]
> Key information users need to know to achieve their goal. 

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems. 

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions. 


