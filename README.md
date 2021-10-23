# GitHub Markdown Syntax Guide

### Here’s an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.

## Headers

    "#" This is use to apply h1 tag
    "##" This is use to apply h2 tag
    "###" This is use to apply h3 tag
    "####" This is use to apply h4 tag
    "#####" This is use to apply h5 tag
    "######" This is use to apply h6 tag
    
    Alternatively, for H1 and H2, an underline-ish style:

    Alt-H1
    ======
    
    -OR-

    Markup :  ============= (below H1 text)

    Alt-H2
    ------
    
    -OR-

    Markup: --------------- (below H2 text)

# The Largest Heading
## The Second Largest Heading
### The Third Largest Heading
#### The Fourth Largest Heading
##### The Fifth Largest Heading
###### The Smallest Heading


#### There are one more option to use Heading Tags using HTML syntax

    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>

<br /><br />

## Emphasis (Styling text)
### We can use Styling tags to style our statements

    To make your text "Bold"
    **This text will be bold**
    __This will also be bold__
    <strong>This will be bold too</strong>

    To make your text "Italic"
    *This text will be italic*
    _This will also be italic_
    <em>This will be italic too</em>

    To "Strikethrough" your text
    ~~This text will be Strikethrough~~

    Combinations:-
    _You **can** combine them_
    **This _Italic_ is combined With Bold**
    <strong>This <em>Italic</em> is combined With Bold</strong>
    
    Bold and Italic
    ***This Statement is both Bold and Italic***
    ___This Statement is both Bold and Italic___


**This text will be bold**<br />
__This will also be bold__<br />
<strong>This will be bold too</strong><br />

*This text will be italic*<br />
_This will also be italic_<br />
<em>This will be italic too</em><br />

~~This text will be Strikethrough~~
<br />

_You **can** combine them_<br />
**This _Italic_ is combined With Bold**<br />
<strong>This <em>Italic</em> is combined With Bold</strong><br />

***This Statement is both Bold and Italic***<br />
___This Statement is both Bold and Italic___<br />

### Quoting a text - We can quote a text by using ">"

    Text that is not a quote
    
    > Text that is a quote

Text that is not a quote

> Text that is a quote

> This is a Quote.
>> The Quted text in Quoted text.
>>> Another Quote in Quoted text of Quoted text.

### More styling

    Monospace and Underlined text
    
<samp>The Statement having font family Monospace.</samp>

<ins>The Underlined text.</ins>

### Boxed Statement

<table><tr><td>This Statement is in a Box.</td></tr></table>

### Subscript and Superscript

H<sub>2</sub>O

5x<sup>2</sup>

### Quoting code - We can quote code by using backticks(`)

    Some basic Git commands are:
    ```
    git status
    git add
    git commit
    ```

Some basic Git commands are:
```
git status
git add
git commit
```

<br />

Function:
```
function test() {
  console.log("notice the blank line before this function?");
}
```

<br />

You can add an optional language identifier to enable syntax highlighting in your fenced code block.

Ruby code:-
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

Python code:-
```python
import sys
print("Hello World")
```

<br /><br />

## Table

We can create table by using below syntax:-

You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe | and :

    | Default | Left align | Center align | Right align |
    | - | :- | :-: | -: |
    | 9999999999 | 9999999999 | 9999999999 | 9999999999 |
    | 999999999 | 999999999 | 999999999 | 999999999 |
    | 99999999 | 99999999 | 99999999 | 99999999 |
    | 9999999 | 9999999 | 9999999 | 9999999 |
    
    
    | Default    | Left align | Center align | Right align |
    | ---------- | :--------- | :----------: | ----------: |
    | 9999999999 | 9999999999 | 9999999999   | 9999999999  |
    | 999999999  | 999999999  | 999999999    | 999999999   |
    | 99999999   | 99999999   | 99999999     | 99999999    |
    | 9999999    | 9999999    | 9999999      | 9999999     |
    
    
    Default    | Left align | Center align | Right align
    ---------- | :--------- | :----------: | ----------:
    9999999999 | 9999999999 | 9999999999   | 9999999999 
    999999999  | 999999999  | 999999999    | 999999999  
    99999999   | 99999999   | 99999999     | 99999999   
    9999999    | 9999999    | 9999999      | 9999999

<br />

| Default    | Left align | Center align | Right align |
| ---------- | :--------- | :----------: | ----------: |
| 9999999999 | 9999999999 | 9999999999   | 9999999999  |
| 999999999  | 999999999  | 999999999    | 999999999   |
| 99999999   | 99999999   | 99999999     | 99999999    |
| 9999999    | 9999999    | 9999999      | 9999999     |

















