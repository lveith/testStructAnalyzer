# Infos to CodeMirror with 4D language and 4D theme
Just a not fully fininshed demo how can define 4D language and 4D theme in CodeMirror.
The 4Dv18R3 mode(language) is defined in 4D.js and the 4D theme is defined 4D.css.
Both files (4D.js and 4D.css) are important and belongs together,
because 4D.css used in addition some extra selectors.

It is recommended to use 4D-mode with 4D-theme,
because in the 4D-theme there are, among other things, special adjustments to 4D-mode.

You can also use 4D.css as a template for to build your own variant (own colors or other own specials).

Of course you can also try one of the many dozen existing themes for 4D mode,
but most of the foreign themes just lack a few hidden special 4D features
to optimally address 4D mode specials (there for the 4D.css is made to bring all 4D mode extras up).

4D.js and 4D.css are just a draft/blueprint,
it can be used but it is not optimally fininshed, its just a sketch.

The contained html files in folder "onlySomeNotesTo4DWithCodeMirror"
can not run standalone, to do this the TestListbox.4dbase.zip is needed.
Inside TestListbox.4dbase.zip there is the original folder
```
.../TestListbox.4dbase/Resources/HTML_Docs/cm/codemirror-5.45.0
```
here you can find all needed files and
so there this html-demo files can open in a browser successfully.

### What is codemirror and how to use it
More information can find here https://codemirror.net
CodeMirror is a versatile text editor implemented in JavaScript for the browser.
It is specialized for editing code, and comes with a number of language modes and addons that implement more advanced editing functionality.
A rich programming API and a CSS theming system are available for customizing CodeMirror
to fit your application, and extending it with new functionality.