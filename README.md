# GitHub Markdown Syntax Guide #

### Here’s an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files. ###

## Headers ##

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

# The Largest Heading #
## The Second Largest Heading ##
### The Third Largest Heading ###
#### The Fourth Largest Heading ####
##### The Fifth Largest Heading #####
###### The Smallest Heading ######


#### There are one more option to use Heading Tags using HTML syntax ####

    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>

<br /><br />

## Emphasis (Styling text) ##
### We can use Styling tags to style our statements ###

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

### Quoting a text - We can quote a text by using ">" ###

    Text that is not a quote
    
    > Text that is a quote

Text that is not a quote

> Text that is a quote

> This is a Quote.
>> The Quted text in Quoted text.
>>> Another Quote in Quoted text of Quoted text.

### More styling ###

    Monospace and Underlined text
    
<samp>The Statement having font family Monospace.</samp>

<ins>The Underlined text.</ins>

### Boxed Statement ###

<table><tr><td>This Statement is in a Box.</td></tr></table>

### Subscript and Superscript ###

H<sub>2</sub>O

5x<sup>2</sup>

### Quoting code - We can quote code by using backticks(`) ###

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

Inline `code` has `back-ticks around` it.

<br />

Function:
```
function test() {
  console.log("notice the blank line before this function?");
}
```

<br />

#### Note - You can add an optional language identifier to enable syntax highlighting in your fenced code block. ####

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

#### You can also simply indent your code by four spaces: ####

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }

<br /><br />

## Table ##

#### We can create table by using below syntax:- ####

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

<br /><br />

## Lists ##

There are two types of ___Lists___

### Unordered Lists ###

    * Item 1
    * Item 2
      * Item 2a
      * Item 2b
      
    - Item 1
    - Item 2
      - Item 2a
      - Item 2b
      
    + Item 1
    + Item 2
      + Item 2a
      + Item 2b
      
* Item 1
* Item 2
  * Item 2a
  * Item 2b

### Ordered Lists ###

    1. Item 1
    1. Item 2
    1. Item 3
       1. Item 3a
       1. Item 3b

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

#### Note - You must've to place child list just below the first letter of parent list. ####

    1. First list item
       - First nested list item
         - Second nested list item

1. First list item
   - First nested list item
     - Second nested list item

#### You can also add HTML syntax ####

    <ul>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
    <li>Fourth item</li>
    </ul>

<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>

#### Note - You can also use nested ***Unordered*** or ***Ordered*** list ####

<br /><br />

