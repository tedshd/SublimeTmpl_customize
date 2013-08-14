## Ted's sublime customize setting

### scss

Preferences -> Package settings -> SublimeTmpl

* Settings - Menu
add
```py
{
    "caption": "SCSS",
    "command": "sublime_tmpl",
    "args": {
        "type": "scss"
    }
},
```

* Settings - Commands
add
```py
{
    "caption": "Tmpl: Create scss", "command": "sublime_tmpl",
    "args": {"type": "scss"}
},
```

* Settings - Default
add
```py
"scss": {
    "syntax": "Packages/CSS/SCSS.tmLanguage"
},
```

* Key Bindings
add
```py
,{
    "keys": ["ctrl+alt+s"], "command": "sublime_tmpl",
    "args": {"type": "scss"}
}
```