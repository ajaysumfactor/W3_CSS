# W3_CSS


# BOX MODAL
### Overview
    1. Box modal describes the layout of the element.The HTML Elements are considered as boxes.
    2. The CSS Box modal is essentially a box that wraps around every HTML elemnt.
    3. Consists of(margins,borders,padding,content).
    4. Total width=total_horizontal_margin+border+padding+content_width of element.

# CSS OUTLINE
### Overview
    1. An outline is a line drawn outside the border.
    2. the element's total width and height is not affected by the width of the outline .
    3. it has following properties
##### outline-style
    dotted - Defines a dotted outline
    dashed - Defines a dashed outline
    solid - Defines a solid outline
    double - Defines a double outline
    groove - Defines a 3D grooved outline
    ridge - Defines a 3D ridged outline
    inset - Defines a 3D inset outline
    outset - Defines a 3D outset outline
    none - Defines no outline
    hidden - Defines a hidden outline

#### None of the other outline properties will have ANY effect unless the outline-style property is set!

##### Outline-width(specifies the width of the outline,and can have one of the following values)
    value(thin/medium/thick/px/pt/cm/em)

##### Outline-color:name/HEX/RGB/HSL;
##### Outline shorthand property
    outline: outline-width outline-style outline-color;
##### outline-offset (make a space between border and the outline)
        outline-offset: px;

# CSS Text
#### color property--set the color to the text
    1. color: name/hex/rgb;
    2. text-alignment
        text-align-->set horizontal alignment of a text;
        text-align-last-->  how to align the last line of a text
        direction-->properties can be used to change the text direction of an element:
        unicode-bidi
        vertical-align:--> Set the vertical alignment of an image in a text: 
    3. text-decoration-line/color/style/thickness
    4. text-spacing
        text-indent:length;
        letter-spacing:length;
        line-height: length;
        word-spacing: length;
        whitespace:nowrap;
    5. text-shadow: horizontal vertical blur color;

# CSS FONT
    Generic font family
    1. serif
    2. sans-serif
    3. Monospace
    4. Cursive
    5. Fantasy
#### Web safe font?
    Web safe fonts are fonts that are universally installed across all browsers and devices.
#### Fallback fonts

# Icons
    fontawesome
    bootstrap icon
    google icons

# CSS Links
#### Styling Links
    1. a:link - a normal, unvisited link
    2. a:visited - a link the user has visited
    3. a:hover - a link when the user mouses over it
    4. a:active - a link the moment it is clicked
   
#### Text-decoration(mostly use to remove underline )
#### Background-color
#### Link Buttons

# CSS List
###  Types
    1. Ordered list 
    2. unordered list
### property
    list-style-type: square/circle/upper-roman;
    list-style-image: url('');
    list-style-position: outside/inside;
### Shorthand property
    list-style: list-style-type list-style-position list-style-image;
### removing default style setting in list
    list-style-type: none;
    margin:0;
    padding:0;

# CSS Table
    1. border-collapse: collapse;
    2. text-align: center;
    3. vertical-align: top/bottom/middle;
    4. table-style/can give margin/padding/background-color/color;


# DISPLAY
    1. CSS Property for controlling layout.
    2. Specifies how element is displayed.
    3. display:inline/block/inline-block/none.

#### inline display
    1. element does not start in a new line.
    2. only takes up as much width as necessary.
    3. can not set height and width.
    4. vertical margin will not work.
#### Block display
    1. Element starts in a new line.
    2. Takes up full-width of the parent element.
#### display: inline-block;
    1. height and width of element can be set now.
    2. vertical margin is allowed.
    3. element can sit next to each other.
#### display: none
    1. property hides the elements in a browser. It actually removes the element from the HTML page and nothing is shown in its place.
#### visibility: hidden;
    1. the element is not removed from the page and still occupies












 