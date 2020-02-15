
## zsh keyboard shortcuts

### moving around current line
- `[Ctrl][A]` - move to the beginning of the current line
- `[Ctrl][E]` - move to the end of the current line
- `[Alt][F]`  - move the cursor forward one word on the current line
- `[Alt][B]`  - move the cursor backwards one word on the current line

### clear and delete words
- `[Ctrl][U]` - clear the entire line
- `[Ctrl][W]` - delete the word in front of the cursor
- `[Alt][D]`  - delete the word after the cursor


### explore history
- `[Ctrl][R]` - search in history - find first matching entry in the history, type again to find next matching entry

### manipulating words and letters
- `[Alt][U]`  - make the current word after the cursor uppercase
- `[Alt][L]`  - make the current word after the cursor lowercase
- `[Alt][C]`  - capitalize a word, if cursor is on the beginning of the word
- `[Alt][C]`  - capitalize a letter, if cursor is midway in a word

## zsh configuration

- ZSH DELETE Keybinding : `bindkey "\e[3~" delete-char `
