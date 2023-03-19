#Basic markdown commands


---

###Font styles

>To make text __italic__, add __\___ symbol before and after the word/phrase(like that \_Italic\_)

__Examples:__

* _Italic_
* __Bold__ (used two __\___ symbols)
* ___Bold and Italic___ (used three __\___ symbols)
* ~~Crossed~~ (used two __~__ symbols)

---

###Blockquotes
>To add a blockquote, use '>' symbol(blockquotes can be nested with adding exta '>')

__Example:__
>Lorem ipsum(__used one '>'__)
>>Lorem ipsum(__used two '>'__)

---

###Inserting code

>To insert code, you can use __\`__ or __\```__ before and after text
To specify which language color scheme should be used, indicate it manually after first special symbol(in this example:     __```html__) 

__Example:__
```html
<body class="light-theme">
    <h1>Task List</h1>
    <p id="msg">Current tasks:</p>
    <ul>
        <li class="list">Add visual styles</li>
        <li class="list">Add light and dark theme</li>
        <li>Enable switching the theme</li>
    </ul>
    <div>
        <button class="btn">Dark</button>
    </div>
    <script src="app.js"></script>
    <noscript>You need to enable JS to view the full site</noscript>
</body>
```

---

###Adding links

>To add link, use this syntax: \[\_link text_](\_link_)

__Example:__
[Microsoft learn](https://learn.microsoft.com/)

>If link is big and it messes up the text, you can create link on link

first hyperlink[^1] and second hyperlink[^2] 

---

###Creating lists

>To create unnumbered list, use __*__ or __-__ sign before element
To create numbered list, use __numbers__(1,2,3, etc) before element
To create nested list, use __tab__ before special sign  


__Examples:__

_Unnumbered:_

* el1
* el2
* el3
    * el 31
        * el 32
            * el 33

<br>

_Numbered:_
1. el1
2. el2
3. el3
    1. el4
    2. el5
        1. el6
            
---
###Lines

>To create horizontal line, enter three __-__ symbols(it also can be __\___ or __*__) one after another

__Examples:__

---
___

***
<br>

---

###Inserting images

>To insert image, use this syntax: ![\_Description of image_](\_image link(url or local)_)


__Example:__

![inserting image](1.jpg)

---

###Creating tables

>To create table, use this syntax:
```
column1_name | column2_name | ... | columnN_name
:------------|:-------------|:----|-------------:
row1_name    | value(2,1)   |.....| value(n,1)
row2_name    | value(2,2)   |.....| value(n,2)
..........   | ..........   |.....| .........
rowN_name    | value(2,N)   |.....| value(N,N)
```

type name | full name     | size
:---------|:--------------|-----:
int       | System.Int32  |4 bytes
bool      | System.Boolean|1 byte
char      | System.Char   | 1 byte

---

###Using special symbols as regular text

>To use special character as regular text, use __\\__ sign before special character

__Examble:__

\# Header

---

###Adding emojis

>To add emoji, put its name between two __:__ signs

__Example:__

:expressionless:

---

###Adding checklists

>To add checklist, use this syntax: - [ ] \_Task name_
They can be nested

__Example:__
- [ ] Main Task
    - [ ] Secondary Task



[^1]: https://www.google.com
[^2]: https://translate.google.com