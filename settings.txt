sublime text 2 配置


---- console

    <code>
    import urllib2,os; pf='Package Control.sublime-package'; ipp = sublime.installed_packages_path(); os.makedirs( ipp ) if not os.path.exists(ipp) else None; urllib2.install_opener( urllib2.build_opener( urllib2.ProxyHandler( ))); open( os.path.join( ipp, pf), 'wb' ).write( urllib2.urlopen( 'http://sublime.wbond.net/' +pf.replace( ' ','%20' )).read()); print( 'Please restart Sublime Text to finish installation')
    </code>


---- user

    <code>
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
        "font_size": 11,
        "highlight_line": true,
        "highlight_modified_tabs": true,
        "ignored_packages":
        [
            "Vintage"
        ],
        "line_padding_bottom": 1,
        "line_padding_top": 1,
        "tab_size": 4,
        "theme": "Soda Dark.sublime-theme",
        "translate_tabs_to_spaces": true,
        "trim_trailing_white_space_on_save": true
    }
    </code>



---- color scheme

    </code>
        Obsidian
    </code>
