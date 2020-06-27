# Brief Reference HTML

**Brief Reference HTML** is a concise reference of the HTML markup language.

---

#### Comment
```
<!-- This is a comment -->
```

#### Basic element syntax
```
<element attribute1="value1" attribute2="value2"></element>
```

#### Basic page structure
```
<html>
    <head>
    </head>
    <body>
    </body>
</html>
```

#### Tell to the browser that is a HTML5 file
```
<!DOCTYPE html>
```

#### Incude a JavaScript file
```
<html>
    <head>
    </head>
    <body>
        <script src="script.js">
        </script>
    </body>
</html>
```

#### Link to a CSS StyleSheet file
```
<html>
    <head>
        <link href="css/style.css" type="text/css" rel="stylesheet" />
    </head>
    <body>
    </body>
</html>
```

#### Create a link
```
<a href='>images</a>
```

#### Display an image
```
<img src="images/happy.jpg"/>
```

#### Create an unorderer list
```
<p>Unorderer List</p>
<ul>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3</li>
</ul>
```

#### Create an orderer list
```
<p>Orderer List</p>
<ol>
    <li>List item 1</li>
    <li>List item 2</li>
    <li>List item 3</li>
</ol>
```

#### Create a hard line break
```
<br/>
```

#### Display emphasized Text Inside a Paragraph
```
<p>This is the <em>emphasized</em> text</p>
```

#### Display bold elements
```
<p>This is a <strong>strong</strong>text<p>
```

#### Hard break
```
<br/>
```


#### Create a link
```
<a href='>images</a>
```

#### Open a link in a new tab
```
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank">
    Mozilla Developer Network 
</a>
```

#### Specify the width of an image
```
<img src="images/mochi.png" width="75"/>
```

#### Specify alternative text to an image
```
<img src="images/mochi.gif" width="75" alt="Dancing ball"/>
```

#### Specify the document language
```
<html lang="en">
    ...
</html>
```

#### Use the reserved characters
```
<p>
    Three reserved characters in HTML: &lt; &gt; and &amp;.
</p>
```

#### Specify the charset
```
<head>
    <meta charset="UTF-8"/>
</head>
```

#### Strike deleted text
```
<p>This is a <del>deleted</del> text.</p>
```

#### Underline text
```
<p>This is an <ins>underline</ins> text.</p>
```

#### Define specific styles
```
<style>
    body {
        color: #0000FF;
    }
</style>
```

#### Define an inline style
```
<a href="nowhere.html" style="color: #990000; text-decoration: line-through;">obsolete link</a>. This is your chance!
```

#### Prevent margin collapse
```
<div style="margin-top: 1px"></div>
```

#### Point to specific part of a web page with url fragments from the same page
```
<a href="#button-2">Go to Button Two</a>
```

#### Point to specific part of a web page with url fragments from a different page
```
<a href="selectors.html#button-2">Go to Button Two</a>
```

#### Disable the default zoom enabled on mobile devices
```
<meta name="viewport" content="width=device-width, initial-scale-1.0, maximum-scale=1.0">
```

#### Basic form
```
<form action="" method="get" class="speaker-form">
    <div class="form-row">
        <label for="full-name">Name</label>
        <input id="full-name" name="full-name" type="text"/>
    </div>
</form>
```

#### Define a text area
```
<textarea>
</textarea>
```
