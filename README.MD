# c-intro-and-ref

GNU C Language Intro and Reference

## How to build

install `texinfo`:

macOS: `sudo port install texinfo` or `brew install texinfo`

Debian Linux: `sudo apt install texinfo`

build html:

```bash
make c.html
```

build html with css:

```bash
makeinfo --html --css-include=style.css c.texi
```
