# HTML Form

## What is an HTML form?
An HTML form is part of a web page that includes areas where users can enter information to be sent/submit
- back to you
- to another email address
- to a database that you manage
- to a third-party management system
- ...

## How to submit the finished form
Forms include a submission button for the user to submit the form, When someone clicks the button, all the information typed in the form is sent to a URL specified in the action attribute of the &lt;form&gt; tag.

## &lt;form&gt; tag
- &lt;form name="..." action="..." method="..." enctype="..."&gt;

- name: form's name
- action: target URL for submission
- method: submitting methods, include get/post
- enctype: MIME_type, data coding type

## Form data items
text | password | checkbox | radio | image | file | hidden | button | submit | reset

## &lt;input type="text"&gt;
``` html
<input name="..." type="text" maxlength="..." size="..." value="..."/>
```
- for single text line
- maxlength: max length of typed string
- size: width of this input area
- value: default text

## &lt;input type="password"&gt;
``` html
<input name="..." type="password" maxlength="..." size="..."/>
```
- password isn't shown in plain text.

## &lt;input type="checkbox"&gt;
``` html
<input name="..." type="checkbox" checked="checked"/>
```
- for check options

## &lt;input type="radio"&gt;
``` html
<input name="..." type="radio" checked="checked"/>
```
- for a single radio
- name: radio in a group have the same name

## &lt;input type="image"&gt;
``` html
<input name="..." type="image" src="..." width="..." height="..."/>
```
- for photos, images shown in the form, acting as a submit button
- src: image's URL
- width, height: images size in px

## &lt;input type="file"&gt;
``` html
<input name="..." type="file">
```
- for uploading a file

## &lt;input type="button"&gt;
``` html
<input name="..." type="button" value="..." onclick="..."/>
```
- for normal buttons
- value: text shown on this button
- on click:script for the click event

## &lt;input type="submit"&gt;
``` html
<input name="..." type="submit" value="..."/>
```
- for submitting the entire form data using the form action
- value: text shown on the button

## &lt;input type="reset"&gt;
``` html
<input name="..." type="reset" value="..."/>
```
- for resetting the entire form data
- value: text shown on the button

## &lt;input type="hidden"&gt;
``` html
<input name="..." type="hidden" value="..."/>
```
- for hiding a data piece
- value: plain text

## Multi-line form element
- &lt;input type="..."/&gt; are single-line form elements, there are multi-line form elements, too:
    - &lt;textarea&gt;
    - &lt;select&gt; + &lt;option&gt;
    - &lt;fieldset&gt; + &lt;legend&gt;

### &lt;textarea&gt;
``` html
<textarea name="..." rows="..." cols="..." wrap="..."/>
```
- rows, cols : numbers
- wraps: wrap | virtual | physics | off
    - wrap | off: no wrap
    - virtual | physics: word wrap

### &lt;select&gt;
``` html
<select name="..." size="..." multiple="multiple"/>
```
- size: visible options
- multiple: single | multiple choice
- inside are &lt;option&gt;
    - &lt;option value="..." selected&gt;

### &lt;fieldset&gt;: grouping form elements
``` html
<fieldset>
  <legend>group caption</legend>
  <input .../>
  <input .../>
</fieldset>
```