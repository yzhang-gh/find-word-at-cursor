[![version](https://img.shields.io/vscode-marketplace/v/yzhang.find-word-at-cursor.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=yzhang.find-word-at-cursor)

Adapted from [findWordAtCursor](https://marketplace.visualstudio.com/items?itemName=mksafi.find-word-at-cursor) by M.K. Safi (@msafi).

Make search a little bit easier.

## Changes

- `Find next` can loop back to the first line when reaching the end of the file
- Be consistent with <kbd>Ctrl</kbd> + <kbd>D</kbd>
    - No selection → `wholeWords: true; caseSensitive: true`
    - Has selection → `wholeWords: false; caseSensitive: false`
- Default key binding
    - <kbd>F3</kbd> / <kbd>Shift</kbd> + <kbd>F3</kbd> (find next/previous word at cursor)