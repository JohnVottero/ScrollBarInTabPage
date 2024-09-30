# Scrolling does not work in a FluentTab in a FluentDialog

This repository was created to reproduce an issue with the Fluent UI for Blazor library.

If the contents of a FluentTab are too large to fit in the tab, the tab should be scrollable.
However, this is not the case in a FluentDialog. A scroll bar is added but, the fluent-tab-panel
is too large so the contents and the scroll bar run off the bottom of the dialog.

Here is a screenshot of the issue:

![Screenshot](ScrollBarInTabPage.png)