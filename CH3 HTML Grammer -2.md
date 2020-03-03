# Tag Architecture
tag archiecture:
![tag architecture](/img/tagArchitecture.jpg/)

# Comments
``` html
<!-- ... -->
```

the commented out html instructions will not be ecevuted by the browser even if they still present in the html doc.

# Specific Symbols (Character Entity)
![character entity](/img/characterEntity.jpg/)

# Hyperlinks
``` html
<a href="..." title="..." target="...">...</a>
```
Hyperlink Tag &lt;a&gt;: to connect two points wither inside the same document or in individual documents.  

Two types of connections:
- External Links: &lt;a href="..."&gt;External Link&lt;/a&gt;
- Internal Links: &lt;a name="..."&gt;Internal Link&lt;/a&gt;

For example:
``` html
external link:
<a href="www.lbyuoe.com">lbyuoe</a>

internal link
<a name="anchor1"></a>
<a href="#anchor1">link to anchor1</a>
```

# Table

## Table Tags
tags:
``` html
<table></table>: table
<caption></caption>: caption
<tr></tr>: table row
<th></th>: table heading
<td></td>: table cell
```

## Table Attributes
``` html
· border, cellspacing, cellpadding --- for <table>
· colspan / rowspan -- for <th>/<td>
· align="left|right|center" -- for <tr>/<th>/<td>
· valign="top|botton|center" -- for <th>/<td>
```