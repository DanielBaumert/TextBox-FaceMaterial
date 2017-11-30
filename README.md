# TextBox - FaceMaterial - WinForm

<center>![logo]</center>



### Type One - Single line 
********************************************************
###### without Text 
 ![singlelineempty](https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/SingleLineEmpty.png)
 ![singleline](https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/SingleLine.png)
##### Settings 

|Line |               | Text  | |Control||
|:---|:-:|:-|:-:|:-|:-:
| LineColor | DodgerBlue | AutoScaleByText | false |BackColor |FromArgb(36, 36, 36)
| LineHeight  | 2 | ForeColor  | DodgerBlue |Padding | Padding(0, 0, 0, 2)
| LineMarginHorizontal  | 0 | Input  | null |
| LineMarginLeft  | 0 | Multiline  | false |
| LineMarginRight  | 1 | AutoScaleByText | false |
| LineMarginToText  | DodgerBlue | PasswortChar  | '\0' |
|PatterError|Firebrick|Patter| null
|||UseSystemPasswordChar| false

```csharp
// 
// SingleLineTextBox
// 
this.SingleLineTextBox.AutoScaleByText = false;
this.SingleLineTextBox.BackColor = System.Drawing.Color.FromArgb(36, 36, 36);
this.SingleLineTextBox.ForeColor = System.Drawing.Color.DodgerBlue;
this.SingleLineTextBox.Input = null;
this.SingleLineTextBox.IsntInput = null;
this.SingleLineTextBox.LineColor = System.Drawing.Color.DodgerBlue;
this.SingleLineTextBox.LineHeight = 2;
this.SingleLineTextBox.LineMarginHorizontal = 0;
this.SingleLineTextBox.LineMarginLeft = 0;
this.SingleLineTextBox.LineMarginRight = 0;
this.SingleLineTextBox.LineMarginToText = 1;
this.SingleLineTextBox.Margin = new System.Windows.Forms.Padding(4, 5, 4, 5);
this.SingleLineTextBox.Multiline = false;
this.SingleLineTextBox.Name = "SingleLineTextBox";
this.SingleLineTextBox.Padding = new System.Windows.Forms.Padding(0, 0, 0, 2);
this.SingleLineTextBox.PasswortChar = '\0';
```
	
### Type Two - Multi line

### Type Three - Passwort

### Type Four - Patter

### Type Five - Multi line auto size vertical

Basic useful feature list:

 * Ctrl+S / Cmd+S to save the file
 * Ctrl+Shift+S / Cmd+Shift+S to choose to save as Markdown or HTML
 * Drag and drop a file into here to load it
 * File contents are saved in the URL so you can share files


I'm no good at writing sample / filler text, so go write something yourself.

Look, a list!

 * foo
 * bar
 * baz

And here's some code! :+1:

```javascript
$(function(){
  $('div').html('I am a div.');
});
```

This is [on GitHub](https://github.com/jbt/markdown-editor) so let me know if I've b0rked it somewhere.


Props to Mr. Doob and his [code editor](http://mrdoob.com/projects/code-editor/), from which
the inspiration to this, and some handy implementation hints, came.

### Stuff used to make this:

 * [markdown-it](https://github.com/markdown-it/markdown-it) for Markdown parsing
 * [CodeMirror](http://codemirror.net/) for the awesome syntax-highlighted editor
 * [highlight.js](http://softwaremaniacs.org/soft/highlight/en/) for syntax highlighting in output code blocks
 * [js-deflate](https://github.com/dankogai/js-deflate) for gzipping of data to make it fit in URLs
 
[singlelineempty]: https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/SingleLineEmpty.png
[singleline]: https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/SingleLine.png
[logo]: https://github.com/facebamm/TextBox-FaceMaterial/raw/master/Images/Form.png 
