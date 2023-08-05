# Markdown
Markdown is a Lightweight Markup Language

## Things you can format
    Headings
    Lists
    Emphasis
    Links
    Blocks of Code
    Images
    Blockquotes
    Horizontol Rules

## VsCode Extensions
    Markdown Preview Github Styling
    Auto-Open Markdown 
    
[comment]: # (This is a comment, it will not be included)

---
## 0. Escape a special character
    Use \ to escape a special charater
    ### Text
    \### Text

### Text
\### Text

## 1. Headings

    To add a heading use : # Heading 
    
    # Heading 1
    ## Heading 2
    ### Heading 3
    #### Heading 4
1. # Heading 1
2. ## Heading 2
3. ### Heading 3
4. #### Heading 4

## 2. Italics
    To change a text style to italics, 
    add the text in between * * or _ _
    
    *This text* is italic
    So is _this text_
*This text* is italic

So is _this text_

## 3. Bold (Strong)
    To change a text style to bold,
    add the text in between ** ** or __ __
    
    **This text** is bold
    So is __this text__

**This text** is bold

So is __this text__

## 4. Strikethrough
    To strikethrough a text,
    add the text in between ~~ ~~ (double tilde Text double tilde)

    ~~This text~~ is strikethrough

~~This text~~ is strikethrough

## 5. Horizontal Rule
    To add a horizontal seperator,
    use --- (triple hyphen)
    or ___ (triple underscores)

---
This text is added after a seperator
___
So is this text

## 6. Blockquote
    To quote a text, type > followed by the text

    > Note : This is a quote
    

> Note : This is a quote

## 7. Links
    To add a link to a text,
    add the text in [] and link in ()

    [Google Search](https://www.google.com/)

    To display a custom text when we hover over the link,
    add the custom text in " " after the link in ()

    [Google Search](https://www.google.com/ "Click to Search")

[Google Search](https://www.google.com/)

[Google Search](https://www.google.com/ "Click to Search")

## 8. Images
    To add an image,
    Add ! followed by Alt Text in [] and link in ()

    ![Markdown Here](https://markdown-here.com/img/icon48.png)

![Markdown Here](https://markdown-here.com/img/icon48.png)


## 9. Unordered Lists (UL)
    To create an UL,
    add a * followed by the item name

    * Item 1
    * Item 2
    * Item 3
    
    To create a nested item,
    press TAB followed by * and item name

        * Item 3.1
            * Item 3.1.1
            * Item 3.1.2
        * Item 3.2

* Item 1
* Item 2
* Item 3
    * Item 3.1
        * Item 3.1.1
        * Item 3.1.2
    * Item 3.2

## 10. Ordered List (OL)
    To create an OL,
    add 1. followed by the item name

    1. Item 1
    1. Item 2
    1. Item 3

    To create a nested item,
    press TAB followed by 1. and item name

        1. Item 3.1
            1. Item 3.1.1
            1. Item 3.1.2
        1. Item 3.2

1. Item 1
1. Item 2
1. Item 3
    1. Item 3.1
        1. Item 3.1.1
        1. Item 3.1.2
    1. Item 3.2

## 11. Inline Code Block
    To create an inline code block,
    add the code in between ` ` (backticks)

    `print("Hello, World")`
    <p>This is a paragraph</p>

`print("Hello, World")`

`<p>This is a paragraph</p>`

---
# Github Markdown

## 1. Codeblocks
    Add code in between ``` ``` (triple backticks)

    ``` 
    npm install

    npm start
    ```

    Language specific codeblocks

    ```python
    def sum(num1,num2):
        return num1 + num2
    ```

``` 
npm install

npm start
```

```python
def sum(num1,num2):
    return num1 + num2
```

## 2. Tables
    Use | to create vertical lines,
    and - to create horizontal lines

    | Name | Branch |
    |-|-|
    | Omkar | ME |
    | Aditya | EC |
    | Shlok | CS |

| Name | Branch |
|-|-|
| Omkar | ME |
| Aditya | EC |
| Shlok | CS |

## 3. Task Lists
    To create an Task List,
    add a * followed by [x] or [ ] and the task name
    
    * [x] Task 1
    * [x] Task 2
    * [ ] Task 3

* [x] Task 1
* [x] Task 2
* [ ] Task 3

---
# Useful Links :

* [Markdown Crash Course](https://youtu.be/HUBNt18RFbo)

* [Basic Syntax](https://www.markdownguide.org/basic-syntax/)

* [Extended Syntax](https://www.markdownguide.org/extended-syntax/)
---