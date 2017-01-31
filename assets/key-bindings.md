```javascript

[
//=======================elegantspirit=======================//
// delete line
{ "keys": ["alt+k"], "command":"run_macro_file", "args": {"file":"Packages/Default/Delete Line.sublime-macro"} },
// duplicate line
{ "keys": ["alt+z"], "command": "duplicate_line" },

// navigate to specified line
{ "keys": ["alt+g"], "command": "show_overlay", "args": {"overlay": "goto", "text": ":"} },

// start new line after current
{ "keys": ["alt+m"], "command": "run_macro_file", "args": {"file": "res://Packages/Default/Add Line.sublime-macro"} },
// start new line before current
{ "keys": ["alt+f"], "command": "run_macro_file", "args": {"file": "res://Packages/Default/Add Line Before.sublime-macro"} },

// move caret to line start with selection
{ "keys": ["alt+9"], "command": "move_to", "args": {"to": "bol", "extend": true} },
// move caret to line end with selection
{ "keys": ["alt+0"], "command": "move_to", "args": {"to": "eol", "extend": true} },

// move caret to previous word with selection
{ "keys": ["alt+y"], "command": "move", "args": {"by": "words", "forward": false, "extend": true} },
// move caret to next word with seleciton
{ "keys": ["alt+t"], "command": "move", "args": {"by": "word_ends", "forward": true, "extend": true} },

// undo
{ "keys": ["alt+i"], "command": "undo" },

// add selection for next occurrence
{ "keys": ["alt+j"], "command":"find_under_expand" },
// 一次选中所有的
{ "keys": ["ctrl+b"],"command": "find_all_under" },

// delete to word start
{ "keys": ["alt+h"], "command": "delete_word", "args": { "forward": false } },

// move caret to previous word
{ "keys": ["alt+w"], "command": "move", "args": {"by": "subwords", "forward": false} },
// move caret to next word
{ "keys": ["alt+n"], "command": "move", "args": {"by": "subword_ends", "forward": true} },

// cut copy paste
{ "keys": ["alt+x"], "command": "cut" },
{ "keys": ["alt+c"], "command": "copy" },
{ "keys": ["alt+v"], "command": "paste" },

// scroll up
{ "keys": ["alt+,"], "command": "scroll_lines", "args": {"amount": 1.0 } },
// scroll down
{ "keys": ["alt+."], "command": "scroll_lines", "args": {"amount": -1.0 } },

// move the cursor
{ "keys": ["alt+l"], "command": "move","args": {"by": "characters", "forward":false} },
{ "keys": ["alt+r"], "command": "move","args": {"by": "characters", "forward":true} },
{ "keys": ["alt+u"], "command": "move","args": {"by": "lines", "forward":false} },
{ "keys": ["alt+d"], "command": "move","args": {"by": "lines", "forward":true} },

// move caret to line start
{ "keys": ["alt+s"], "command":"move_to", "args": {"to": "bol","extend": false} },
// move caret to line end
{ "keys": ["alt+e"], "command":"move_to", "args": {"to": "eol","extend": false} }
]

```
