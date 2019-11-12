# Close Others for Sublime Text

Close other tabs and windows with shortcuts.

## Installation

### Setup Package Control Repository

Follow the instructions from https://sublime.fnando.com

### Git Clone

Clone this repository into the Sublime Text “Packages” directory, which is located where ever the “Preferences” -> “Browse Packages” option in sublime takes you.

## Usage

- The keybinding for closing all other tabs is `super+shift+w`.
- The keybinding for close all other windows is `super+alt+shift+w`.

There are also commands trigger both

You can change it by defining a new shortcut binding like the following:

```json
[
  { "keys": ["super+shift+w"], "command": "close_other_tabs" },
  { "keys": ["super+alt+shift+w"], "command": "close_other_windows" }
]
```

## License

Copyright (c) 2019 Nando Vieira

MIT License

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
