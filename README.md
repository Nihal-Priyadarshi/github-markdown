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
    
<samp>The Statement having font family Monospace.</samp>

<ins>The Underlined text.</ins>

### Boxed Statement ###

    <table><tr><td>This Statement is in a Box.</td></tr></table>

<table><tr><td>This Statement is in a Box.</td></tr></table>

### Subscript and Superscript ###

    H<sub>2</sub>O
    5x<sup>2</sup>

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

    :bowtie: :smile: :laughing: :blush: :smiley: :relaxed: :smirk: :heart_eyes: :kissing_heart: :kissing_closed_eyes: :flushed: :relieved: :satisfied: :grin:
    :wink: :stuck_out_tongue_winking_eye: :stuck_out_tongue_closed_eyes: :grinning: :kissing: :kissing_smiling_eyes: :stuck_out_tongue: :sleeping: :worried:
    :frowning: :anguished: :open_mouth: :grimacing: :confused: :hushed: :expressionless: :unamused: :sweat_smile: :sweat: :disappointed_relieved: :weary: :pensive:
    :disappointed: :confounded: :fearful: :cold_sweat: :persevere: :cry: :sob: :joy: :astonished: :scream: :neckbeard: :tired_face: :angry: :rage: :triumph:
    :sleepy: :yum: :mask: :sunglasses: :dizzy_face: :imp: :smiling_imp: :neutral_face: :no_mouth: :innocent: :alien: :yellow_heart: :blue_heart: :purple_heart:
    :heart: :green_heart: :broken_heart: :heartbeat: :heartpulse: :two_hearts: :revolving_hearts: :cupid: :sparkling_heart: :sparkles: :star: :star2: :dizzy:
    :boom: :collision: :anger: :exclamation: :question: :grey_exclamation: :grey_question: :zzz: :dash: :sweat_drops: :notes: :musical_note: :fire: :hankey: :poop:
    :shit: :+1: :thumbsup: :-1: :thumbsdown: :ok_hand: :punch: :facepunch: :fist: :v: :wave: :hand: :raised_hand: :open_hands: :point_up: :point_down: :point_left:
    :point_right: :raised_hands: :pray: :point_up_2: :clap: :muscle: :metal: :fu: :star_struck: :runner: :running: :couple: :family: :two_men_holding_hands:
    :two_women_holding_hands: :dancer: :dancers: :ok_woman: :no_good: :information_desk_person: :raising_hand: :bow: :couplekiss:
    :couple_with_heart: :massage: :haircut: :nail_care: :boy: :girl: :woman: :man: :baby: :older_woman: :older_man: :man_with_gua_pi_mao: :man_with_turban:
    :construction_worker: :cop: :angel: :princess: :smiley_cat: :smile_cat: :heart_eyes_cat: :kissing_cat: :smirk_cat: :scream_cat: :crying_cat_face: :joy_cat:
    :pouting_cat: :japanese_ogre: :japanese_goblin: :see_no_evil: :hear_no_evil: :speak_no_evil: :guardsman: :skull: :feet: :lips: :kiss: :droplet: :ear: :eyes:
    :nose: :tongue: :love_letter: :bust_in_silhouette: :busts_in_silhouette: :speech_balloon: :thought_balloon: :feelsgood: :finnadie: :goberserk: :godmode:
    :hurtrealbad: :rage1: :rage2: :rage3: :rage4: :suspect: :trollface:

