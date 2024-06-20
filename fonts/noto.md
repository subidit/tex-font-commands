# noto

This package provides LATEX, pdfLATEX, XELATEX and LuaLATEX support for the NotoSerif, NotoSans and NotoSansMono families of fonts, designed by Steve Matteson for Google.

Condensed variants have been moved into a separate notocondensed package. (Not working in fontenc.)


| NotoSerif               | NotoSans                          | NotoSansMono           |
| ----------------------- | --------------------------------- | ---------------------- |
| \usepackage[rm]{noto}   | \usepackage[sf]{noto}             |                        |
| \usepackage{noto-serif} | \usepackage[sfdefault]{noto-sans} | \usepackage{noto-mono} |
| \notoserif              | \notosans                         | \notomono              |
| \notoseriflgr           | \notosanslgr                      | \notomonolgr           |


## Weights

| Regular     | Bold      |
| ----------- | --------- |
| thin        | semibold  |
| extralight  | bold [d]  |
| light       | extrabold |
| regular [d] | black     |
| medium      |           |


# notocondensed
*Not Working with fontenc T1*

```
\usepackage{notocondensed}
\usepackage[rm]{notocondensed}
\usepackage[sf]{notocondensed} 
\usepackage{notocondensed-mono}
```

## Commands 
```
\notoserifcondensed, \notosanscondensed, \notomonocondensed, 
\notoserifsemicondensed, \notosanssemicondensed, \notomonosemicondensed,
\notoserifextracondensed, \notosansextracondensed and \notomonoextracondensed 
```