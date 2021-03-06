# Atom Editor Cheat Sheet

Here are the most useful Atom editor plugins and shortcuts (in my opinion).

## My Configuration

### My Plugins

* Archive View
* Atom Syntax Hilighting for Sass
* Atom Beautify
* Auto Indent
* Auto Update Packages
* Autoclose Html
* Autocomplete Plus
* Bracket Matcher
* Color Gutter
* Color Picker
* Command Palette
* Fuzzy Finder
* Go To Line
* Refactor
* JS Refactor
* Minimap
* Sublime Style Column Selection
* Sublime Tabs
* Wrap Guide

### My Snippet(s)

My snippet file (Atom &gt; Open Your Snippets) looks like this:

    '.html':
      'HTML5 Boilerplate':
        'prefix': 'HTML5'
        'body': """<!DOCTYPE html>
        <html>
          <head>
            <meta charset="utf-8">
            <title>Title</title>
          </head>
          <body>
          </body>
        </html>"""

### My Atom Config

If you want guide-lines showing  your indentation, here's how to do that.

Atom > Open Your Config, then I made my editor block look like this (but remember, syntax matters):

    editor:
      showIndentGuide: true
      autoIndentOnPaste: false
      invisibles: {}

### My Atom Stylesheet

In my stylesheet (Atom &gt; Open Your Stylesheet) I added this to the bottom:

    /*
    * Make matching brackets hilight in green
    */
    .editor, atom-text-editor::shadow {
       .bracket-matcher {
       border-bottom: 1px solid lime;
        position: absolute;
        border: 1px solid rgba(0, 255, 0, 0.7);
        background-color: rgba(0, 255, 0, 0.3);
      }
    }



## Shortcuts

Edit multiple lines:

    Cmd + click any number of lines, then type or delete, or whatevz

Rename HTML tag:

    Ctrl + Shift + U

Rename JS variable/function:

    Ctrl + Alt + r

Go to matching HTML tag:

    Ctrl + Alt + j

Find a file:

    Cmd + T

Go to line:

    Ctrl + G

Cut move line:

    Ctrl + Cmd + [up]
    Ctrl + Cmd + [down]

Comment current selection/line:

    Cmd + /

Select current line:

    Cmd + l

Color picker:

    Cmd + Shift + C

Edit multiple values:

    Cmd + double-click the values, then edit

## For more, see

http://d2wy8f7a9ursnm.cloudfront.net/atom-editor-cheat-sheet.pdf
