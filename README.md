diaspora glyphs
===============

Some Glyphs for the web as a Addon for FontAwesome
with http://fontcustom.com/

### Installation
Install this things:
```
    sudo apt-get install fontforge ttfautohint
    cd fonts
    wget http://people.mozilla.com/~jkew/woff/woff-code-latest.zip
    unzip woff-code-latest.zip -d sfnt2woff && cd sfnt2woff && make && sudo mv sfnt2woff /usr/local/bin/
    gem install fontcustom
```
### compile glyphs

```
    fontcustom watch zeugs

```

### Glyphs
The finish Glyphs are found in the directory fontcustom
