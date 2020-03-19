# Basic CSS Selectors
- Tag selector: body{}, p{}, a{}
- Class selector: .className{}
    ``` html
    <p class="c1">...</p>
    ```
- ID selector: #idName{}
    ``` html
    <p id="c1">...</p>
    ```

# Psuedo-Class（伪类） selector
- Tag, class, and id selelctors pick complete html elements.
- There are some parts of an html element, or its special moments need special style -- Pseudo-class Selector

| pseudo-class | remark|
| :-: | :-: |
| link | unvisited &lt;a&gt; |
| hover | hovered &lt;a&gt; |
| active | pressed down but not up &lt;a&gt; |
| visited | visited &lt;a&gt; |
| first-letter | first letter of a block |
| first-line | first line of a block |
| first-child | first child of a parent |

# Selector Declaration
- collective decalration:
    declare a group of selectors sharing common styes by using:
    -   ``` css
        h1, h2, h3, h4, h5 {color: purple;}
        ```
    -   ``` css
        p.special, #one {font-size: 16px; color: #1e1e1e;}
        ```
- derived declaration:
    using the context to change
    -   ``` css
        li strong {font-weight: normal; font-style: italic;}
        ```

# Formatting style properties
- font properties:
    | property | value |
    | :-: | :-: |
    | font-size | size unit: px, %, em, ex |
    | font-style | normal \| italic \| oblique |
    | font-weight | normal \| bold \| bolder \| lighter \| 100~900 |
    | font-variant | normal \| small-caps |
    | font-family | times new roman \| arial \| bangla \| chalkboard \| ... |
- Special formatting properties:
    | property | value | remark |
    | :-: | :-: | :-: |
    | letter-spacing 字间距 | normal \| px \| % | between letters |
    | text-indect 首行缩进 | normal \| px \| % | for paragraphes |
    | text-decoration 文字装饰 | none \| blink \| underline \| line-through \|overline | special effect |
    | text-transform 英文大小写 | none \| capitalize \| uppercase \| lowercase | for English text |
    | text-align 水平对齐 | left \| right \| center \| justify | horizontal |
    | vertical-align 垂直对齐 | baselien \| top \| middle \| botton \| ... | for child element |
    | line-height 行距 | normal \| px \| ex \| em | |
- background & color properties:
    | property | value | remark |
    | :-: | :-: | :-: |
    | color | rgb(%, %, %) \| rgb(num, num, num) \| #FFFFFF \| #FFF \| colorname \| foreground color |
    | background-color | rgb(%, %, %) \| rgb(num, num, num) \| #FFFFFF \| #FFF \| colorname | |
    | background-image | none \| url("bg.jpg") | image file/url |
    | background-repeat | no-repeat \| repeat-x \| repeat-y | |
    | background-position | left \| center \| right \| x% \| x_pos | x-position |
    | background-position | top \| center \| top \| y% \| y_pos | y_position |
- list properties:
    | property | value | remark |
    | :-: | :-: | :-: |
    | list-style-type | disc \| square \| decimal \| lower-roman \| upper-roman \| upper-alpha \| lower-alpha \| none | unordered ordered |
    | list-style-image | none \| url("xxx.jpg") | image bullet |
    | list-style-position | outside \| inside | image file/url |

# New tags: &lt;div&gt; & &lt;span&gt;
- &lt;div&gt; and &lt;span&gt; are both html tags that help apply CSS styles
    - &lt;div&gt;: division, block element, container, might contain &lt;span&gt;
    - &lt;span&gt;: span, inline element, container, might not contain &lt;div&gt;
    - they always have the properties of id or class to be referred to
    - nested &lt;div&gt; elements are used as web page layers

# &lt;div&ht; properties
- class / id / width / height
- border / background
- position: relative | fixed | absolute
- left/top: px | %
- float: left | right | none
- clear: left | right | both | none
- z-index: auto | 1 | 2 | ...