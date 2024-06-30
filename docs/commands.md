# Font Commands

```
\fontfamily{family} 
\fontseries{series} 
\fontshape{shape} 
\fontsize{size}{skip} 
\selectfont 

\usefont{enc}{family}{series}{shape} 
% eg: \usefont{ot1}{cmr}{m}{n}

\linespread{factor} 
```

## Font Styles

| Text Style              | Command                                 |
| ----------------------- | --------------------------------------- |
| Roman                   | `\textrm{..}` or `{\rmfamily ..}`       |
| Italics                 | `\textit{..}` or `{\itshape ..}`        |
| Medium weight (default) | `\textmd{..}` or `{\mdseries ..}`       |
| Boldface                | `\textbf{..}` or `{\bfseries ..}`       |
| Upright (default)       | `\textup{..}` or `{\upshape ..}`        |
| Slanted                 | `\textsl{..}` or `{\slshape ..}`        |
| Sans serif              | `\textsf{..}` or `{\sffamily ..}`       |
| Small caps              | `\textsc{..}` or `{\scshape ..}`        |
| Typewriter              | `\texttt{..}` or `{\ttfamily ..}`       |
| Main document font      | `\textnormal{..}` or `{\normalfont ..}` |


### Series
`\fontseries{series}` 
A series combines a weight and a width. Typically, a font supports only a few of the possible combinations. Some common combined series values include:

- `m`	Medium (normal)
- `b`	Bold
- `c`	Condensed
- `bc`	Bold condensed
- `bx`	Bold extended

#### Weight & Width

| weight              | width                |
| ------------------- | -------------------- |
| `ul` Ultra light    | `uc` Ultra condensed |
| `el` Extra light    | `ec` Extra condensed |
| `l` Light           | `c` Condensed        |
| `sl` Semi light     | `sc` Semi condensed  |
| `m` Medium (normal) | `m` Medium           |
| `sb` Semi bold      | `sx` Semi expanded   |
| `b` Bold            | `x` Expanded         |
| `eb` Extra bold     | `ex` Extra expanded  |
| `ub` Ultra bold     | `ux` Ultra expanded  |


### Shape
`\fontshape{shape}`
Select font shape. Valid shapes are:

- `n`	Upright (normal)
- `it`	Italic
- `sl`	Slanted (oblique)
- `sc`	Small caps
- `ui`	Upright italics
- `ol`	Outline
The two last shapes are not available for most font families, and small caps are often missing as well.


## Font Sizes

`\fontsize{size}{skip}`

Set the font size and the line spacing. The unit of both parameters defaults to points (pt). The line spacing is the nominal vertical space between lines, baseline to baseline. It is stored in the parameter `\baselineskip`. The default `\baselineskip` for the Computer Modern typeface is 1.2 times the `\fontsize`.

| Command                 |
| ----------------------- |
| `\tiny`                 |
| `\scriptsize`           |
| `\footnotesize`         |
| `\small`                |
| `\normalsize` (default) |
| `\large`                |
| `\Large`                |
| `\LARGE`                |
| `\huge`                 |
| `\Huge`                 |