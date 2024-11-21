---
title: "Advanced Features"
---

### Tab in Peek

You can also use Cursor Tab in the "Go to Definition" or "Go to Type Definition" peek views. This is useful, for example, when adding a new argument to a function call.


  


We especially enjoy using this in vim in conjunction with `gd` to, for example, modify a function definition, then fix all of its usages in one go.

###   Cursor Prediction

Cursor can also predict where you will go to after an accepted edit.
If available, you will be able to press tab to go to the next location, allowing you to tab-tab-tab through edits.





###   Partial Accepts

You can accept the next word of a suggestion by pressing `Ctrl/⌘` and the right arrow (or by setting `editor.action.inlineSuggest.acceptNextWord` to your preferred keybinding).

To enable partial accepts, navigate to `Cursor Settings` > `Features` > `Cursor Tab`.
