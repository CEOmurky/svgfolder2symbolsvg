# svgFolder2SymbolSvg

Merge some folder in svg files one svg file with Symbol

## Example

folder has many svg file

```
svg/
    double-right.svg
    double-left.svg
```

Do this

```
svg2symbol ./svg icons.svg
```

Make it this

```
svg/
    double-right.svg
    double-left.svg

icons.svg
```

icons.svg
```svg
<svg aria-hidden="true" style="position: absolute; width: 0; height: 0; overflow: hidden;" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<defs>
<symbol id="dobule-right" viewBox="0 0 32 32">
<title>dobule-right</title>
<path d="...."></path>
</symbol>
<symbol id="dobule-left" viewBox=""0 0 32 32">
<title>dobule-left</title>
<path d="..."</path>
</symnol>
</defs>
```
