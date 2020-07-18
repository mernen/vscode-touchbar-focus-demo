# touchbar-focus-demo README

This is a basic VSCode extension that attempts to show two buttons on the Touch Bar:

* "Editor Focus" — when the editor is focused
* "Search Focus" — when the search sidebar is focused
* "Search Visible" — when the search sidebar is visible

The "Editor Focus" button is mostly reliable — sometimes the Touch Bar will fail
to update when the `editorFocus` variable should have changed value.

The "Search Visible" button is very reliable.

The "Search Focus", as far as I can tell (testing on a single computer), never appears.

Testing this behavior requires a Mac, preferably one with a physical Touch Bar.
If one is not available, it's still possible to try it by opening Apple's Xcode,
then going to Window→Touch Bar→Show Touch Bar (Command+Shift+8) before trying
the extension.