:bowtie: :smile: :laughing: :blush: :smiley: :relaxed: :smirk: :heart_eyes: :kissing_heart: :kissing_closed_eyes: :flushed: :relieved: :satisfied: :grin: :wink: :stuck_out_tongue_winking_eye: :stuck_out_tongue_closed_eyes: :grinning: :kissing: :kissing_smiling_eyes: :stuck_out_tongue: :sleeping: :worried: :frowning: :anguished: :open_mouth: :grimacing: :confused: :hushed: :expressionless: :unamused: :sweat_smile: :sweat: :disappointed_relieved: :weary: :pensive: :disappointed: :confounded: :fearful: :cold_sweat: :persevere: :cry: :sob: :joy: :astonished: :scream: :neckbeard: :tired_face: :angry: :rage: :triumph: :sleepy: :yum: :mask: :sunglasses: :dizzy_face: :imp: :smiling_imp: :neutral_face: :no_mouth: :innocent: :alien: :yellow_heart: :blue_heart: :purple_heart: :heart: :green_heart: :broken_heart: :heartbeat: :heartpulse: :two_hearts: :revolving_hearts: :cupid: :sparkling_heart: :sparkles: :star: :star2: :dizzy: :boom: :collision: :anger: :exclamation: :question: :grey_exclamation: :grey_question: :zzz: :dash: :sweat_drops: :notes: :musical_note: :fire: :hankey: :poop: :shit: :+1: :thumbsup: :-1: :thumbsdown: :ok_hand: :punch: :facepunch: :fist: :v: :wave: :hand: :raised_hand: :open_hands: :point_up: :point_down: :point_left: :point_right: :raised_hands: :pray: :point_up_2: :clap: :muscle: :metal: :fu: :star_struck: :runner: :running: :couple: :family: :two_men_holding_hands: :two_women_holding_hands: :dancer: :dancers: :ok_woman: :no_good: :information_desk_person: :raising_hand: :bow: :couplekiss: :couple_with_heart: :massage: :haircut: :nail_care: :boy: :girl: :woman: :man: :baby: :older_woman: :older_man: :man_with_gua_pi_mao: :man_with_turban: :construction_worker: :cop: :angel: :princess: :smiley_cat: :smile_cat: :heart_eyes_cat: :kissing_cat: :smirk_cat: :scream_cat: :crying_cat_face: :joy_cat: :pouting_cat: :japanese_ogre: :japanese_goblin: :see_no_evil: :hear_no_evil: :speak_no_evil: :guardsman: :skull: :feet: :lips: :kiss: :droplet: :ear: :eyes: :nose: :tongue: :love_letter: :bust_in_silhouette: :busts_in_silhouette: :speech_balloon: :thought_balloon: :feelsgood: :finnadie: :goberserk: :godmode: :hurtrealbad: :rage1: :rage2: :rage3: :rage4: :suspect: :trollface:

    :sunny: :umbrella: :cloud: :snowflake: :snowman: :zap: :cyclone: :foggy: :ocean: :cat: :dog: :mouse: :hamster: :rabbit: :wolf: :frog: :tiger: :koala: :bear:
    :pig: :pig_nose: :cow: :boar: :monkey_face: :monkey: :horse: :racehorse: :camel: :sheep: :elephant: :panda_face: :snake: :bird: :baby_chick: :hatched_chick:
    :hatching_chick: :chicken: :penguin: :turtle: :bug: :honeybee: :ant: :beetle: :snail: :octopus: :tropical_fish: :fish: :whale: :whale2: :dolphin: :cow2: :ram:
    :rat: :water_buffalo: :tiger2: :rabbit2: :dragon: :goat: :rooster: :dog2: :pig2: :mouse2: :ox: :dragon_face: :blowfish: :crocodile: :dromedary_camel: :leopard:
    :cat2: :poodle: :paw_prints: :bouquet: :cherry_blossom: :tulip: :four_leaf_clover: :rose: :sunflower: :hibiscus: :maple_leaf: :leaves: :fallen_leaf: :herb:
    :mushroom: :cactus: :palm_tree: :evergreen_tree: :deciduous_tree: :chestnut: :seedling: :blossom: :ear_of_rice: :shell: :globe_with_meridians: :sun_with_face:
    :full_moon_with_face: :new_moon_with_face: :new_moon: :waxing_crescent_moon: :first_quarter_moon: :waxing_gibbous_moon: :full_moon: :waning_gibbous_moon:
    :last_quarter_moon: :waning_crescent_moon: :last_quarter_moon_with_face: :first_quarter_moon_with_face: :crescent_moon: :earth_africa: :earth_americas:
    :earth_asia: :volcano: :milky_way: :partly_sunny: :octocat:

