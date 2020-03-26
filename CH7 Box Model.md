# Positioning Style Properties
| property | value | remark |
| :-: | :-: | :-: |
| position | relative \| static \| absolute \| fixed | absolute/fix + left/top |
| left \| top | px | image bullet |
| width \| height | px | |
| float | left \| right \| none | |
| clear | left \| right \| both \| none | to clear floating style |
| z-index | block \| inline \| none | none: hidden |

# CSS Box Model
- Every element in HTML is represented by CSS box model
    - content: box center
    - padding: around the content;  
    it inherits the background color of the content area
    - border: extends around the element, on the outer edge of any padding  
    It's type, width, and color can differ
    - margin: the area outside of the element, it never has color(transparent).

![boxmodel](/img/boxmodel.jpg/)

# Box Style Properties
- list proeperties 
    | property | value | remark |
    | :-: | :-: | :-: |
    | margin-(top \| right \| botton \| left) | px \| % \| auto \| ... |
    | border-(style \| width \| color) | none \| solid \| dotted \| dashed \| doubled \|...<br />medium \| thin \| thick \| px | image bullet |
    | padding-(top \| right \| botton \| left) | px \| % \| auto \| ... | |

# CSS+DIV Layout
- HTML elements organized using CSS+DIV could sparate web content and style away
    - design div layout
    - css style

![CSS&DIV](/img/CSS&DIV.jpg/)