## Links ##

    http://github.com - automatic!

    [GitHub](http://github.com)

http://github.com - automatic!

[GitHub](http://github.com)

#### Note - We can also create relative links with all relative link operands, such as ./ and ../ ####

<br /><br />

## Images ##

    ![Nihal Priyadarshi](https://raw.githubusercontent.com/Nihal-Priyadarshi/Curriculum-vitae/master/Images/Nihal.jpg "Nihal Priyadarshi")
    
    Format: ![Alt Text](url)

![Nihal Priyadarshi](https://raw.githubusercontent.com/Nihal-Priyadarshi/Curriculum-vitae/master/Images/Nihal.jpg "Nihal Priyadarshi")

#### Note - You can also use html tag to set height or width of the image. ####

<img src="https://raw.githubusercontent.com/Nihal-Priyadarshi/Curriculum-vitae/master/Images/Nihal.jpg" width="200" height="200"/>

## Inline HTML ##

#### You can also use raw HTML in your Markdown. ####

    <section>
         <h2>Taste The Joy</h2>
         <p>We are enlighting your every Sunday evening in our cafe, you can taste different varities of coffee
              and listen to famous poets and their beautiful poetries.<br><br>You will always find something new
              here.</p>
    </section>

#### Note - You Cannot use ___Markdown Syntax___ in HTML. ####

<br /><br />

## Task Lists ##

#### We can create a task list items with a regular space character using a hyphen followed by [ ], and to mark a complete task, put an x inside the brackets, use [x]. ####
    
    - [x] HTML
    - [x] CSS
    - [ ] Javascript
    - [ ] Add delight to the experience when all tasks are complete :tada:

- [x] HTML
- [x] CSS
- [ ] Javascript
- [ ] Add delight to the experience when all tasks are complete :tada:

#### We can also nest this task list. ####

    - [ ] Frontend
        - [x] HTML
        - [x] CSS
        - [x] Bootstrap
        - [ ] Javascript
    - [ ] Backend
        - [ ] PHP
        - [ ] Node.js
        - [ ] Mongo.db
    - [ ] Add delight to the experience when all tasks are complete :tada:

- [ ] Frontend
    - [x] HTML
    - [x] CSS
    - [x] Bootstrap
    - [ ] Javascript
- [ ] Backend
    - [ ] PHP
    - [ ] Node.js
    - [ ] Mongo.db
- [ ] Add delight to the experience when all tasks are complete :tada:

<br /><br />

## Horizontal Rule ##

#### We can use three hyphens, asterisks, or underscores to create a horizontal line. ####

    ---
    
    Hyphens
    
    ***
    
    Asterisks
    
    ___
    
    Underscores

---

Hyphens

***

Asterisks

___

Underscores

<br /><br />

## Username @mentions ##

Typing an `@` symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

<br /><br />

## Reference Lists & Titles ##

    **The quick brown [fox][1], jumped over the lazy [dog][2].**
    
    [1]: https://en.wikipedia.org/wiki/Fox "Wikipedia: Fox"
    [2]: https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog"

**The quick brown [fox][1], jumped over the lazy [dog][2].**

[1]: https://en.wikipedia.org/wiki/Fox "Wikipedia: Fox"
[2]: https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog"

<br /><br />

## Escaping ##

    *   Asterisk
    \   Backslash
    `   Backtick
    {}  Curly braces
    .   Dot
    !   Exclamation mark
    #   Hash symbol
    -   Hyphen symbol
    ()  Parentheses
    +   Plus symbol
    []  Square brackets
    _   Underscore

    \*Escaping\*
    \\Escaping\\
    \`Escaping\`
    \{Escaping\}
    \.Escaping\.
    \!Escaping\!
    \#Escaping\#
    \-Escaping\-
    \(Escaping\)
    \+Escaping\+
    \[Escaping\]
    \_Escaping\_

\*Escaping\*

\\Escaping\\

\`Escaping\`

\{Escaping\}

\.Escaping\.

\!Escaping\!

\#Escaping\#

\-Escaping\-

\(Escaping\)

\+Escaping\+

\[Escaping\]

\_Escaping\_

<br /><br />

## Comments ##

We can include comments inside a .md file.
  
    <!-- Lorem ipsum dolor sit amet -->

<!-- Lorem ipsum dolor sit amet -->

Here is a code written but no one is able to see it because it is a comment.

<br /><br />

## Automatic linking for URLs ##

Any URL `http://www.github.com/` will be automatically converted into a clickable link.

    http://www.github.com/

http://www.github.com/

<br /><br />

## Emoji ##

#### We can also include emojis in our `.md` file. ####

:bowtie::smile::simple_smile:    | :laughing:        | :blush:           | :smiley:          | :relaxed:         | :smirk:           |
| :heart_eyes:      | :kissing_heart:   | :kissing_closed_eyes: | :flushed:     |


:relieved:
:satisfied:
:grin:
:wink:
:stuck_out_tongue_winking_eye:
:stuck_out_tongue_closed_eyes:
:grinning:
:kissing:
:kissing_smiling_eyes:
:stuck_out_tongue:
:sleeping:
:worried:
:frowning:
:anguished:
:open_mouth:
:grimacing:
:confused:
:hushed:
:expressionless:
:unamused:
:sweat_smile:
:sweat:
:disappointed_relieved:
:weary:
:pensive:
:disappointed:
:confounded:
:fearful:
:cold_sweat:
:persevere:
:cry:
:sob:
:joy:
:astonished:
:scream:
:neckbeard:
:tired_face:
:angry:
:rage:
:triumph:
:sleepy:
:yum:
:mask:
:sunglasses:
:dizzy_face:
:imp:
:smiling_imp:
:neutral_face:
:no_mouth:
:innocent:
:alien:
:yellow_heart:
:blue_heart:
:purple_heart:
:heart:
:green_heart:
:broken_heart:
:heartbeat:
:heartpulse:
:two_hearts:
:revolving_hearts:
:cupid:
:sparkling_heart:
:sparkles:
:star:
:star2:
:dizzy:
:boom:
:collision:
:anger:
:exclamation:
:question:
:grey_exclamation:
:grey_question:
:zzz:
:dash:
:sweat_drops:
:notes:
:musical_note:
:fire:
:hankey:
:poop:
:shit:
:+1:
:thumbsup:
:-1:
:thumbsdown:
:ok_hand:
:punch:
:facepunch:
:fist:
:v:
:wave:
:hand:
:raised_hand:
:open_hands:
:point_up:
:point_down:
:point_left:
:point_right:
:raised_hands:
:pray:
:point_up_2:
:clap:
:muscle:
:metal:
:fu:
:runner:
:running:
:couple:
:family:
:two_men_holding_hands:
:two_women_holding_hands:
:dancer:
:dancers:
:ok_woman:
:no_good:
:information_desk_person:
:raising_hand:
:bride_with_veil:
:person_with_pouting_face:
:person_frowning:
:bow:
:couplekiss:
:couple_with_heart:
:massage:
:haircut:
:nail_care:
:boy:
:girl:
:woman:
:man:
:baby:
:older_woman:
:older_man:
:person_with_blond_hair:
:man_with_gua_pi_mao:
:man_with_turban:
:construction_worker:
:cop:
:angel:
:princess:
:smiley_cat:
:smile_cat:
:heart_eyes_cat:
:kissing_cat:
:smirk_cat:
:scream_cat:
:crying_cat_face:
:joy_cat:
:pouting_cat:
:japanese_ogre:
:japanese_goblin:
:see_no_evil:
:hear_no_evil:
:speak_no_evil:
:guardsman:
:skull:
:feet:
:lips:
:kiss:
:droplet:
:ear:
:eyes:
:nose:
:tongue:
:love_letter:
:bust_in_silhouette:
:busts_in_silhouette:
:speech_balloon:
:thought_balloon:
:feelsgood:
:finnadie:
:goberserk:
:godmode:
:hurtrealbad:
:rage1:
:rage2:
:rage3:
:rage4:
:suspect:
:trollface:






<br /><br />

## Referencing issues and pull requests ##

#### You can bring up a list of suggested issues and pull requests within the repository by typing `#`. Type the issue or pull request number or title to filter the list, and then press either tab or enter to complete the highlighted result. ####

`#` and issue or pull request number

`GH-` and issue or pull request number

`Username/Repository#` and issue or pull request number

`Organization_name/Repository#` and issue or pull request number

<br /><br />

## Footnotes ##

You can add footnotes to your content by using this bracket syntax:

    Here is a simple footnote[^1].
    
    A footnote can also have multiple lines[^2].  
    
    You can also use words, to fit your writing style more closely[^note].
    
    [^1]: My reference.
    [^2]: Every new line should be prefixed with 2 spaces.  
      This allows you to have a footnote with multiple lines.
    [^note]:
        Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
        This footnote also has been made with a different syntax using 4 spaces for new lines.

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.

<br /><br />

## Hotkey ##

<kbd>⌘F</kbd>

<kbd>⇧⌘F</kbd>

    Markup : <kbd>⌘F</kbd>

Hotkey list:

| Key | Symbol |
| --- | --- |
| Option | ⌥ |
| Control | ⌃ |
| Command | ⌘ |
| Shift | ⇧ |
| Caps Lock | ⇪ |
| Tab | ⇥ |
| Esc | ⎋ |
| Power | ⌽ |
| Return | ↩ |
| Delete | ⌫ |
| Up | ↑ |
| Down | ↓ |
| Left | ← |
| Right | → |







