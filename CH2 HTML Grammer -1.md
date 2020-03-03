# HTML -- Web Language
HTML(HyperText MarkUp Language) tells the browser how the text is structured by "making up" the text with tags.

# Html Basic Tags -- sturcture
- \<html\>
- \<head\>
- \<title\>
- \<body\>

## What's in \<head\>...\</head\>
- The \<base\> tag is used to create a "base" url for all links on the pages.
- The \<object\> tag is designed to include images, JavaScripts objects, Flasj animations, MP3 files, QuickTime movies and other components of a page.
- The \<link\> tag is used to link to an external file, such as a style sheet or JavaScript file.
- The \<style\> tag is used to include CSS rules inside the document.
- The \<script\> tag is used to include JavaScript or VBScript inside the document.
- The \<meta\> tags includes information about the document such as keywords and a description, which are particularly helpful for search application.

a \<head\> example:
``` html
<head>
  <title>HTML Basic Tags</title>
  <meta name="Keywords" content="HTML, Web Pages" />
  <meta name="description" content="HTML Basic Tags" />
  <base href="Http://www.tutorialspoint.com" />
  <link rel="stylesheet" type="text/css" href="tp.css" />
  <script type="text/javascript">
    -uacct = "UA-232293";
    urchinTracker();
  </script>
</head>
```

# HTML Grammer

## HTML tags so far
- Structures:
    - \<html\>\</html\>, \<head\>\</head\>, \<title\>\</title\>, \<body\>\</body\>
- Paragraphs:
    - \<p\>\</p\>
- Headings:
    - \<h1\>\</h1\>, \<h2\>\</h2\>, ..., \<h6\>\</h6\>
- Images:
    - \<img scr="..." /\>
- Horizontal line:
    - \<hr\>
- Emphasis:
    - \<em\>...\</em\>
    - \<strong\>...\</strong\>

## Fonts
- Font tags:
    - \<sup\>\</sup\> -- superscript text
    - \<sub\>\</sub\> -- subscript text
    - \<em\>\</em\> -- emphasized text
    - \<i\>\</i\> -- italic text
    - \<strong\>\</strong\> -- strong text
    - \<b\>\</b\> -- boldface text
- Special text formatting by adding font tags or attributes
    - Font tag with attributes face, size, color:
    ``` html
    <font face="arial, sans-serif, 'times roman'" size="14px" color="green"> ...</font>
    ```
    - Add attributes to other elements:
    ``` html
    <p style="font-style: italic; font-family: arial, sans-serif, 'times roman'; font-size: 14px; color: green"></p>
    ```

## Align
- Align text on a page
    1. By adding aligning attribute "align=..." to an element, values may be "left, center, right"
    2. By adding a tag \<center\>\</center\>
    3. By adding style margin attributes to elements
        - style="margin-left: 20"
        - style="margin-top: 20"
        - style="margin-right: 20"
        - style="margin-botton: 20"

## List tags
- Ordered list
    ``` html
    <ol>
        <li></li>
        <li></li>
    </ol>
    ```
- Unordered list
    ``` html
    <ul>
        <li></li>
        <li></li>
    </ul>
    ```
