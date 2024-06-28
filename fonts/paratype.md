# ParaType Sans, Serif & Mono
```
\usepackage[T1]{fontenc} % required
\usepackage{paratype}

% to use only one font with other fonts
\usepackage[T1]{fontenc}
\usepackage{PTSerif}
```

There are also several packages that set the individual font families. They have the
same name as the font family, but without the suffix: 
- PTSerif, 
- PTSerifCaption,
- PTSans, 
- PTSansNarrow, 
- PTSansCaption and 
- PTMono.

You can also typeset some text in a desired font like this:
`{\usefont{T1}{PTSerifCaption-TLF}{m}{it}Text in PT Serif Caption Italic}`

`\usefont{enc}{family}{series}{shape}`

## The available series/shape combinations

| font family        | series/shape combinations                      |
| ------------------ | ---------------------------------------------- |
| PTSans-TLF         | m/n, m/it, b/n, b/it, c/n, bc/n                |
| PTSansNarrow-TLF   | m/n, b/n, _m/sl, b/sl_                         |
| PTSansCaption-TLF  | m/n, b/n, _m/sl, b/sl_                         |
| PTSerif-TLF        | m/n, m/it, b/n, b/it, _m/sl, m/ui, b/sl, b/ui_ |
| PTSerifCaption-TLF | m/n, m/it, _m/sl, m/ui_                        |
| PTMono-TLF         | m/n, b/n, _m/sl, b/sl_                         |

*_Slanted_ = faked


## About

The fonts were developed by ParaType for the project _Public Types of Russian Federation_ and released under an open user license. They were designed by Alexandra Korolkova, Olga Umpeleva, Isabella Chaeva and Vladimir Yefimov.