:sunny: :umbrella: :cloud: :snowflake: :snowman: :zap: :cyclone: :foggy: :ocean: :cat: :dog: :mouse: :hamster: :rabbit: :wolf: :frog: :tiger: :koala: :bear: :pig: :pig_nose: :cow: :boar: :monkey_face: :monkey: :horse: :racehorse: :camel: :sheep: :elephant: :panda_face: :snake: :bird: :baby_chick: :hatched_chick: :hatching_chick: :chicken: :penguin: :turtle: :bug: :honeybee: :ant: :beetle: :snail: :octopus: :tropical_fish: :fish: :whale: :whale2: :dolphin: :cow2: :ram: :rat: :water_buffalo: :tiger2: :rabbit2: :dragon: :goat: :rooster: :dog2: :pig2: :mouse2: :ox: :dragon_face: :blowfish: :crocodile: :dromedary_camel: :leopard: :cat2: :poodle: :paw_prints: :bouquet: :cherry_blossom: :tulip: :four_leaf_clover: :rose: :sunflower: :hibiscus: :maple_leaf: :leaves: :fallen_leaf: :herb: :mushroom: :cactus: :palm_tree: :evergreen_tree: :deciduous_tree: :chestnut: :seedling: :blossom: :ear_of_rice: :shell: :globe_with_meridians: :sun_with_face: :full_moon_with_face: :new_moon_with_face: :new_moon: :waxing_crescent_moon: :first_quarter_moon: :waxing_gibbous_moon: :full_moon: :waning_gibbous_moon: :last_quarter_moon: :waning_crescent_moon: :last_quarter_moon_with_face: :first_quarter_moon_with_face: :crescent_moon: :earth_africa: :earth_americas: :earth_asia: :volcano: :milky_way: :partly_sunny: :octocat:

    :bamboo: :gift_heart: :dolls: :school_satchel: :mortar_board: :flags: :fireworks: :sparkler: :wind_chime: :rice_scene: :jack_o_lantern: :ghost: :santa:
    :christmas_tree: :gift: :bell: :no_bell: :tanabata_tree: :tada: :confetti_ball: :balloon: :crystal_ball: :cd: :dvd: :floppy_disk: :camera: :video_camera:
    :movie_camera: :computer: :tv: :iphone: :phone: :telephone: :telephone_receiver: :pager: :fax: :minidisc: :vhs: :sound: :speaker: :mute: :loudspeaker: :mega:
    :hourglass: :hourglass_flowing_sand: :alarm_clock: :watch: :radio: :satellite: :loop: :mag: :mag_right: :unlock: :lock: :lock_with_ink_pen:
    :closed_lock_with_key: :key: :bulb: :flashlight: :high_brightness: :low_brightness: :electric_plug: :battery: :calling: :email: :mailbox: :postbox: :bath:
    :bathtub: :shower: :toilet: :wrench: :nut_and_bolt: :hammer: :seat: :moneybag: :yen: :dollar: :pound: :euro: :credit_card: :money_with_wings: :e-mail: 
    :inbox_tray: :outbox_tray: :envelope: :incoming_envelope: :postal_horn: :mailbox_closed: :mailbox_with_mail: :mailbox_with_no_mail: :package: :door: :smoking: 
    :bomb: :gun: :hocho: :pill: :syringe: :page_facing_up: :page_with_curl: :bookmark_tabs: :bar_chart: :chart_with_upwards_trend: :chart_with_downwards_trend: 
    :scroll: :clipboard: :calendar: :date: :card_index: :file_folder: :open_file_folder: :scissors: :pushpin: :paperclip: :black_nib: :pencil2: :straight_ruler:
    :triangular_ruler: :closed_book: :green_book: :blue_book: :orange_book: :notebook: :notebook_with_decorative_cover: :ledger: :books: :bookmark: :name_badge: 
    :microscope: :telescope: :newspaper: :football: :basketball: :soccer: :baseball: :tennis: :8ball: :rugby_football: :bowling: :golf: :mountain_bicyclist: 
    :bicyclist: :horse_racing: :snowboarder: :swimmer: :surfer: :ski: :spades: :hearts: :clubs: :diamonds: :gem: :ring: :trophy: :musical_score: :musical_keyboard: 
    :violin: :space_invader: :video_game: :black_joker: :flower_playing_cards: :game_die: :dart: :mahjong: :clapper: :memo: :pencil: :book: :art: :microphone: 
    :headphones: :trumpet: :saxophone: :guitar: :shoe: :sandal: :high_heel: :lipstick: :boot: :shirt: :tshirt: :necktie: :womans_clothes: :dress: 
    :running_shirt_with_sash: :jeans: :kimono: :bikini: :ribbon: :tophat: :crown: :womans_hat: :mans_shoe: :closed_umbrella: :briefcase: :handbag: :pouch: :purse: 
    :eyeglasses: :fishing_pole_and_fish: :coffee: :tea: :sake: :baby_bottle: :beer: :beers: :cocktail: :tropical_drink: :wine_glass: :fork_and_knife: :pizza: 
    :hamburger: :fries: :poultry_leg: :meat_on_bone: :spaghetti: :curry: :fried_shrimp: :bento: :sushi: :fish_cake: :rice_ball: :rice_cracker: :rice: :ramen: 
    :stew: :oden: :dango: :egg: :bread: :doughnut: :custard: :icecream: :ice_cream: :shaved_ice: :birthday: :cake: :cookie: :chocolate_bar: :candy: :lollipop: 
    :honey_pot: :apple: :green_apple: :tangerine: :lemon: :cherries: :grapes: :watermelon: :strawberry: :peach: :melon: :banana: :pear: :pineapple: :sweet_potato: 
    :eggplant: :tomato: :corn:

