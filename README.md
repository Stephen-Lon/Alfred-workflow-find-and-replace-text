# Alfred-workflow-find-and-replace-text
Find and replace a word or phrase in text

# Introduction

The workflow takes selected or pasted text and enables a single find and replace on elements of that text. You will be shown a preview of the revised text and can accept it, edit it or go back and change the replacement text.

The workflow works with either:
- selected text (using your Universal Actions hotkey); or
- text that you paste into the workflow (after using the workflow keyword).

**Please note**: both the `Find` and the `Replace` are case sensitive.

# Using the Universal Action on selected text

1. Select some text and press your Universal Action hotkey (<kbd>⌘/</kbd> by default). Choose the `Find and replace text` action and press <kbd>↩︎</kbd>.
![The UA](https://github.com/user-attachments/assets/8cbfc068-f523-46ad-af20-1b5b786afdd3)

Type the case sensitive word or phrase you wish to find in the text. (Take care with spaces because the find and replace will work on spaces as well as characters.)
![Find](https://github.com/user-attachments/assets/2640534a-67d7-4f2c-90ca-646f3ddd79b7)

2. Press <kbd>⏎</kbd> and type the case sensitive word or phrase which you wish to *replace* the original word or phrase. (You'll see the original word or phrase in the sub-text of the prompt.) You can leave the field blank if you simply wish to delete a word or phrase in the selected text.
![Replace](https://github.com/user-attachments/assets/2002283f-c9e6-4748-bfdd-cbf2be5f983f)

  Press <kbd>⏎</kbd>.

3. If the `Find` then fails to find the relevant word or phrase in the text you will see an error message warning you of that. 
 
4. If the find and replace operation is successful you will see a preview of the revised text:
![Check](https://github.com/user-attachments/assets/dbd62974-e5a2-40c0-9eda-24e1cc8c111c)

Note:
- The capitalised "Seagulls" was not replaced because the search and replace is case sensitive.
- The prompts at the bottom of the window: press <kbd>↩</kbd> to accept the revised text or <kbd>⌘</kbd><kbd>↩</kbd> if you wish to edit it. <kbd>⌘</kbd><kbd>0</kbd> wiill toggle size of the window and <kbd>esc</kbd> will take you back to change the replacement text.
- You can also press <kbd>⌘</kbd><kbd>esc</kbd> to cancel the workflow.

If you press <kbd>⌘</kbd><kbd>↩</kbd> to edit the text you will see a window like this:
![Edit](https://github.com/user-attachments/assets/08303de2-9dd3-46fb-b296-0a84305e84fb)

Note:
- Most of the prompts at the bottom of the window have changed. <kbd>↩</kbd> will enter a new line in the text and <kbd>⌘</kbd><kbd>↩</kbd> will save the text in the window (whether you edit it or not). <kbd>esc</kbd> will undo any edits and take you back to the previous window (from which, if you wish, you can again press <kbd>esc</kbd> to go back and change the replacement text).
- If you decide not to edit the text you don't need to return to the previous window to save it: just press <kbd>⌘</kbd><kbd>↩</kbd> in this window to continue.
- You can press <kbd>⌘</kbd><kbd>esc</kbd> to cancel the workflow.

You can edit the text however you wish:
![Result](https://github.com/user-attachments/assets/0e223a24-1263-44ff-841b-3ad8b256ee36)

5. At the end of the workflow you will see the dialog offering the options of either overwriting the original selected text or of simply copying the revised text to the clipboard. (You may need the latter option when working with text in a document that is not writable—a PDF file, for example.)

## Tip

If:
- you are happy with the revised text preview; and
- simply wish to replace selected text with the revised text (as opposed to copying the revised text to the clipboard)

then once you have entered the search text and replacement text all you have to do is to press <kbd>↩</kbd> at the following window and subesquent prompt to take you very quickly through the workflow.

# Using pasted text with the workflow keyword
You can copy some text then use the workflow keyword (`fxr` by default) and paste the text in the workflow:

![Find and replace text](Images/Keyword.png)

The find and replace then works in the same manner as outlined above save that at the end of the workflow you will be offered the options of either overwriting the original text on the clipboard or simply ending the workflow.
