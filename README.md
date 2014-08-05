Qt Creator Wombat Theme
=======================

This is a dark color scheme for Qt Creator. It's inspired from the VIM [wombat][1] theme, but also styles the widgets such as combo boxes, tree views, etc.

![Qt Creator with wombat theme](http://i.imgur.com/eqXMhz1.png)


Note
====

This is a work in progress. Any suggestions or pull requests are appreciated.


Install
=======

The theme consists of two parts:

1. The wombat colorscheme
2. The application stylesheet

The colorscheme should be copied in the styles directory of Qt Creator such as ~/.config/QtProject/qtcreator/styles

The stylesheet can be copied along with the icons folder anywhere. It is then loaded using the -style parameter on startup of Qt Creator.

An example:
```
/path/to/QtCreator/QtCreator -style /path/to/stylesheet/stylesheet.css
```


[1]: http://www.vim.org/scripts/script.php?script_id=2465
