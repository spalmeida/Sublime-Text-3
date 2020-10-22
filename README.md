# Sublime-Text-3
Meu ambiente de trabalho Sublime Text 3

# KeyMap
```json
[
	{
		"keys": ["ctrl+shift+o"], "command": "terminus_open", "args": {
			"cwd": "${C:\\laragon\\www}"
		}
	},


	
	{	"keys": ["alt+shift+f"], "command": "reindent", "args": {"single_line": false}},
	

	{ 	"keys": ["ctrl+alt+e"],  "command": "run_macro_file", "args": {"file": "Packages/User/echo_simplificado.sublime-macro"} },
	

	{ 	"keys": ["ctrl+m"],  "command": "run_macro_file", "args": {"file": "Packages/User/assets.sublime-macro"} },
	
	{ 	"keys": ["ctrl+shift+m"], "command": "insert_snippet", "args": 
		{ "name": "Packages/User/codes/comentario.sublime-snippet" } 
	},

	{ "keys": ["shift+escape"], "command": "show_panel", "args": {"panel": "output.Terminus Build Results"},
	"context": [
		{"key": "terminus_view.exec_panel_exists", "operand": true},
		{"key": "terminus_view.exec_panel_visible", "operand": false}
	]
},
{ "keys": ["shift+escape"], "command": "show_panel", "args": {"panel": "output.exec"},
"context": [
	{"key": "terminus_view.exec_panel_exists", "operand": true},
	{"key": "terminus_view.exec_panel_visible", "operand": true}
]
},

]

```
