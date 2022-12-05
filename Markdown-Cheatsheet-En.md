<!-- 
 *   https://github.com/andreysssr/Markdown-Cheatsheet
-->

# Cheatsheet on Markdown - Markdown syntax

---

##### Content
[Headings](#headers)  
[The block in which the code is issued code](#blockCode)  
[Horizontal lines](#hr)  
[Text Selection](#textSelecte)  
[Line breaks](#lineBreaks)  
[Lists and margins](#listsAndMargins)  
[Links and pictures](#linksAndPictures)  
[Inserting a local image - from the current folder](#localPictures)  
[Creating a menu](#createMenu)  
[Quotes](#quotes)  
[Inserting code](#insertingCode)  
[Tables](#tables)  
[Checkboxes](#checkboxes)  
[Screening](#screening)

---
<a name="headers"><h2>Headings</h2></a>

The H1–H6 headers are highlighted in Markdown using lattice signs

# This is H1
## This is H2
### This is H3
#### This is H4
##### This is H5
###### This is H6

H1 and H2 can also be distinguished in a different way

Is it H1 or Header I
===
Is it H2 or Header II
---

[code] ↓
```
# This is H1
## This is H2 
### This is H3
#### This is H4 
##### This is H5 
###### This is H6

H1 and H2 can also be distinguished in a different way

Is it H1 or Header I
===

Is it H2 or Header II
---
```

---
<a name="blockCode"><h2>The block in which the code is issued codede]</h2></a>
to design a block or highlight words in the text, three back quotes are used above the block and three back quotes under the block of text

[code] ↓
```
    ```
        here is the block that needs to be issued
    ```
```

---
<a name="hr"><h2>Horizontal lines</h2></a>
---
or
***
or
<hr>

[code] ↓
```
---
    or
***
    or
<hr>
```

---
<a name="textSelecte"><h2>Text Selection</h2></a>

Plain text

__Bold text__

**Bold text**

*Italics text*

_Italics text_

~~Crossed text~~

[code] ↓
```
Plain text

__Bold text__

**Bold text**

*Italics text*

_Italics text_

~~Crossed text~~
```

---
<a name="lineBreaks"><h2>Line breaks</h2></a>

Two spaces after the line.  
A new line has been inserted.

Using HTML tag to break.<br>
A new line has been inserted.

[code] ↓
```
Two spaces after the line.  
A new line has been inserted.

Using HTML tag to break.<br>
A new line has been inserted.
```

---
<a name="listsAndMargins"><h2>Lists and margins</h2></a>

To make a line into a bulleted list item,
you need to put a plus, minus or asterisk at the beginning.

- Item 1
- Item 2
- Item 3

or
+ Item 1
+ Item 2
+ Item 3

or
* Item 1
* Item 2
* Item 3

[code] ↓
```
- Item 1
- Item 2
- Item 3

or
+ Item 1
+ Item 2
+ Item 3

or
* Item 1
* Item 2
* Item 3
```
. . . . . . . . . . .


1. Item 1
2. Item 2
3. Item 3

or
1. Item 1
1. Item 2
1. Item 3

[code] ↓
```
1. Item 1
2. Item 2
3. Item 3

or
1. Item 1
1. Item 2
1. Item 3

```
. . . . . . . . . . .

- Item 1
    - Subitems A
        - Subitems a

- Item 2
    + Subitems A
        * Subitems a

<br>

1. Item 1
    + Subitems A
        - Subitems a

2. Item 2
    1. Subitems 2.1.
        1. Subitems 2.1.1

3. Item 3


[code] ↓
```
- Item 1
    - Subitems A
        - Subitems a
        
- Item 2
    + Subitems A
        * Subitems a



1. Item 1
    + Subitems A
        - Subitems a

2. Item 2
    1. Subitems 2.1.
        1. Subitems 2.1.1

3. Item 3
```

---
<a name="linksAndPictures"><h2>Links and pictures</h2></a>

This [link](http://example.net/ "Agency") with a title.

[This link](http://example.net/) without a title.

<https://example.com/> – this is a non-anchor link.

[code] ↓
```
This [link](http://example.net/ "Agency") with a title.

[This link](http://example.net/) without a title.

<https://example.com/> – this is a non-anchor link.
```

The Markdown syntax for working with pictures is very similar to working with links.
The difference is in the exclamation mark before the first square brackets.
The link to the picture can also be assigned a specific ID. Examples:


![Logo github](https://github.githubassets.com/favicons/favicon.svg)

![Logo github](https://github.githubassets.com/favicons/favicon.svg "Our logo")

```
![Logo github](https://github.githubassets.com/favicons/favicon.svg)

![Logo github](https://github.githubassets.com/favicons/favicon.svg "Our logo")
```

---
<a name="localPictures"><h2>Inserting a local image - from the current folder</h2></a>

<p align="center">
    <img alt="Git" src="img/git-logo.png" height="190" width="455">
</p>

[code] ↓

```
# image location - left, center, right
<p align="center">
    <img alt="Git" src="img/git-logo.png" height="190" width="455">
</p>
```

---
<a name="createMenu"><h2>Creating a menu</h2></a>

#### Creating a menu on external pages

[Menu item 1](http://example.net/url1)   
[Menu item 2](http://example.net/url2)
- [Menu item 3](http://example.net/url3)
- [Menu item 4](http://example.net/url4)  
  -- [Menu item 5](http://example.net/url5)  
  -- [Menu item 6](http://example.net/url6)

[Menu item 7](http://example.net/url7)  
[Menu item 8](http://example.net/url8)

[code] ↓

```
[Menu item 1](http://example.net/url1)   
[Menu item 2](http://example.net/url2)   
- [Menu item 3](http://example.net/url3)   
- [Menu item 4](http://example.net/url4)  
-- [Menu item 5](http://example.net/url5)  
-- [Menu item 6](http://example.net/url6)

[Menu item 7](http://example.net/url7)  
[Menu item 8](http://example.net/url8) 
```
. . . . . . . . . . . . . . . .
#### Creating a menu for internal page items

[Headings](#headers)  
[Horizontal lines](#hr)  
[Text Selection](#textSelecte)

[code] ↓

```
# menu design 
[Headings](#headers)  
[Horizontal](#hr)  
[Text Selection](#textSelecte)

# the design of the titles referenced by the menu
<a name="headers"><h2>Headings</h2></a>
<a name="hr"><h2>Horizontal</h2></a>
<a name="textSelecte"><h2>Text Selection</h2></a>
```

---
<a name="quotes"><h2>Quotes</h2></a>

> Hi! This is a quote

>> This is also a quote

> This is another quote
This is its continuation (we show it indented)

> This is also
> One whole quote

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
    >
    >  *Everything* is going according to **plan**.

[code] ↓
```
> Hi! This is a quote

>> This is also a quote

> This is another quote
This is its continuation (we show it indented)

> This is also
> One whole quote

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
```

Quotes are embedded both in lists and in other quotes.
Quotes can also include headers, lists, and code.

---
<a name="insertingCode"><h2>Inserting code</h2></a>

You can insert the code both inside the lines and in separate blocks.
Gravis or reverse ticks are used for the corresponding markup - a backquote on the key ( ~ ).

The inline code is allocated in single characters, and the blocks are triple.
When designing an entire block, you can specify a programming language
to highlight the appropriate syntax.

Inline code: `print("Hello, World!")`

[code] ↓

```
Inline code: `print("Hello, World!")`
```
. . . . . . . . . . . . . . . .

Python code:

```python
x = int(input())
if x > 0:
    print(x)
else:
    print(-x)
```

. . . . . . . . . . . . . . . .

JavaScript code:
```javascript
let greeting1 = 'Father!';
console.log(greeting1);

let greeting2 = 'Mother!';
console.log(greeting2);
```

[code] ↓
```
# after the back quotes, add the language - for highlighting
```javascript
let greeting1 = 'Father!';
console.log(greeting1);

let greeting2 = 'Mother!';
console.log(greeting2);
`` `
```

. . . . . . . . . . . . . . . .

lua code

```lua
local Class = {
    new = function(self, Objict1, Object2, Config) 
        //...
        return self
    end
}
```
[code] ↓

```
    # after the back quotes, add the language - for highlighting
    ```lua
    local Class = {
        new = function(self, Objict1, Object2, Config) 
            //...
            return self
        end
    }
    ```
```

---
<a name="tables"><h2>Tables</h2></a>

| Fun                  | With                 | Tables          |
| :------------------- | -------------------: |:---------------:|
| left-aligned column  | right-aligned column | centered column |
| $100                 | $100                 | $100            |
| $10                  | $10                  | $10             |
| $1                   | $1                   | $1              |

|                  |Header 1 |Header 2|
|------------------|---------|--------|
|**First column A**|Cell 1A  |Cell 2A |
|**First column B**|Cell 1B  |Cell 2B |

| Язык | Метка |
| -----|------|
| Java Script | javascript |
| C++ |cpp|
| HTML|html|
|Markdown|md|
|JSON|json|
|Python|python|
|SQL|sql|

|   | table | header |
|---|-------|--------|
| a | table | row    |
| b | table | row    |


[code] ↓
```
| Fun                  | With                 | Tables          |
| :------------------- | -------------------: |:---------------:|
| left-aligned column  | right-aligned column | centered column |
| $100                 | $100                 | $100            |
| $10                  | $10                  | $10             |
| $1                   | $1                   | $1              |

|                  |Header 1 |Header 2|
|------------------|---------|--------|
|**First column A**|Cell 1A  |Cell 2A |
|**First column B**|Cell 1B  |Cell 2B |

| Язык | Метка |
| -----|------|
| Java Script | javascript |
| C++ |cpp|
| HTML|html|
|Markdown|md|
|JSON|json|
|Python|python|
|SQL|sql|

|   | table | header |
|---|-------|--------|
| a | table | row    |
| b | table | row    |

```

---
<a name="checkboxes"><h2>Checkboxes</h2></a>

For fans of checklists, there is such an opportunity.
A check-box will turn out if you put a space at the beginning of the line,
enclosed on both sides in square brackets.
You can immediately set the completed task using [X].
With the design of links in a different way - in square brackets
or text, or nothing.

- [X] Take a wallet
- [x] Go to the store
- [x] Buy bread and milk
- [ ] Bring groceries home

[code] ↓
```
- [X] Take a wallet 
- [x] Go to the store 
- [x] Buy bread and milk
- [ ] Bring groceries home
```

---
<a name="screening"><h2>Screening</h2></a>

In order for special characters not to disappear and not affect the design,
you need to use shielding. As in many other
programming languages, the backslash serves these purposes.

\*No italics\*
\*\*No bold selection\*\*
\# No headlines H1 \#

[code] ↓
```
\*No italics\*
\*\*No bold selection\*\*
\# No headlines H1 \#
```
