# TextBox - FaceMaterial - WinForm

<center>![form](https://github.com/facebamm/TextBox-FaceMaterial/raw/master/Images/Form.png)</center>

### Type One - Single line 
********************************************************
###### without text and with text
 * ![singlelineempty](https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/SingleLineEmpty.png)
 * ![singleline](https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/SingleLineFill.png)
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
|||CueText|Text

```csharp
// 
// SingleLineTextBox
// 
this.SingleLineTextBox.AutoScaleByText = false;
this.SingleLineTextBox.BackColor = System.Drawing.Color.FromArgb(36, 36, 36);
this.SingleLineTextBox.ForeColor = System.Drawing.Color.DodgerBlue;
this.SingleLineTextBox.CueText = "Text";
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
this.SingleLineTextBox.Patter = null;
this.SingleLineTextBox.PatterError = System.Drawing.Color.Red;
this.SingleLineTextBox.UseSystemPasswordChar = false;
```
	
### Type Two - Multi line
********************************************************
###### With two lines and three lines
 * ![singlelineempty](https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/MultiLineFixSize1.png)
 * ![singleline](https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/MultiLineFixSize2.png)
##### Settings 

|Line |               | Text  | |Control||
|:---|:-:|:-|:-:|:-|:-:
| LineColor | DodgerBlue | AutoScaleByText | false |BackColor |FromArgb(36, 36, 36)
| LineHeight  | 2 | ForeColor  | DodgerBlue |Padding | Padding(0, 0, 0, 2)
| LineMarginHorizontal  | 0 | Input  | null |
| LineMarginLeft  | 0 | Multiline  | **true** |
| LineMarginRight  | 1 | AutoScaleByText | false |
| LineMarginToText  | DodgerBlue | PasswortChar  | '\0' |
|PatterError|Firebrick|Patter| null
|||UseSystemPasswordChar| false

```csharp
// 
// MultiLineTextBox
// 
this.MultiLineTextBox.AutoScaleByText = false;
this.MultiLineTextBox.BackColor = System.Drawing.Color.FromArgb(36, 36, 36);
this.MultiLineTextBox.CueText = "";
this.MultiLineTextBox.ForeColor = System.Drawing.Color.DodgerBlue;
this.MultiLineTextBox.Input = null;
this.MultiLineTextBox.IsntInput = null;
this.MultiLineTextBox.LineColor = System.Drawing.Color.DodgerBlue;
this.MultiLineTextBox.LineHeight = 2;
this.MultiLineTextBox.LineMarginHorizontal = 0;
this.MultiLineTextBox.LineMarginLeft = 0;
this.MultiLineTextBox.LineMarginRight = 0;
this.MultiLineTextBox.LineMarginToText = 1;
this.MultiLineTextBox.Margin = new System.Windows.Forms.Padding(4, 5, 4, 5);
this.MultiLineTextBox.Multiline = true;
this.MultiLineTextBox.Name = "MultiLineTextBox";
this.MultiLineTextBox.Padding = new System.Windows.Forms.Padding(0, 0, 0, 2);
this.MultiLineTextBox.PasswortChar = '\0';
this.MultiLineTextBox.Patter = null;
this.MultiLineTextBox.PatterError = System.Drawing.Color.Red;
this.MultiLineTextBox.UseSystemPasswordChar = false;
```	

### Type Three - Passwort
###### without password and with paassword
 * ![singlelineempty](https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/PasswordEmpty.png)
 * ![singleline](https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/PasswordFill.png)
##### Settings 

|Line |               | Text  | |Control||
|:---|:-:|:-|:-:|:-|:-:
| LineColor | DodgerBlue | AutoScaleByText | false |BackColor |FromArgb(36, 36, 36)
| LineHeight  | 2 | ForeColor  | DodgerBlue |Padding | Padding(0, 0, 0, 2)
| LineMarginHorizontal  | 0 | Input  | null |
| LineMarginLeft  | 0 | Multiline  | false |
| LineMarginRight  | 1 | AutoScaleByText | false |
| LineMarginToText  | DodgerBlue | PasswortChar  | **'●'** |
|PatterError|Firebrick|Patter| null
|||UseSystemPasswordChar| **true**
|||CueText|**Passwort**
```csharp
// 
// MultiLineTextBox
// 
this.PasswordTextBox.AutoScaleByText = false;
this.PasswordTextBox.BackColor = System.Drawing.Color.FromArgb(36, 36, 36);
this.PasswordTextBox.CueText = "Passwort";
this.PasswordTextBox.ForeColor = System.Drawing.Color.DodgerBlue;
this.PasswordTextBox.Input = null;
this.PasswordTextBox.IsntInput = null;
this.PasswordTextBox.LineColor = System.Drawing.Color.DodgerBlue;
this.PasswordTextBox.LineHeight = 2;
this.PasswordTextBox.LineMarginHorizontal = 0;
this.PasswordTextBox.LineMarginLeft = 0;
this.PasswordTextBox.LineMarginRight = 0;
this.PasswordTextBox.LineMarginToText = 1;
this.PasswordTextBox.Margin = new System.Windows.Forms.Padding(4, 5, 4, 5);
this.PasswordTextBox.Multiline = false;
this.PasswordTextBox.Name = "PasswordTextBox";
this.PasswordTextBox.Padding = new System.Windows.Forms.Padding(0, 0, 0, 2);
this.PasswordTextBox.PasswortChar = '●';
this.PasswordTextBox.Patter = null;
this.PasswordTextBox.PatterError = System.Drawing.Color.Red;
this.PasswordTextBox.UseSystemPasswordChar = true;
```	

### Type Four - Patter
###### without password and with paassword
 * ![PatterEmpty](https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/PatterEmpty.png)
 * ![PatterWrong](https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/PatterWrong.png) 
 * ![PatterRight](https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/PatterRight.png)
##### Settings 

|Line |               | Text  | |Control||
|:---|:-:|:-|:-:|:-|:-:
| LineColor | DodgerBlue | AutoScaleByText | false |BackColor |FromArgb(36, 36, 36)
| LineHeight  | 2 | ForeColor  | DodgerBlue |Padding | Padding(0, 0, 0, 2)
| LineMarginHorizontal  | 0 | Input  | null |
| LineMarginLeft  | 0 | Multiline  | false |
| LineMarginRight  | 1 | AutoScaleByText | false |
| LineMarginToText  | DodgerBlue | PasswortChar  | '\0' |
|PatterError|Firebrick|Patter| **Daniel**
|IsntInput|**FromArgb(64, 64, 64)**|UseSystemPasswordChar| false
|||CueText|**Geben sie Daniel ein!**
```csharp
// 
// PatterTextBox
// 
this.PatterTextBox.AutoScaleByText = false;
this.PatterTextBox.BackColor = System.Drawing.Color.FromArgb(36, 36, 36);
this.PatterTextBox.CueText = "Geben sie Daniel ein!";
this.PatterTextBox.ForeColor = System.Drawing.Color.DodgerBlue;
this.PatterTextBox.Input = null;
this.PatterTextBox.IsntInput = System.Drawing.Color.FromArgb(64, 64, 64);
this.PatterTextBox.LineColor = System.Drawing.Color.DodgerBlue;
this.PatterTextBox.LineHeight = 2;
this.PatterTextBox.LineMarginHorizontal = 0;
this.PatterTextBox.LineMarginLeft = 0;
this.PatterTextBox.LineMarginRight = 0;
this.PatterTextBox.LineMarginToText = 1;
this.PatterTextBox.Multiline = false;
this.PatterTextBox.Name = "PatterTextBox";
this.PatterTextBox.Padding = new System.Windows.Forms.Padding(0, 0, 0, 2);
this.PatterTextBox.PasswortChar = '\0';
this.PatterTextBox.Patter = "Daniel"; //Regex/Patter supported
this.PatterTextBox.PatterError = System.Drawing.Color.Firebrick;
this.PatterTextBox.UseSystemPasswordChar = false;
```	
### Type Five - Multi line auto size vertical
###### With two lines and three lines
 * ![MultiLineAutoSize1](https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/MultiLineAutoSize1.png)
 * ![MultiLineAutoSize2](https://github.com/facebamm/TextBox-FaceMaterial/blob/master/Images/MultiLineAutoSize12.png)
##### Settings 

|Line |               | Text  | |Control||
|:---|:-:|:-|:-:|:-|:-:
| LineColor | DodgerBlue | AutoScaleByText | false |BackColor |FromArgb(36, 36, 36)
| LineHeight  | 2 | ForeColor  | DodgerBlue |Padding | Padding(0, 0, 0, 2)
| LineMarginHorizontal  | 0 | Input  | null |
| LineMarginLeft  | 0 | Multiline  | **true** |
| LineMarginRight  | 1 | AutoScaleByText | **true** |
| LineMarginToText  | DodgerBlue | PasswortChar  | '\0' |
|PatterError|Firebrick|Patter| null
|||UseSystemPasswordChar| false

```csharp
// 
// MultiLineTextBox
// 
this.MultiLineTextBox.AutoScaleByText = false;
this.MultiLineTextBox.BackColor = System.Drawing.Color.FromArgb(36, 36, 36);
this.MultiLineTextBox.CueText = "";
this.MultiLineTextBox.ForeColor = System.Drawing.Color.DodgerBlue;
this.MultiLineTextBox.Input = null;
this.MultiLineTextBox.IsntInput = null;
this.MultiLineTextBox.LineColor = System.Drawing.Color.DodgerBlue;
this.MultiLineTextBox.LineHeight = 2;
this.MultiLineTextBox.LineMarginHorizontal = 0;
this.MultiLineTextBox.LineMarginLeft = 0;
this.MultiLineTextBox.LineMarginRight = 0;
this.MultiLineTextBox.LineMarginToText = 1;
this.MultiLineTextBox.Margin = new System.Windows.Forms.Padding(4, 5, 4, 5);
this.MultiLineTextBox.Multiline = true;
this.MultiLineTextBox.Name = "MultiLineTextBox";
this.MultiLineTextBox.Padding = new System.Windows.Forms.Padding(0, 0, 0, 2);
this.MultiLineTextBox.PasswortChar = '\0';
this.MultiLineTextBox.Patter = null;
this.MultiLineTextBox.PatterError = System.Drawing.Color.Red;
this.MultiLineTextBox.UseSystemPasswordChar = false;
```	