:bamboo: :gift_heart: :dolls: :school_satchel: :mortar_board: :flags: :fireworks: :sparkler: :wind_chime: :rice_scene: :jack_o_lantern: :ghost: :santa: :christmas_tree: :gift: :bell: :no_bell: :tanabata_tree: :tada: :confetti_ball: :balloon: :crystal_ball: :cd: :dvd: :floppy_disk: :camera: :video_camera: :movie_camera: :computer: :tv: :iphone: :phone: :telephone: :telephone_receiver: :pager: :fax: :minidisc: :vhs: :sound: :speaker: :mute: :loudspeaker: :mega: :hourglass: :hourglass_flowing_sand: :alarm_clock: :watch: :radio: :satellite: :loop: :mag: :mag_right: :unlock: :lock: :lock_with_ink_pen: :closed_lock_with_key: :key: :bulb: :flashlight: :high_brightness: :low_brightness: :electric_plug: :battery: :calling: :email: :mailbox: :postbox: :bath: :bathtub: :shower: :toilet: :wrench: :nut_and_bolt: :hammer: :seat: :moneybag: :yen: :dollar: :pound: :euro: :credit_card: :money_with_wings: :e-mail: :inbox_tray: :outbox_tray: :envelope: :incoming_envelope: :postal_horn: :mailbox_closed: :mailbox_with_mail: :mailbox_with_no_mail: :package: :door: :smoking: :bomb: :gun: :hocho: :pill: :syringe: :page_facing_up: :page_with_curl: :bookmark_tabs: :bar_chart: :chart_with_upwards_trend: :chart_with_downwards_trend: :scroll: :clipboard: :calendar: :date: :card_index: :file_folder: :open_file_folder: :scissors: :pushpin: :paperclip: :black_nib: :pencil2: :straight_ruler: :triangular_ruler: :closed_book: :green_book: :blue_book: :orange_book: :notebook: :notebook_with_decorative_cover: :ledger: :books: :bookmark: :name_badge: :microscope: :telescope: :newspaper: :football: :basketball: :soccer: :baseball: :tennis: :8ball: :rugby_football: :bowling: :golf: :mountain_bicyclist: :bicyclist: :horse_racing: :snowboarder: :swimmer: :surfer: :ski: :spades: :hearts: :clubs: :diamonds: :gem: :ring: :trophy: :musical_score: :musical_keyboard: :violin: :space_invader: :video_game: :black_joker: :flower_playing_cards: :game_die: :dart: :mahjong: :clapper: :memo: :pencil: :book: :art: :microphone: :headphones: :trumpet: :saxophone: :guitar: :shoe: :sandal: :high_heel: :lipstick: :boot: :shirt: :tshirt: :necktie: :womans_clothes: :dress: :running_shirt_with_sash: :jeans: :kimono: :bikini: :ribbon: :tophat: :crown: :womans_hat: :mans_shoe: :closed_umbrella: :briefcase: :handbag: :pouch: :purse: :eyeglasses: :fishing_pole_and_fish: :coffee: :tea: :sake: :baby_bottle: :beer: :beers: :cocktail: :tropical_drink: :wine_glass: :fork_and_knife: :pizza: :hamburger: :fries: :poultry_leg: :meat_on_bone: :spaghetti: :curry: :fried_shrimp: :bento: :sushi: :fish_cake: :rice_ball: :rice_cracker: :rice: :ramen: :stew: :oden: :dango: :egg: :bread: :doughnut: :custard: :icecream: :ice_cream: :shaved_ice: :birthday: :cake: :cookie: :chocolate_bar: :candy: :lollipop: :honey_pot: :apple: :green_apple: :tangerine: :lemon: :cherries: :grapes: :watermelon: :strawberry: :peach: :melon: :banana: :pear: :pineapple: :sweet_potato: :eggplant: :tomato: :corn:

    :house: :house_with_garden: :school: :office: :post_office: :hospital: :bank: :convenience_store: :love_hotel: :hotel: :wedding: :church: :department_store: 
    :european_post_office: :city_sunrise: :city_sunset: :japanese_castle: :european_castle: :tent: :factory: :tokyo_tower: :japan: :mount_fuji: 
    :sunrise_over_mountains: :sunrise: :stars: :statue_of_liberty: :bridge_at_night: :carousel_horse: :rainbow: :ferris_wheel: :fountain: :roller_coaster: :ship: 
    :speedboat: :boat: :sailboat: :rowboat: :anchor: :rocket: :airplane: :helicopter: :steam_locomotive: :tram: :mountain_railway: :bike: :aerial_tramway: 
    :suspension_railway: :mountain_cableway: :tractor: :blue_car: :oncoming_automobile: :car: :red_car: :taxi: :oncoming_taxi: :articulated_lorry: :bus: 
    :oncoming_bus: :rotating_light: :police_car: :oncoming_police_car: :fire_engine: :ambulance: :minibus: :truck: :train: :station: :train2: :bullettrain_front: 
    :bullettrain_side: :light_rail: :monorail: :railway_car: :trolleybus: :ticket: :fuelpump: :vertical_traffic_light: :traffic_light: :warning: :construction: 
    :beginner: :atm: :slot_machine: :busstop: :barber: :hotsprings: :checkered_flag: :crossed_flags: :izakaya_lantern: :moyai: :circus_tent: :performing_arts: 
    :round_pushpin: :triangular_flag_on_post: :jp: :kr: :cn: :us: :fr: :es: :it: :ru: :gb: :uk: :de:

