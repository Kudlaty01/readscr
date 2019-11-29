# readscr
a bash screen reader based on [ImageMagick](https://github.com/ImageMagick/ImageMagick), [xsel](https://github.com/kfish/xsel), [tesseract](https://github.com/tesseract-ocr/tesseract) and occasionally [translate-shell](https://github.com/soimort/translate-shell)
after execution it allows to select a part of the screen and copies the OCR-ed text content into the clipboard

## installation
just put it in your `/bin` or somewhere else where your `$PATH` reaches and give it a good `chmod +x`

## usage
```
readscr [OPTIONS[
```
### Options
- `-l <lang>` language the screen text is in (it's a tesseract parameter - first 3 letters)
- `-s` speak the text of fetched screen part
- `-i` option for compatibility with my i3 desktop environment, with it set, utility can have it's i3 keybinding - it just pauses for a second
  
## TODO
- add translation options


Any feedback, opinions and most of all contribution is appreciated :)
