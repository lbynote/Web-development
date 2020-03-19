# What is CSS?
- Cascading Style Sheet(级联样式表)
    - A style sheet is a grouping of formatting instructions that controls the appearance of several HTML pages at home.
        - like: typeface controls, letter and line spacing, and margins and page borders.
    - Cascading
        - for a formatting property of a single elements, if there are serveral formatting instructions, whichi one will take effect?
    - CSS is a language that defines style constructs such as fonts, colors, and positioning, to describe how information on web pages is formatted and displayed.

# How CSS works?
- CSS styles can be stored
    - directly in an HTML web page
        - inline style or internal style sheet
    - or in a separate style sheet file
        - external style sheet (*.css)
- Style sheets contain style rules that apply styles to elements of given types.

# Ways to use CSS
- Inline styles
    -   ``` html
        <h1 style="color: white; background-color: blue;">Menu</h1>
        ```
- Internal(embedded) styles -- enclosed by &lt;head&gt;...&lt;head&gt;
    - using tag &lt;style&gt;...&lt;/style&gt;
- External styles -- enclosed by &lt;head&gt;...&lt;head&gt;
    -   ``` html
        <link href="*.css" rel="stylesheet" type="text/css">
        ```
    -   ``` html
        <style>@import"*.css";</style>
        ```

# Style rules
- A style rule is a formatting/positioning instruction that can be applied to one or a group of html elements.
- Style rules = style properties : associated values.
    - "color: darked; font-size: 26px; font-family: cursive;"
- Cascading -- the manner in which style sheet rules are applied to html elements.
    - CSS styles form a hierarchy in which more specific styles override more general styles.

``` css
selector {
    property 1: value 1;
    property 2: value 2;
    ...
}
```

# CSS style primer
Css style properties can be grouped into two major categories:
- Layout properties -- properties that afect the positioning of elements on a web page:
    - margins, padding, alignment, and so on
- Formatting properties -- properties that affect the visual display of elements within a website:
    - font type, size, color, and so on.

# Basic selectors
- Selectors -- which elements is the CSS style rule applied to?
- Three elementary types:
    - Tag: body{}, p{}, h1{}, div{}
    - Class: .sel{}
    - ID: #div{}