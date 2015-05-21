## An(other, minimal,) `emacs` cheat sheet

### Help

|Keystrokes  | Action     |
|------------|------------|
|`C-h k`| Describe command from keystrokes|
|`C-h f`| Describe command from function name|
|`C-h ?`| help suggestions|

### Files

|Keystrokes  | Action|
|------------|------------|
|`C-x C-f`   | Create/Open|
|`C-x C-s`   | Save|
|`C-x C-w`   | Save as|
|`C-x C-c`   | Close|
|`C-x i`     | Insert|

### Moving

|Keystrokes  | Action|
|------------|------------
|`C-p `      | previous line|
|`C-n `      | next line|
|`C-a `      | line beginning|
|`C-e `      | end of line|
|`C-f `      | forward a character|
|`C-b `      | backward a character|
|`M-f `      | forward a word|
|`M-b `      | backward a word|
|`M-a `      | beginning of sentence|
|`M-e `      | end of sentence|
|`M-{ `      | beginning of paragraph|
|`M-} `      | end of paragraph|
|`C-q C-l`   | insert a page break |
|`C-x [`     | previous page|    
|`C-x ]`     | next page|    
|`C-v`       | next screen|    
|`M-v ]`     | previous screen|    
|`M-< `      | beginning of buffer|
|`M-> `      | end of buffer|
|`M-g M-g`   | go to line|

### Select region

|Keystrokes  | Action|
|------------|------------
|`C-space`     | by line
|`C-x space`   | by column

### Editing

|Keystrokes  | Action|
|------------|------------
|`C-w `      | Cut region|
|`M-w`       | Copy region|
|`C-y`       | Paste|
|`C-x u`     | Undo|

### Wrapping text
|Keystrokes  | Action|
|------------|------------
|`M-q `      | wrap paragraph|
|`M-x fill-region`  | wrap paragraphs from selected region|

### Accessing menu
```
M-`
```

### Repeating a command

|Keystrokes  | Action|
|------------|------------
|`M-n CMD_KEYSTROKES` | repeat n times `CMD_KEYSTROKES`|
|`C-u CMD_KEYSTROKES` | repeat 4 times `CMD_KEYSTROKES`|
|`C-u C-u CMD_KEYSTROKES` | repeat 16 times `CMD_KEYSTROKES`|
|`C-u C-u C-u CMD_KEYSTROKES` | repeat 64 times `CMD_KEYSTROKES`|

and so on