:house: :house_with_garden: :school: :office: :post_office: :hospital: :bank: :convenience_store: :love_hotel: :hotel: :wedding: :church: :department_store: :european_post_office: :city_sunrise: :city_sunset: :japanese_castle: :european_castle: :tent: :factory: :tokyo_tower: :japan: :mount_fuji: :sunrise_over_mountains: :sunrise: :stars: :statue_of_liberty: :bridge_at_night: :carousel_horse: :rainbow: :ferris_wheel: :fountain: :roller_coaster: :ship: :speedboat: :boat: :sailboat: :rowboat: :anchor: :rocket: :airplane: :helicopter: :steam_locomotive: :tram: :mountain_railway: :bike: :aerial_tramway: :suspension_railway: :mountain_cableway: :tractor: :blue_car: :oncoming_automobile: :car: :red_car: :taxi: :oncoming_taxi: :articulated_lorry: :bus: :oncoming_bus: :rotating_light: :police_car: :oncoming_police_car: :fire_engine: :ambulance: :minibus: :truck: :train: :station: :train2: :bullettrain_front: :bullettrain_side: :light_rail: :monorail: :railway_car: :trolleybus: :ticket: :fuelpump: :vertical_traffic_light: :traffic_light: :warning: :construction: :beginner: :atm: :slot_machine: :busstop: :barber: :hotsprings: :checkered_flag: :crossed_flags: :izakaya_lantern: :moyai: :circus_tent: :performing_arts: :round_pushpin: :triangular_flag_on_post: :jp: :kr: :cn: :us: :fr: :es: :it: :ru: :gb: :uk: :de:

    :one: :two: :three: :four: :five: :six: :seven: :eight: :nine: :keycap_ten: :1234: :zero: :hash: :symbols: :arrow_backward: :arrow_down: :arrow_forward: 
    :arrow_left: :capital_abcd: :abcd: :abc: :arrow_lower_left: :arrow_lower_right: :arrow_right: :arrow_up: :arrow_upper_left: :arrow_upper_right: 
    :arrow_double_down: :arrow_double_up: :arrow_down_small: :arrow_heading_down: :arrow_heading_up: :leftwards_arrow_with_hook: :arrow_right_hook: 
    :left_right_arrow: :arrow_up_down: :arrow_up_small: :arrows_clockwise: :arrows_counterclockwise: :rewind: :fast_forward: :information_source: :ok: 
    :twisted_rightwards_arrows: :repeat: :repeat_one: :new: :top: :up: :cool: :free: :ng: :cinema: :koko: :signal_strength: :u5272: :u5408: :u55b6: :u6307: :u6708: 
    :u6709: :u6e80: :u7121: :u7533: :u7a7a: :u7981: :sa: :restroom: :mens: :womens: :baby_symbol: :no_smoking: :parking: :wheelchair: :metro: :baggage_claim: 
    :accept: :wc: :potable_water: :put_litter_in_its_place: :secret: :congratulations: :m: :passport_control: :left_luggage: :customs: :ideograph_advantage: :cl: 
    :sos: :id: :no_entry_sign: :underage: :no_mobile_phones: :do_not_litter: :non-potable_water: :no_bicycles: :no_pedestrians: :children_crossing: :no_entry: 
    :eight_spoked_asterisk: :sparkle: :eight_pointed_black_star: :heart_decoration: :vs: :vibration_mode: :mobile_phone_off: :chart: :currency_exchange: :aries: 
    :taurus: :gemini: :cancer: :leo: :virgo: :libra: :scorpius: :sagittarius: :capricorn: :aquarius: :pisces: :ophiuchus: :six_pointed_star: 
    :negative_squared_cross_mark: :a: :b: :ab: :o2: :diamond_shape_with_a_dot_inside: :recycle: :end: :back: :on: :soon: :clock1: :clock130: :clock10: :clock1030: 
    :clock11: :clock1130: :clock12: :clock1230: :clock2: :clock230: :clock3: :clock330: :clock4: :clock430: :clock5: :clock530: :clock6: :clock630: :clock7: 
    :clock730: :clock8: :clock830: :clock9: :clock930: :heavy_dollar_sign: :copyright: :registered: :tm: :x: :heavy_exclamation_mark: :bangbang: :interrobang: :o: 
    :heavy_multiplication_x: :heavy_plus_sign: :heavy_minus_sign: :heavy_division_sign: :white_flower: :100: :heavy_check_mark: :ballot_box_with_check: 
    :radio_button: :link: :curly_loop: :wavy_dash: :part_alternation_mark: :trident: :black_small_square: :white_small_square: :black_medium_small_square: 
    :white_medium_small_square: :black_medium_square: :white_medium_square: :black_large_square: :white_large_square: :white_check_mark: :black_square_button: 
    :white_square_button: :black_circle: :white_circle: :red_circle: :large_blue_circle: :large_blue_diamond: :large_orange_diamond: :small_blue_diamond: 
    :small_orange_diamond: :small_red_triangle: :small_red_triangle_down: :shipit:

