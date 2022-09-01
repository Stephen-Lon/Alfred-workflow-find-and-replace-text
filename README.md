# Alfred-workflow-find-and-replace-in-clipboard-text
Find and replace a word or phrase in text on the clipboard
# About

This workflow takes the text and enables a single find and replace on elements of that text. You have the option of posting the revised text to the file `~/Downloads/tmp.txt` and if you choose that option the file will then be opened (enabling you, if you wish, to see a spellcheck on the relevant text).

You can use this workflow *either*
- as a Universal Action on selected text; *or*
- on text already on the clipboard by using the workflow's keyword.

Note:
- When configuring this workflow you have the option to specify another folder to receive the temporary file. The default is `~/Downloads`.
- It's up to you to delete the temporary file after you have finished with it—although the workflow will automatically overwrite it next time you use the workflow if you don't delete the file.
- The *Find* is *case sensitive* so take care to ensure the case is correct when searching for something.
- The revised text on the clipboard at the end of the workflow is *not* marked as transient in the `Copy to Clipboard` Action so it's not hidden from Alfred and you can access it again through Alfred's `Clipboard History` viewer.

# Usage

1. Invoke the Alfred Universal Action shortcut on selected text and type the word or phrase you wish to find in the text. Alternatively copy to the clipboard the text on which you wish to work, type the workflow's keyword plus <space> and the word or phrase you wish to find in the clipboard text.
2. Press <Enter> and type the word or phrase which you wish to *replace* the original word or phrase. (You'll see the original word or phrase in the sub-text of the prompt.)
3. If the *Find* then fails to find the relevant word or phrase in the text you will then see an error message warning you of that.  
4. If the find and replace operation is successful you will see a dialog confirming that. You can then either close that dialog (so ending the workflow—though leaving the revised text on the clipboard) or choose to write the revised text to the file mentioned under `About` above.  
