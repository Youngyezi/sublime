# sublime text 配置

------

跨平台编辑器 Mac/Linux/Win

------

## Package Control


### sublime text 2

```
import urllib2,os; pf='Package Control.sublime-package'; ipp = sublime.installed_packages_path(); os.makedirs( ipp ) if not os.path.exists(ipp) else None; urllib2.install_opener( urllib2.build_opener( urllib2.ProxyHandler( ))); open( os.path.join( ipp, pf), 'wb' ).write( urllib2.urlopen( 'http://sublime.wbond.net/' +pf.replace( ' ','%20' )).read()); print( 'Please restart Sublime Text to finish installation')
```

### sublime text 3
```
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
```

## Settings

### theme

```
"theme": "theme name.sublime-theme",
```

### color scheme

```
Obsidian
```

### settings_config

```
{
    "auto_indent": true,
    "bold_folder_labels": true,
    "caret_style": "phase",
    "color_scheme": "Packages/Obsidian Color Scheme/textmate/Obsidian.tmTheme",
    "default_line_ending": "unix",
    "ensure_newline_at_eof_on_save": true,
    "fade_fold_buttons": false,
    "fold_buttons": true,
    "font_face": "Inconsolata",
    "font_options":
    [
        "directwrite"
    ],
    "font_size": 12,
    "highlight_line": true,
    "highlight_modified_tabs": true,
    "ignored_packages":
    [
        "Vintage"
    ],
    "line_padding_bottom": 1,
    "line_padding_top": 1,
    "tab_size": 4,
    "theme": "Cobalt2.sublime-theme",
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true
}

```

### plugs
> * Emmet               代码自动补全
> * BracketHighlighter  高亮显示匹配的括号、引号和标签
> * SideBarEnhancements 侧边栏增强
> * ColorPicker         调色盘
> * ConvertToUTF8       编码装换
> * DocBlockr           代码注释