:one: :two: :three: :four: :five: :six: :seven: :eight: :nine: :keycap_ten: :1234: :zero: :hash: :symbols: :arrow_backward: :arrow_down: :arrow_forward: :arrow_left: :capital_abcd: :abcd: :abc: :arrow_lower_left: :arrow_lower_right: :arrow_right: :arrow_up: :arrow_upper_left: :arrow_upper_right: :arrow_double_down: :arrow_double_up: :arrow_down_small: :arrow_heading_down: :arrow_heading_up: :leftwards_arrow_with_hook: :arrow_right_hook: :left_right_arrow: :arrow_up_down: :arrow_up_small: :arrows_clockwise: :arrows_counterclockwise: :rewind: :fast_forward: :information_source: :ok: :twisted_rightwards_arrows: :repeat: :repeat_one: :new: :top: :up: :cool: :free: :ng: :cinema: :koko: :signal_strength: :u5272: :u5408: :u55b6: :u6307: :u6708: :u6709: :u6e80: :u7121: :u7533: :u7a7a: :u7981: :sa: :restroom: :mens: :womens: :baby_symbol: :no_smoking: :parking: :wheelchair: :metro: :baggage_claim: :accept: :wc: :potable_water: :put_litter_in_its_place: :secret: :congratulations: :m: :passport_control: :left_luggage: :customs: :ideograph_advantage: :cl: :sos: :id: :no_entry_sign: :underage: :no_mobile_phones: :do_not_litter: :non-potable_water: :no_bicycles: :no_pedestrians: :children_crossing: :no_entry: :eight_spoked_asterisk: :sparkle: :eight_pointed_black_star: :heart_decoration: :vs: :vibration_mode: :mobile_phone_off: :chart: :currency_exchange: :aries: :taurus: :gemini: :cancer: :leo: :virgo: :libra: :scorpius: :sagittarius: :capricorn: :aquarius: :pisces: :ophiuchus: :six_pointed_star: :negative_squared_cross_mark: :a: :b: :ab: :o2: :diamond_shape_with_a_dot_inside: :recycle: :end: :back: :on: :soon: :clock1: :clock130: :clock10: :clock1030: :clock11: :clock1130: :clock12: :clock1230: :clock2: :clock230: :clock3: :clock330: :clock4: :clock430: :clock5: :clock530: :clock6: :clock630: :clock7: :clock730: :clock8: :clock830: :clock9: :clock930: :heavy_dollar_sign: :copyright: :registered: :tm: :x: :heavy_exclamation_mark: :bangbang: :interrobang: :o: :heavy_multiplication_x: :heavy_plus_sign: :heavy_minus_sign: :heavy_division_sign: :white_flower: :100: :heavy_check_mark: :ballot_box_with_check: :radio_button: :link: :curly_loop: :wavy_dash: :part_alternation_mark: :trident: :black_small_square: :white_small_square: :black_medium_small_square: :white_medium_small_square: :black_medium_square: :white_medium_square: :black_large_square: :white_large_square: :white_check_mark: :black_square_button: :white_square_button: :black_circle: :white_circle: :red_circle: :large_blue_circle: :large_blue_diamond: :large_orange_diamond: :small_blue_diamond: :small_orange_diamond: :small_red_triangle: :small_red_triangle_down: :shipit:

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
