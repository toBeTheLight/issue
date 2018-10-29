# ISSUE
When user has not ended composition (compositionend event) with IME, before version of 2.5.14, keyboard events with modifiers (e.g, keydown@enter, keydown@up) will not be fired. After version of 2.5.14 it will. And the keyboard arrow keys are usually be used to choose the right word, so this change will result in a lot of extra events. 


# Steps to reproduce
1. Open demo.html
2. Use IME
3. Type some letters
4. Press the down arrow of the keyboard