# pandoc-test

## nav.xhtml location check

### Pandoc

1. Make epub.
```
pandoc example.md -o example-pandoc.epub --epub-subdirectory=OEBPS
```

2. Unzip epub.
```
unzip example-pandic.epub
```

3. Check nav.xhtml location.
```
OEBPS/nav.xthml
```

### Sigle

1. Make epub.
2. Unzip epub.
3. Check nav.xhtml location.
```
OEBPS/Text/nav.xhtml
```
