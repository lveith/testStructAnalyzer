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


### Shortcuts to Search

Ctrl-F / Cmd-F
Start searching

Ctrl-G / Cmd-G
Find next

Shift-Ctrl-G / Shift-Cmd-G
Find previous

Shift-Ctrl-F / Cmd-Option-F
Replace

Shift-Ctrl-R / Shift-Cmd-Option-F
Replace all

Alt-F
Persistent search (dialog doesn't autoclose, enter to find next, Shift-Enter to find previous)

Alt-G
Jump to line


### Other Shortcuts (just a subset of all possible keys, means this is not all)

Alt-Left: goSubwordLeft

Alt-Right: goSubwordRight

Cmd-Up: scrollLineUp

Cmd-Down: scrollLineDown

Shift-Cmd-L: splitSelectionByLine

Alt-Tab: indentLess

Shift-Tab: indent (needs correct language mode with block detect)

Esc: singleSelectionTop

Cmd-L: selectLine

Shift-Cmd-K: deleteLine

Cmd-Enter: insertLineAfter

Shift-Cmd-Enter: insertLineBefore

Cmd-D: selectNextOccurrence

Shift-Cmd-Space: selectScope

Shift-Cmd-M: selectBetweenBrackets

Cmd-M: goToBracket

Cmd-Ctrl-Up: swapLineUp

Cmd-Ctrl-Down: swapLineDown

Cmd-/: toggleComment

Cmd-J: joinLines

Ctrl-J: jumpToMatchingTag

Shift-Cmd-D: duplicateLine

Cmd-T: transposeChars

F9: sortLines

Cmd-F9: sortLinesInsensitive

F2: nextBookmark

Shift-F2: prevBookmark

Cmd-F2: toggleBookmark

Shift-Cmd-F2: clearBookmarks

Alt-F2: selectBookmarks

Alt-Q: wrapLines

Cmd-K Cmd-Backspace: delLineLeft

Backspace: smartBackspace

Cmd-K Cmd-K: delLineRight

Cmd-K Cmd-U: upcaseAtCursor

Cmd-K Cmd-L: downcaseAtCursor

Cmd-K Cmd-Space: setSublimeMark

Cmd-K Cmd-A: selectToSublimeMark

Cmd-K Cmd-W: deleteToSublimeMark

Cmd-K Cmd-X: swapWithSublimeMark

Cmd-K Cmd-Y: sublimeYank

Cmd-K Cmd-G: clearBookmarks

Cmd-K Cmd-C: showInCenter

Shift-Alt-Up: selectLinesUpward

Shift-Alt-Down: selectLinesDownward

Cmd-F3: findUnder

Shift-Cmd-F3: findUnderPrevious

Ctrl-Q: fold

Shift-Cmd-\[: fold

Shift-Cmd-]: unfold

Cmd-K Cmd-j: unfoldAll

Cmd-K Cmd-0: unfoldAll

Cmd-H: replace
