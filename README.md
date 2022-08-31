# Alfred-workflow-find-and-replace-in-clipboard-text
Find and replace a word or phrase in text on the clipboard
# About

This workflow takes the text on the clipboard and enables a single find and replace on elements of that text. You have the option of posting the revised clipboard text to the file `~/Downloads/tmp.txt` and if you choose that option the file will then be opened (enabling you, if you wish, to see a spellcheck on the relevant text).

Note:
- When configuring this workflow you have the option to specify another folder to receive the temporary file. The default is `~/Downloads`.
- It's up to you to delete the temporary file after you have finished with it—although the workflow will automatically overwrite it next time you use the workflow if you don't delete the file.
- The *Find* is *case sensitive* so take care to ensure the case is correct when searching for something.

# Usage

1. Copy to the clipboard the text on which you wish to work *before* you run this workflow.
2. Type `fr` (for Find Replace) plus <space> and the word or phrase you wish to find in the clipboard text. Press <Enter>.
3. Type the word or phrase which you wish to *replace* the original word or phrase. (You'll see the original word or phrase in the sub-text of the prompt.)
4. If the *Find* then fails to find the relevant word or phrase among the clipboard text you will then see an error message warning you of that.
5. If the find and replace operation is successful you will see a dialog confirming that. You can then either close that dialog (so ending the workflow—though leaving the revised text on the clipboard) or choose to write the revised clipboard text to the file mentioned under `About` above.
